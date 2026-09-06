# Felopater & Ledia — Engagement Invitation

A bilingual engagement invitation with an animated envelope, butterflies, botanical decorations, and a responsive optional message form.

- `index.html`: English by default.
- `en.html`: English by default.
- Both pages include a language switch and embedded artwork.

Open either HTML file in a browser, or serve the repository as a static website.

## RSVP and music

Names and optional messages are submitted to the configured Formspree endpoint. Configure recipient emails and access in the Formspree dashboard. The form asks only for a required name and an optional message; ensure the Formspree workflow does not require a guest email. Success appears only after Formspree accepts the submission; errors preserve entered answers.

The supplied audio is embedded in each page. Music starts when the invitation is opened and loops; the bilingual music button can disable it before opening or pause/resume it afterward.
