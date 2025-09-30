# Book Store — HTML / CSS / JavaScript

**Overview**
A simple web project for an online Book Store. The website allows users to browse books, search by title/author, filter by categories, and manage a shopping cart. Built entirely with **HTML**, **CSS**, and **Vanilla JavaScript** — no frameworks used.

## Features

* Display a list of books with cover image, title, author, and price.
* Live search by title or author.
* Filter by category (e.g., Novels, Technical, Self-Help).
* Book detail view (modal or separate page).
* Simple shopping cart (add/remove items, update quantity, calculate total).
* Responsive design for desktop, tablet, and mobile.
* Local storage support to save cart or favorites between visits.

## Tech Stack

* HTML5
* CSS3 (Flexbox / Grid, Media Queries)
* JavaScript (ES6+)
* `localStorage` for persisting cart/favorites

## Getting Started

1. Clone the repo or download the files.
2. Open `index.html` directly in your browser.
3. (Optional) Run with a local server:

```bash
# Using Python 3
python -m http.server 5500
# Open http://localhost:5500
```

## Project Structure

```
book-store/
├─ index.html
├─ css/
│  └─ styles.css
├─ js/
│  └─ app.js
├─ assets/
│  └─ cover1.jpg
└─ README.md
```

## JavaScript Functions (examples)

* `renderBooks(books)` — renders the book list.
* `searchBooks(query)` — filters books by search input.
* `addToCart(bookId)` & `removeFromCart(bookId)` — manage shopping cart items with `localStorage`.
* `updateCartUI()` — updates cart counter and total in the UI.

## Future Improvements

* Connect to a backend or database (Firebase, Node.js + MongoDB, etc.).
* Admin panel for adding/editing/removing books.
* Reviews and ratings per book.
* Mock payment or integration with a payment gateway.
* Improved UI/UX with SVG icons or icon libraries.

## Contributing

1. Fork the project.
2. Create a new branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request.

## License

Educational/demo project. You can add an [MIT License](https://opensource.org/licenses/MIT) or another license of your choice.

---
