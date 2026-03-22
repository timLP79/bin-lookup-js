# BIN Lookup Tool

A client-side web application for searching Bank Identification Numbers (BINs) from a comprehensive database. No backend required.

[Live Demo](https://timlp79.github.io/bin-lookup-js/)

---

## Tech Stack

- JavaScript (ES6+)
- HTML5
- CSS3

---

## Features

- Search by BIN number prefix
- Keyword search across all columns with AND logic
- Paginated results with configurable page size
- Real-time results with no backend or server required
- All data loaded once and cached in the browser

---

## Getting Started

Open `index.html` in any modern browser. The tool will fetch and cache the BIN dataset automatically on load.

---

## How to Use

### BIN Search

1. Click the **BIN Search** tab
2. Enter a BIN number or partial BIN (e.g. `414720`)
3. Set results per page and click **Search**
4. Navigate results with the pagination controls

### Keyword Search

1. Click the **Keyword Search** tab
2. Enter one or more space-separated keywords (e.g. `visa credit usa`)
3. All keywords must match (AND logic)
4. Set results per page and click **Search**

---

## Technical Details

### Data Source

BIN data is loaded from:

```
https://raw.githubusercontent.com/venelinkochev/bin-list-data/refs/heads/master/bin-list-data.csv
```

Requires an internet connection on first load. The CSV must be accessible via a CORS-enabled URL.

### Browser Compatibility

Requires ES6+, Fetch API, CSS Grid, and Flexbox. Works on all modern browsers (Chrome 60+, Firefox 55+, Safari 11+, Edge 79+).

---

## Project Structure

```
bin-lookup-js/
├── index.html      # Main HTML structure
├── styles.css      # Custom CSS styling
├── script.js       # Application logic
└── README.md
```

---

## Customization

Colors and theming are controlled via CSS variables in `styles.css`. Edit the `:root` block to change the color scheme.

---

## Credits

- BIN data: [venelinkochev/bin-list-data](https://github.com/venelinkochev/bin-list-data)

---

## Contact

- Email: timpalacios@u.boisestate.edu
- GitHub: [@timLP79](https://github.com/timLP79)
- LinkedIn: [tim-palacios](https://www.linkedin.com/in/tim-palacios/)
