# Static Blog Project - Conversion Result

This project has been converted from a complex multi-directory structure into a clean, standard static HTML/CSS/JS site.

## Project Structure

- `index.html`: The main landing page (Personal Blog Landing Page).
- `archive.html`: The blog post list page (Blog Archive Index).
- `article.html`: The detailed blog post view (Blog Article Detail View).
- `images/`: A centralized folder containing all image assets used across the pages.
- `screen_images/`: Contains screen captures for each page (`index_screen.png`, `archive_screen.png`, `article_screen.png`).
- `README.md`: This documentation.

## Legacy Content
The original `stitch` directory and its subfolders have been removed as all content has been successfully migrated to the root and reorganized.

## How to Run

Simply open `index.html` in any modern web browser. No local server or build system is required.

## Key Changes Made

1. **Asset Localization**: All images that were previously hosted on Google servers (`lh3.googleusercontent.com`) have been downloaded and saved locally in the `images/` directory.
2. **Path Refactoring**: All `<img>` tags and CSS `background-image` properties have been updated to point to the local files in `./images/`.
3. **Internal Navigation**: Fixed all navigation links (Header menu, "Read Latest" buttons, "View All" links) to allow seamless navigation between the three static pages.
4. **Tailwind CSS**: Maintained the Tailwind CSS CDN approach for maximum portability and ease of customization without a build step.
5. **Code Cleanup**: Removed directory-specific wrappers and unified the pages at the project root for a flatter, more standard structure.
