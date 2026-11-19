PHO VIET DELIGHT — FEEDBACK PAGE

FILES
- index.html: complete responsive feedback website (HTML, CSS and JavaScript in one file)

DEPLOY WITH GITHUB + NETLIFY
1. Create a new GitHub repository (for example: pho-viet-delight-feedback).
2. Upload index.html to the ROOT of the repository (not inside an extra nested folder).
3. In Netlify, choose Add new site > Import an existing project, connect GitHub, and select the repository.
4. For a plain HTML site, leave Build command blank and set Publish directory to . (a single dot).
5. Deploy the site.
6. In Netlify, open Forms. Confirm that the form named "private-feedback" is detected after deployment. If it is not detected, trigger a new deploy after ensuring index.html contains the static form markup.
7. In Netlify, open Forms > private-feedback > Settings/Notifications (wording may vary) and add the owner's email under email notifications. Netlify collects submissions; the owner email notification must be configured in the dashboard.
8. Test the live site: select 1–3 stars and submit a test; verify it appears in Netlify Forms and the owner receives the configured notification. Test 4–5 stars to verify the Google listing opens.

HOW IT WORKS
- 1, 2, or 3 stars reveal the private Netlify form. Name and comments are required; email is optional.
- 4 or 5 stars redirect directly to the supplied Google Maps listing.
- The form includes a honeypot field to help reduce spam.

IMPORTANT
- No owner email was supplied, so it has not been hardcoded. Add the owner's email as a Netlify form notification after deployment.
- Netlify Forms must be enabled for the site. Test a real deployed URL; form submissions will not work by opening index.html directly from your computer.
- The hero uses a remotely hosted Unsplash image and Google Fonts, so those visual assets need an internet connection. You can replace the image URL in the CSS if desired.
