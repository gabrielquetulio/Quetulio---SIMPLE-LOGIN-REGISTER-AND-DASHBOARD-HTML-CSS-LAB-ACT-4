[README.md](https://github.com/user-attachments/files/31401407/README.md)
# Login → Register → Dashboard (HTML/CSS Activity)

A simple, front-end-only Login, Register, and Dashboard flow built with plain HTML and CSS. This activity extends a previous Login/Dashboard exercise by adding a **User Registration page** (`register.html`).

## Live Pages

| Page | File | Purpose |
|---|---|---|
| Login | `login.html` | Entry point — user signs in |
| Register | `register.html` | New user creates an account |
| Dashboard | `dashboard.html` | Landing page after login |

## Tech Used

- HTML5 (semantic form elements)
- CSS3 (single shared stylesheet: `style.css`)
- Anchor tags (`<a>`) for all page-to-page navigation
- No backend / no database — this is a static front-end prototype

## Project Structure

```
auth-flow/
├── login.html
├── register.html
├── dashboard.html
├── style.css
├── README.md
└── USER_MANUAL.md
```

## User Flow

```
login.html  --(Register here)-->  register.html
register.html  --(Register button)-->  login.html
login.html  --(Login button)-->  dashboard.html
dashboard.html  --(Log out)-->  login.html
```

## How to Run

1. Clone or download this repository.
2. Open `login.html` directly in any web browser (no server or build step required).
3. Navigate between pages using the links and buttons on each screen.

## Notes

- Since this activity has no backend, form fields do not persist or validate data server-side — HTML5 `required` attributes provide basic client-side validation only.
- The Register button on `register.html` is implemented as an `<a>` tag (per activity requirements) that redirects to `login.html`.
- See `USER_MANUAL.md` for step-by-step usage instructions.
