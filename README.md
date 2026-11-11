# vcrg-send

Upload page for the Veridata Compliance Research Group mailer. Homeowners scan the QR code and send copies of the pre-foreclosure solicitations they receive.

Live: https://veridatacompliance.github.io/vcrg-send/ (also /send/)

## How uploads work
The form posts to FormSubmit, which emails each submission (with photos) to ashlee@veridatacompliance.org. The first submission triggers a one-time activation email to that inbox; click the link once or later submissions are held.

## Files
- index.html: the upload page
- thanks.html: shown after a submission
- send/: identical copies, so a custom domain's /send path also works
