# StudyLink — updated demo source

This extends the original plain HTML, CSS, and JavaScript StudyLink project. No framework, dependency installation, or build step is required.

## Open the demo

Open `dist/index.html` in a modern browser. Alternatively, serve `dist` with any static web server. Hash-based routes work on static hosting without rewrite rules.

- Landing page: `#/`
- Login: `#/login`
- Sign up: `#/signup`
- Password reset preview: `#/forgot`
- Student dashboard: `#/dashboard`
- Dashboard sections: `#/dashboard/tutors`, `#/dashboard/materials`, `#/dashboard/sessions`, `#/dashboard/subscription`, `#/dashboard/profile`

Use any sample email and a password of at least 8 characters. Sign-up requires a matching confirmation, a role, and the demo terms checkbox. “Just exploring?” opens the dashboard directly.

## Included behavior

- Responsive account pages with password visibility toggles and form validation.
- Remember-email preference using localStorage; a reset-flow explanation without sending email.
- Student/Tutor role selection; both open the student preview, with a notice for Tutor.
- Dashboard overview and working section navigation, session-detail dialogs, tutor profile, subscription details, progress, and quick actions.
- Downloadable original sample learning resources as TXT files.
- Editable profile held in memory until refresh; log out resets the profile.
- Working landing-page tutor search and mobile navigation.
- Keyboard focus indicators, labels, native modal dialogs, reduced-motion support, and screen-reader status messages.

## Demo boundaries

This is a frontend demo, not production authentication. Passwords are neither stored nor transmitted, and login does not verify credentials. Only the optional remembered email is saved on this device. Profile changes are in memory. Dashboard figures, people, sessions, dates, and subscriptions are sample data frozen to 7 September 2026. Payments, bookings, reset emails, and real tutoring services are not connected. Download examples are original sample text, not official examination papers.

Google Fonts supplies the original DM Sans and Manrope fonts when online; system fallbacks remain available offline.

## Files

- `dist/index.html`: original landing page and document metadata.
- `dist/styles.css`: original design plus responsive account and dashboard styles.
- `dist/app.js`: routing, forms, demo data, and interactions.
- `.openai/hosting.json`: original Sites project association retained.

The existing hosted publication has not been changed. This package is the updated source deliverable.
