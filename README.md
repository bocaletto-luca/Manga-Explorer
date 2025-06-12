# Manga Explorer – Complete Edition | API Free | WebAPP  
#### Author: Bocaletto Luca

[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?style=flat)](https://developer.mozilla.org/en-US/docs/Web/HTML) [![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?style=flat)](https://developer.mozilla.org/en-US/docs/Web/CSS) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Bootstrap 5](https://img.shields.io/badge/Bootstrap-7952B3.svg?style=flat)](https://getbootstrap.com/) [![License: GPL](https://img.shields.io/badge/License-GPL-blue.svg)](LICENSE)

#### index.html
[![Test Online](https://img.shields.io/badge/Test%20Online-Click%20Here-brightgreen?style=for-the-badge)](https://bocaletto-luca.github.io/Manga-Explorer/index.html)
#### index2.html
[![Test Online](https://img.shields.io/badge/Test%20Online-Click%20Here-brightgreen?style=for-the-badge)](https://bocaletto-luca.github.io/Manga-Explorer/index2.html)

## Overview

**Manga Explorer – Complete Edition** is a professional web application built entirely using free APIs. It allows users to discover manga through multiple search modes, including:
- **Search by Name:** Enter a manga title to retrieve and paginate all matching results.
- **Search by Letter:** Browse through an A–Z menu that filters manga titles by their starting letter and orders them by score in descending order.
- **Filter by Genre:** Choose a genre from a dropdown to see all manga within that genre, sorted from highest to lowest score.
- **Top 100 Rated:** Explore the top 100 rated manga, and view a horizontal bar chart that visualizes the Top 10 rated titles.

Detailed manga information (cover, synopsis, genres, authors, and chapter count) is available in a fullscreen modal when you click on any manga card. The cover images are displayed in a tall container ensuring the full image is visible (using `object-fit: contain`).

## Features

- **Multiple Discovery Modes:**  
  - *Search by Name:* Uses a query parameter to return a paginated list matching your search.  
  - *Search by Letter:* Fetches a broad dataset from many API pages, filters that dataset by the first letter (case-insensitive), sorts the results by score (highest first), and paginates them.  
  - *Filter by Genre:* Retrieves manga across multiple pages for the selected genre and sorts the results by score (descending).  
  - *Top 100 Rated:* Aggregates multiple pages sorted by score, then displays the top 100 manga along with a Top 10 horizontal bar chart.
  
- **Enhanced Visuals:**  
  - Full cover images are displayed in a 350px tall container with `object-fit: contain` to prevent cropping.  
  - A colored header and horizontal navigation menu with green buttons provide a polished, modern look.

- **Detailed Manga View:**  
  Clicking any manga card opens a fullscreen modal with extended details, including cover image, synopsis, genres, authors, and chapter information.
  
- **Responsive and Modern Design:**  
  Built with HTML5, CSS3, JavaScript, and Bootstrap 5 for optimal performance across devices.

- **Bilingual Code Comments:**  
  All code is commented in both English and Italian for clarity and collaboration.

## Usage

1. **Navigation:**  
   Use the horizontal navigation menu at the top to switch between modes:
   - **Search by Name**
   - **Search by Letter**
   - **Filter by Genre**
   - **Top 100 Rated**

2. **Search by Name:**  
   Enter a manga title in the search field and click "Search" to view matching results in a paginated grid.

3. **Search by Letter:**  
   Click on a letter (A–Z) in the alphabet menu to retrieve a large dataset from multiple pages. The app then filters by the selected letter and sorts results by score, displaying them with pagination.

4. **Filter by Genre:**  
   Select a genre from the dropdown menu and click "Filter." The app collects manga from multiple API pages, sorts the filtered results by score in descending order, and paginates them.

5. **Top 100 Rated:**  
   Click "Load Top 100" to view the highest rated manga, paginated with a horizontal bar chart (using Chart.js) displaying the Top 10 rated titles by score.

6. **Manga Details:**  
   Click on any manga card to open a fullscreen modal that shows detailed information (full cover, synopsis, genres, authors, and chapters).

## Technologies Used

- **HTML5** – Structured and semantic markup.
- **CSS3** – Styling and responsive design.
- **JavaScript** – Dynamic features and API integration.
- **Bootstrap 5** – Modern, responsive interface components.
- **Chart.js** – Rendering the Top 10 rated manga chart.
- **Jikan API v4** – Provides manga data from MyAnimeList:
  - Search by Name: `https://api.jikan.moe/v4/manga?q={query}&page={page}`
  - General List: `https://api.jikan.moe/v4/manga?page={page}`
  - Filter by Genre: `https://api.jikan.moe/v4/manga?genres={genreID}&page={page}`
  - Top Rated: `https://api.jikan.moe/v4/manga?order_by=score&sort=desc&page={page}`
  - Manga Details: `https://api.jikan.moe/v4/manga/{id}`

## Contributing

Contributions are welcome! Fork the repository, open an issue for any bug reports or feature suggestions, and submit pull requests. Let's work together to make this Manga Explorer even better.

## License

This project is licensed under the **GPL License**. See the [LICENSE](LICENSE) file for details.

## About the Author

**Bocaletto Luca**  
GitHub: [bocaletto-luca](https://github.com/bocaletto-luca)

Manga Explorer is developed by Bocaletto Luca, a passionate advocate for creating 100% free, open source, and open data web applications.

---

Enjoy exploring your favorite manga with comprehensive discovery modes and professional design – oh yeah friend!
