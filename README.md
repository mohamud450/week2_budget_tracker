# Personal Budget & Expense Tracker — Week 2

## Project overview
This project is a static Personal Budget & Expense Tracker built with HTML and CSS. It extends the Week 1 project by adding a structured expense table, an improved expense form, multimedia content, and interactive page elements.

## Files
- `index.html` — contains the page structure, budget overview, expense form, sample expense table, collapsible help section, image, and embedded video.
- `style.css` — controls the page layout, colors, form styling, table borders, alternating table rows, hover effects, focus states, and responsive layout.

## What I built

### 1. Expense table
The expenses section uses a `<table>` with `<thead>` and `<tbody>`. It has four columns (Name, Amount, Category, Date) and five sample expense records. CSS uses `border-collapse: collapse`, cell padding, a colored header, and `tr:nth-child(even)` for alternating row colors.

### 2. Add Expense form
The form includes fields for expense name, amount, category, and date. The category `<select>` has five categories: Food, Transport, Rent, Entertainment, and Other. Each field has a matching `id` and `label`. The Add Expense button uses `type="button"` as required. It is a visual placeholder and does not add records yet.

### 3. Multimedia
An image is displayed beside the main heading with `src`, `alt`, and `width` attributes. A YouTube video is embedded using an `<iframe>` with width, height, title, and frameborder attributes.

### 4. Interactive elements
A `<details>` and `<summary>` element creates a collapsible help section. Table rows change color on hover, and the Add Expense button uses `cursor: pointer`.

### 5. Advanced CSS selectors
The stylesheet demonstrates:
- Descendant selector: `.expenses-section th, .expenses-section td`
- Direct child selector: `.add-expense-section > form > button`
- Positional pseudo-class: `.expenses-section tbody tr:nth-child(even)`
- Negation pseudo-class: `input:not([type="submit"])`
- Focus pseudo-class: `input:focus`
- Hover pseudo-class: `.expenses-section tbody tr:hover`

## How to view the project
1. Download and extract the ZIP file.
2. Open the `week2_budget_tracker` folder.
3. Double-click `index.html` or open it in a web browser.
4. Keep `index.html` and `style.css` in the same folder.

## Notes
This is a static HTML and CSS assignment. The Add Expense button is not connected to JavaScript yet, as functionality is planned for a later week. The image and embedded video require an internet connection to load.
