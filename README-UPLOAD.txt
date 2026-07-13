WORXMAN WEBSITE UPDATE — FILE NAMES AND UPLOAD NOTES
======================================================

UPLOAD THESE FILES TO THE ROOT OF THE EXISTING GITHUB PAGES REPOSITORY:

Website files:
- index.html
- contact.html
- thank-you.html
- styles.css

New flyer image names:
- worxman-kitchen-transformation.png
- worxman-tub-tile-transformation.png
- worxman-hardwood-flooring-transformation.png
- worxman-custom-table-benches.png

WHAT THIS UPDATE CHANGES
------------------------
1. Changes every visible phone number to:
   801-709-1223

2. Removes the publicly displayed email address and replaces it with:
   Contact Us / Request an Estimate buttons.

3. Adds all four new flyers to a redesigned Recent Projects section.

4. Adds a dedicated contact page modeled on the straightforward FOTOC form:
   - First and last name
   - Email
   - Phone
   - Project location
   - Project type
   - Message
   - Human-verification question
   - Hidden honeypot field
   - CAPTCHA screening

5. Preserves the intended spelling and capitalization:
   WorXMan

CONTACT FORM ACTIVATION
-----------------------
The form uses FormSubmit because GitHub Pages cannot process email forms by itself.

After uploading:
1. Open https://worxman.pro/contact.html
2. Send one test submission.
3. FormSubmit will email a one-time activation link to:
   worxmanllc@protonmail.com
4. Approve the activation.
5. Send a second test message and confirm delivery.

The email is not visibly printed on the page, although it necessarily appears in the
form action within the source code. For stronger email-address concealment later,
replace FormSubmit with a Formspree form-ID endpoint.

EXISTING ASSETS
---------------
Keep the current favicon.png in the repository. If it has another name, either rename
it favicon.png or update the two HTML files.

DEPLOYMENT
----------
On GitHub:
1. Open the worxman-pro repository.
2. Upload/replace all files listed above.
3. Commit directly to the main branch.
4. Wait approximately 1–3 minutes.
5. Refresh worxman.pro with Ctrl+F5.
