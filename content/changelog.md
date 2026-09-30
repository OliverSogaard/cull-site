# What's new

## 2.1.1

- Help has a toggle: F1 opens the keys sheet and keeps it open until F1 or Esc. Holding Tab still shows it for as long as it is held.
- Updating no longer makes the next launch say CULL didn't close properly.
- A dialog opened with the mouse no longer lights up its first button; opened from the keyboard, it still starts on the safe choice.
- Settings → General: the default overlays row wraps instead of forcing a sideways scroll.
- Scrollbars match the app instead of the system's white ones.
- The recent folders list gives keyboard focus room around each row.
- What's new has space above its footer; over the Free limit, the staged screen no longer suggests adding folders. The keys sheet no longer shows a light seam under the title bar.

## 2.1.0

- Faster on big shoots: a rating no longer stalls for a moment while the smart suggestions catch up, scrubbing stays smooth while thumbnails fill in, and the loupe and compare panes stop repainting for changes behind them.
- Faster on a NAS: moving rejects does one file operation per frame instead of six, opening a shoot of DNGs no longer looks for a sidecar beside every file, filmstrip thumbnails read a tenth of the data, and cache hits copy nothing.
- Smart culling scores frames on several cores when the shoot is on a local drive.
- Rating, starring or labelling a DNG keeps its cached previews, so reopening a culled DNG shoot is instant again.
- A frame with no embedded preview (some DNGs, a CR2 without one) shows as unavailable in the grid instead of retrying forever.
- Capture-time order: a DNG whose XMP another tool had written, or a frame whose date sat right at a read boundary, could lose its capture time and sort by file date. Fixed.
- The Finish button in the status bar no longer reopens the dialog with the previous run's result.
- Copying keeps to an export folder flushes each file to disk before it counts as done, so a power cut cannot leave a truncated copy that later looks finished.
- Settings are saved a moment after the last change instead of on every change, and always before a quit, an export or an update.
- Keyboard: Ctrl R retries changes that didn't save and re-checks an unreachable folder. F6 moves focus between the frame, the status bars and the info rail; there, Enter and Space press a button, the arrows move between buttons, and Esc returns to the frame.
- Screen readers hear saving and failed saves, the folder and memory chips, analyzing progress, Finish results and a copied report. The grid and filmstrips are lists of named frames (verdict, stars, label). Dialogs keep focus inside and start on the safe choice, so Enter on Stay stays.
- With unsaved changes, the leave dialog and the Finish dialog offer Retry saving.
- Two-step confirms say what they do, wait 20 seconds, and cancel on Esc or when focus moves away. Windows says Recycle Bin.
- Wording: frames rather than ratings or images, Filmstrip, Finish the cull, Lightroom rating, key names like Ctrl E and Shift 3, Center guide, and error messages that say what to do next. Counts get thousands separators. Leica is named among the formats.
- Quieter text is brighter, and text fields have a visible border.
- Report a problem: one "Save as file", "Copied." feedback, and a note when no mail program opens.
- The license terms and privacy policy state what the app does today: a key is checked on this computer and nothing is sent. There is no trial, and the terms no longer mention one.
- Saving settings, adding or removing a license, and writing the log no longer run on the window's thread, so a slow drive cannot freeze the window.

## 2.0.1

- Settings live in a file (settings.json in the app's data folder) and move there on their own from earlier versions. Settings → Storage can export them to a file and import them on another computer.
- About: a "Check for updates" button, and the Third-party licenses page now lists every component in the app, not only the models.
- The Windows installer shows the license terms, installs for the current user, and on uninstall removes the image cache and logs. Sidecars are never touched.

## 2.0.0

- CULL Free and CULL Pro. Free has every feature and culls up to 250 frames in one session. Pro has no limit. A license key goes in under Settings → License; "Remove license from this computer" takes it out again.
- The limit is decided by the app itself when a cull begins, on the whole staged set, so it holds whatever folders are opened.

## 1.9.2

- About links to the website, and Report a problem can email support directly: cull.help@outlook.com.

## 1.9.1

- The first-cull hint floats over the bottom of the photo instead of sitting in the status bar, so it has room at every window size.
- About: "Licenses" is now "Third-party licenses", to tell it from the license terms.

## 1.9.0

- A welcome on first launch: the promise, the five keys, and your first folder. Hints in the status bar during your first cull, each gone once you have done it.
- What's new opens once after an update, from a line on the home screen. License terms and the privacy policy are in About and are shipped inside the app.

## 1.8.0

- Report a problem from About: what happened, what you expected, and diagnostics you can read before they leave your computer. With no report server set up yet, the report is saved as a file and shown in your file manager.
- A log file, kept on this computer (Settings → Storage → Open log folder). It never contains file or folder names, or paths: a path is reduced to its file extension before it is written. Diagnostic logging adds detail when you are asked for it.
- If CULL closes unexpectedly, the next start says so and offers to report it.

## 1.7.2

- Every message in the app reads the same way: what happened, then what to do. Error messages no longer show technical details.
- About shows what's new and the licenses of bundled components.
- Spelling unified to American English (favorite, color).

## 1.7.1

- Updates download faster and more reliably.

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
