# SMIU Events Portal

A responsive front-end university events portal concept for the SMIU Student Affairs Office. Students can explore events, view event information, discover societies, register for activities and contact the office.

> **Class project note:** Event dates, venue details, contact information, statistics and team profiles are demonstration/sample content. Replace them with verified details before final submission.

## Technologies
- HTML5 and CSS3
- Bootstrap 5.3.3 via official CDN
- Bootstrap Icons
- Vanilla JavaScript
- Git and GitHub

## Pages and features
- `index.html` – hero, featured-event carousel, upcoming event cards, benefits, statistics and footer.
- `events.html` – 10 event cards, title search, category filter, no-results feedback and event schedule table.
- `event-details.html` – Build-a-thon details, accordion and validated registration modal.
- `societies.html` – 8 society cards and society membership modal.
- `register.html` – responsive registration form with client-side validation and success feedback.
- `contact.html` – contact form, sample contact details, map placeholder and three team profile cards.

## Project structure
```text
smiu-events-portal/
├── index.html
├── events.html
├── event-details.html
├── societies.html
├── register.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   ├── main.js
│   ├── events.js
│   └── forms.js
├── images/
│   ├── events/
│   ├── societies/
│   └── team/
└── README.md
```

## Run locally
1. Download or clone the repository.
2. Open the project folder in VS Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension.
4. Internet access is needed to load Bootstrap, Bootstrap Icons and the remote Unsplash photos.

## Group members
Replace the placeholders below with the actual details of all three members.

| Member | Full name | Roll number | GitHub username | Responsibility |
|---|---|---|---|---|
| 1 | Member 1 – Full Name Abdul Wasay | YOUR-ROLL-NO SFS-24S-003 | @your-username | Homepage and contact |
| 2 | Member 2 – Full Name Moin | YOUR-ROLL-NO  BSE-24S-003| @your-username | Events and Event details |
| 3 | Member 3 – Full Name  Daniyal Ahmed| YOUR-ROLL-NO BSE-24S-041 | @your-username | Societies, and rigister |

## Responsive testing
Test at 360px, 768px and 1200px using Chrome DevTools device toolbar. Check the navigation, cards, forms, carousel, modal, table and horizontal overflow.

## GitHub collaboration process
1. The team leader creates one repository named `smiu-events-portal-groupname`.
2. Add all group members and instructor `Hassan-Raza0` as collaborators.
3. Each member clones the repository and creates a separate feature branch.
4. Commit work with descriptive messages and push the branch.
5. Open a pull request to `main`; another member reviews it and leaves a meaningful comment.
6. Address review feedback, then merge the approved pull request.
7. Repeat for all members. Do not develop directly on `main`.

### Suggested branches
- `feature/homepage`
- `feature/events-page`
- `feature/societies-contact`
- `feature/forms-validation`

### Merge conflict documentation
Complete this section only after a real shared-file conflict occurs during normal parallel development.

- **Cause:** Describe the two concurrent edits to `css/style.css`.
- **Affected files:** List the files shown by Git as conflicted.
- **Resolution:** Explain how both valid changes were reviewed and combined, then committed.
- **Learning:** Explain why pulling/rebasing regularly and communicating about shared files helps prevent conflicts.

## Screenshots
Add screenshots captured from your own browser before submission. Suggested files:
- `screenshots/home-desktop.png`
- `screenshots/home-mobile.png`
- `screenshots/events-page.png`
- `screenshots/societies-page.png`

Then embed them here, for example:
`![Homepage desktop](screenshots/home-desktop.png)`

## Important
This is a front-end demonstration. Forms validate in the browser only and do not save or transmit registrations. No database or backend is included.


