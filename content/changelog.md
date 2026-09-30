# What's new

## 2.0.1

- Settings live in a file (settings.json in the app's data folder) and move there on their own from earlier versions. Settings → Storage can export them to a file and import them on another computer.
- About: a "Check for updates" button, and the Third-party licenses page now lists every component in the app, not only the models.
- The Windows installer shows the license terms, installs for the current user, and on uninstall removes the image cache and logs. Sidecars are never touched.

## 2.0.0

- CULL Free and CULL Pro. Free has every feature and culls up to 250 frames in one session. Pro has no limit. A license key goes in under Settings → License; "Remove license from this computer" takes it out again.
- The limit is decided by the app itself when a cull begins, on the whole staged set, so it holds whatever folders are opened.
- The 1.9.0 note about free Pro for copies installed before 2.0 no longer applies: CULL was not released before 2.0, and every copy starts on Free.

## 1.9.2

- About links to the website, and Report a problem can email support directly: cull.help@outlook.com.

## 1.9.1

- The first-cull hint floats over the bottom of the photo instead of sitting in the status bar, so it has room at every window size.
- About: "Licenses" is now "Third-party licenses", to tell it from the license terms.

## 1.9.0

- A welcome on first launch: the promise, the five keys, and your first folder. Hints in the status bar during your first cull, each gone once you have done it.
- What's new opens once after an update, from a line on the home screen. License terms and the privacy policy are in About and are shipped inside the app.
- Coming in 2.0: CULL Free and CULL Pro. Free culls up to 250 frames in one session; Pro has no limit. Everyone who installed before 2.0 gets Pro until the end of 2028, at no cost.

## 1.8.0

- Report a problem from About: what happened, what you expected, and diagnostics you can read before they leave your computer. With no report server set up yet, the report is saved as a file and shown in your file manager.
- A log file, kept on this computer (Settings → Storage → Open log folder). It never contains file or folder names, or paths: a path is reduced to its file extension before it is written. Diagnostic logging adds detail when you are asked for it.
- If CULL closes unexpectedly, the next start says so and offers to report it.

## 1.7.2

- Every message in the app reads the same way: what happened, then what to do. Backend details no longer appear on screen.
- About shows what's new and the licenses of bundled components.
- Spelling unified to American English (favorite, color).

## 1.7.1

- Updates are now delivered from a dedicated downloads repository.

## 1.7.0

- Olympus and OM System ORF files open, with the AF point and drive mode from the camera. Every Olympus body embeds a 3200 px preview, so zoom shows that preview and says so.
- Panasonic RW2 and Leica RWL files open. Bodies from 2022 on zoom to the full image; earlier ones zoom to their 1920 px preview.

## 1.6.1

- Faster opening of every frame and a cheaper folder scan.

## 1.6.0

- A DNG's verdicts are written inside the DNG, where Lightroom reads them, instead of to a sidecar it would ignore.

## 1.5.0

- Sony ARW, Nikon NEF and Fujifilm RAF files open, with the AF point and drive mode where the camera records them.
- A quiet badge shows when a file has no full-size JPEG inside it and zoom is limited to its largest preview.

## 1.4.0

- Adobe DNG files open, from any camera or converter.

## 1.3.0

- A favorite is written as Lightroom's purple label; stars are yours alone, and CULL never removes a label it did not write.

## 1.2.0

- Canon CR2 files open.

## 1.1.0

- Composition guides, the AF-point bracket, and a new icon.

## 1.0.0

- First release: keyboard-fast culling of Canon CR3 files with Lightroom-compatible verdicts, smart-culling suggestions, and automatic updates.
