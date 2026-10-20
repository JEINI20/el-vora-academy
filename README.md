# EL-VORA Academy — Multi-page static website

## Pages
- `index.html`: home page in requested order: top navigation, course links, learning stages, learning feeds, About section last, then footer.
- `courses.html`: separate course details and enquiry links.
- `levels.html`: Beginner, Intermediate and Professional stages.
- `learning.html`: learning feeds/skills.
- `why-us.html`: academy benefits.
- `about.html`: full About page.
- `contact.html`: phone, WhatsApp, email and Instagram.
- `enquire.html`: enquiry form opens the visitor's email or WhatsApp app with a pre-filled message.
- `terms.html`: clear Terms & Conditions covering fees, offers, older advertisements and confirmed enrollments.

## Run and deploy
Open `index.html` locally, or upload the project folder to Netlify, Vercel or GitHub Pages. No QR section is included; create a QR separately after publishing with the final website URL.

## Splash image
The home page currently has a temporary text-based splash screen that appears for two seconds once per browser session. When you provide the real splash image, add it to the folder and replace the splash markup in `index.html`.

## Important
This is a static front-end. It does not provide real email login, private student accounts, saved enquiries or attendance tracking. Those features need Supabase/Firebase authentication and a database with secure access rules. The current enquiry form opens email/WhatsApp; the visitor still needs to press Send.
