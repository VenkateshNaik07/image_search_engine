# Image Search Engine

This is a simple image search engine web application that utilizes the Unsplash API to fetch and display images based on user input. The application is built using HTML, CSS, and JavaScript.

## Files:

### 1. `index.html`

The main HTML file that structures the web page. It includes a form for user input, a display area for search results, and a "Show More" button for paginated image loading.

### 2. `style.css`

The CSS file defines the styling for the web page. It sets up the layout, colors, and responsiveness of the elements.

### 3. `script.js`

The JavaScript file contains the logic for interacting with the Unsplash API. It handles user input, makes API requests, and dynamically updates the web page with the fetched images.

## Usage:

1. Open `index.html` in a web browser.
2. Enter a search query in the input box.
3. Press the "Search" button to load images related to the query.
4. Click the "Show More" button to load more images in a paginated manner.

## API Key:

The application uses the Unsplash API to fetch images. The API key is stored in the `script.js` file. Make sure to replace it with your own valid Unsplash API key if you plan to deploy this application.

```javascript
const accessKey = "YOUR_UNSPLASH_API_KEY";
```

## Dependencies:

- [Poppins](https://fonts.google.com/specimen/Poppins): The chosen font for the web page.

## Notes:

- The application uses asynchronous JavaScript functions and the Fetch API to interact with the Unsplash API.
- Styling is done using a mobile-friendly approach, with responsive design considerations.
- The "Show More" button allows users to load additional images in batches.

Feel free to customize and enhance the application based on your needs.