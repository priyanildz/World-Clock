## World Clock

World Clock is a lightweight frontend web application that displays real-time local and global times across multiple countries. Built using HTML, CSS, and vanilla JavaScript, it provides a clean and responsive interface to explore time zones efficiently.

---

## Live Demo

https://priyanildz.github.io/World-Clock/

---

## Features

- Real-time local clock display
- View current time for multiple countries
- Search and filter countries dynamically
- Dropdown-based country selection
- Responsive dark-themed UI
- No backend or external dependencies

---

## Tech Stack

- HTML5
- CSS3 (Flexbox, Media Queries)
- JavaScript (Vanilla)
- Browser API: Intl.DateTimeFormat

---

## Project Structure

```bash

World-Clock/
│
├── index.html
├── README.md
└── .nojekyll

```

---

## How It Works

- Uses JavaScript `Date` object to fetch current time
- Uses `Intl.DateTimeFormat` to format time based on selected timezone
- Updates time every second using `setInterval`
- Dynamically filters country list based on user input

---

### Run Locally

1. Clone the repository:
   
   git clone https://github.com/priyanildz/World-Clock.git


2. Navigate to the project folder:

   ```bash
   cd World-Clock
   ```

3. Open the project:

   ```bash
   open index.html
   ```

---

## Deployment

This project is deployed using GitHub Pages.

To deploy:

1. Push your code to GitHub
2. Go to Settings → Pages
3. Select:

   * Source: Deploy from branch
   * Branch: main
   * Folder: / (root)

---