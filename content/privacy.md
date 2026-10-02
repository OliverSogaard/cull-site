# Privacy policy

Version 1 · September 2026

This policy is written in plain language.

## The short version

CULL runs on your computer. Your photographs, your verdicts and your settings stay there. Nothing leaves your computer unless you send it, and you can read everything before you do.

## What CULL keeps on your computer

- Your settings, your recent folders, your license key and its current confirmation, in the app's own data folder.
- A log file that records what the app did, for troubleshooting. Before a line is written, every file and folder path in it is reduced to its file extension. The log never contains a name of yours, of a client, or of a folder.
- Verdicts, written next to your photographs as XMP sidecar files, or inside a DNG, where Lightroom reads them.

## What leaves your computer, and when

- **Update check.** When CULL starts, it asks GitHub, where releases are hosted, for the newest version. As with any web request, GitHub sees your IP address; the request carries nothing else about you or your photographs.
- **A problem report.** Only when you send one. It contains what you typed, and, if you tick the box, diagnostics: the app version, your operating system, counts of file types in the shoot, your settings without any path, and the last lines of the log. The whole report is shown to you before it leaves, and paths are reduced to file extensions once more on the way out. Pressing Send delivers it to CULL's report endpoint, which runs on Cloudflare and stores it as a private issue in a GitHub repository that only the author can read; you get a ticket number back. The endpoint accepts five reports a minute from one address and keeps nothing else about you. You can instead save the report as a file, copy it, or send it by email through your own mail program. The email address is optional and is used only to reply.
- **Adding a license, and about every twelve hours after that.** A license key works on two computers, so when you add one, CULL tells the license service, which runs on Cloudflare and is operated by the author, which computer this is: the key, an identifier derived from this installation and this machine, the computer's name as your operating system reports it, which operating system it is, and the app version. The service answers with a signed confirmation that is good for 30 days, and CULL renews it in the background about every twelve hours when it is online. Nothing else is sent: no photographs, no paths, no settings. As with any web request, the service sees your IP address, which it uses only to limit how often one address may call it. The service keeps the key, the email address the key was bought or issued for, the computers using it with the dates they were last seen, and a log of changes to the license, for as long as the license exists. You can see and remove the computers using your key in Settings → License.

CULL sends no usage statistics and no crash reports on its own, and it never uploads a photograph or a thumbnail.

## Where reports go

A report you send is kept by the author in a private issue tracker (GitHub) or, if you emailed it, in a mailbox, either of which only the author can read, for as long as the problem is open and then for up to two years, so that a returning problem can be recognized. Cloudflare and GitHub process the report on the author's behalf under their own privacy terms; neither receives your photographs.

## Your rights

You can see what CULL keeps: Settings → Storage opens the log folder, and a report is saved as a readable file. You can delete the data folder at any time; the app then starts as new. If you have sent a report and want it deleted, write to the support address shown in the app, under About, and it will be removed.

Under the GDPR you also have the right to access, correct and export personal data held about you, and to complain to your data protection authority.

## Changes

When this policy changes, the new version, with its date at the top, is in About, and what's new says that it changed.

## Contact

The author, Oliver Søgaard-Andersen, is the data controller. Reach him at the support address shown in the app, under About.
