# Google Search Frontend (CS50W Project 0)

This repository implements a multi-page frontend that mimics the behavior and appearance of Google Search, Google Image Search, and Google Advanced Search.  
The project follows all specifications from CS50W Project 0, including navigation links, page styling, query forwarding, and the “I’m Feeling Lucky” feature.

## Live Demo
[https://matheusesilva.github.io/google-search/](https://matheusesilva.github.io/google-search-page/)

## Features

### Multi-Page Structure
- **index.html** — Main Google Search page.  
- **image.html** — Google Image Search simulation.  
- **advanced.html** — Google Advanced Search interface.  
- Upper-right navigation links mirror Google’s layout:
  - Search → Images / Advanced  
  - Images / Advanced → Back to Search

### Google Search Page
- Centered search bar with rounded corners styled to resemble Google.
- Centered “Google Search” and “I’m Feeling Lucky” buttons below the input.
- Form submission redirects the user to actual Google search results using the query string.
- “I’m Feeling Lucky” sends the user directly to the first result (Google may display a redirect warning).

### Image Search Page
- Search form directing queries to Google Image Search.
- Layout and styling aligned with Google’s clean, minimal aesthetic.

### Advanced Search Page
- Four vertically stacked fields matching Google’s advanced search parameters:
  - All these words  
  - Exact phrase  
  - Any of these words  
  - None of these words  
- Left-aligned inputs and labels, consistent spacing and grouping.
- Blue “Advanced Search” button with white text, matching Google’s styles.
- Submitting the form constructs and redirects to a valid Google Advanced Search query.

### Styling
- CSS written to replicate Google’s layout philosophy:
  - Clean white space
  - Centered main content
  - Rounded inputs
  - Subtle shadows and minimalistic structure
- Consistent top-right navigation styling on all pages.

## How to Run
Open any of the HTML files in a modern browser, or deploy using GitHub Pages.

## License
This project is provided under the MIT license.
