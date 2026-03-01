# CSS Folder

This folder contains all the stylesheets for the LibraryHub application.

## Files

| File | Description |
|------|-------------|
| `style.css` | Global base styles — CSS custom properties (design tokens), typography, layout helpers, sidebar, header, navigation, buttons, badges, tables, modals, and responsive utilities shared across all pages. |
| `login.css` | Styles specific to the login page (`index.html`) — login card, form inputs, and the animated background. |
| `dashboard.css` | Styles for the dashboard page (`dashboard.html`) — KPI stat cards, charts grid, and activity feed. |
| `books.css` | Styles for the books catalogue page (`books.html`) — book cards, search bar, and filter controls. |
| `members.css` | Styles for the members management page (`members.html`) — member list, member cards, and related UI components. |
| `issues.css` | Styles for the issue/return page (`issues.html`) — issue forms, return forms, and transaction history table. |

## Usage

Each HTML page imports `style.css` first (for shared base styles) and then its own page-specific stylesheet:

```html
<link rel="stylesheet" href="css/style.css">
<link rel="stylesheet" href="css/<page>.css">
```
