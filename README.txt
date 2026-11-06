SMART MAINTAIN – BPCL Gonda LPG Plant
Initial scope: LPG pump motors and LPG compressor motors.

DEPLOYMENT ON GITHUB PAGES
1. Open your SMART-MAINTAIN GitHub repository.
2. Open the repository root (click SMART-MAINTAIN in the breadcrumb until you see the root file list).
3. Add file -> Upload files.
4. Upload this index.html directly into the repository root. If GitHub asks whether to replace the existing index.html, confirm the replacement.
5. Commit changes to the main branch.
6. Repository Settings -> Pages -> Deploy from a branch -> main -> /(root) -> Save.
7. Wait for Pages to publish, then open https://frootyrithikesh.github.io/SMART-MAINTAIN/ .

FEATURES IN THIS VERSION
- Equipment register for the five motor entries extracted from the supplied Excel.
- Equipment profile, QR label and QR deep-link to the selected equipment profile.
- Camera scanner (browser/device support and camera permission required) plus manual equipment ID lookup.
- Edit equipment details.
- AMC contract start date and exact contractual expiry date entered by the user (never auto-calculated or overwritten), total visits agreed, visits given (calculated from saved AMC visit records), and visits remaining.
- Edit AMC contracts without deleting historical visit records.
- AMC service visit history, PM and breakdown logs.
- Team Gonda member directory with add/edit and photo upload.
- AMC expiry reminder preferences and a mailto reminder draft.

IMPORTANT LIMITATIONS
This is a static GitHub Pages version. It saves records in the browser's local storage on the device where they are entered. It does not synchronize records across multiple phones/computers. Clearing browser data can erase locally stored records; export/back up records regularly.

Email reminders: this version can prepare an email in the user's mail application when the reminder button is clicked. It cannot send scheduled automatic emails in the background. Fully automatic email reminders and shared multi-user records require a secured cloud database and email-sending backend.

QR labels: print QR labels after opening the deployed website. QR labels contain the GitHub Pages URL and the equipment ID. For equipment records added on one device to open on another device, the devices must share the same cloud database; local-only records are not shared.

The equipment photographs shown in the app are illustrative drawings unless a real photograph is uploaded. Verify equipment identity, nameplate details, contract details and approved maintenance frequencies before operational use.
