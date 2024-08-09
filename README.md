# Image Search Engine

Welcome to the **Image Search Engine** project! This project is a simple and intuitive web application that allows users to search for images by entering a keyword. The images are fetched from the Unsplash API and displayed in a visually appealing grid format. Users can load more images with a single click to explore further.

## Project Overview

### Features
- **Search Functionality:** Enter a keyword and retrieve a collection of images related to your search.
- **Dynamic Image Grid:** Images are displayed in a clean, responsive grid layout that adapts to different screen sizes.
- **Load More Images:** If the initial results aren't enough, simply click "Show More" to load additional images without refreshing the page.
- **Interactive Links:** Each image is linked to its source on Unsplash, allowing users to explore the original content in detail.

## Technologies Used

### 1. HTML5
   - Provides the basic structure of the web page, ensuring semantic and accessible content.

### 2. CSS3
   - Styles the application, creating a user-friendly interface with a modern, clean design. The CSS includes a responsive layout, ensuring the application works well on various devices.

### 3. JavaScript (ES6+)
   - Implements the core functionality of the project. JavaScript is used to handle form submissions, make API requests to Unsplash, and dynamically render the images on the page.

### 4. Unsplash API
   - A powerful API that provides access to high-quality images. The Unsplash API is used to fetch images based on the search query entered by the user.

## How It Works
1. **Search Form:** Users enter a keyword in the search box and submit the form. The form submission triggers an API request to Unsplash.
2. **API Request:** The JavaScript code makes an asynchronous request to the Unsplash API, retrieving images related to the keyword.
3. **Display Images:** The retrieved images are displayed in a grid format. Each image is clickable and links to its source on Unsplash.
4. **Load More:** If the user wants to see more images, they can click the "Show More" button, which loads additional images from Unsplash.

## How to Run the Project

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/image-search-engine.git
