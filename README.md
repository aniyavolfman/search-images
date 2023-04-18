# Image Search App
## Briefly about the application:

A site for searching and loading images by query. 
With pagination. With information about each image such as amount of likes, views, comments etc. 
With the possibility of flipping slides in the gallery.

## Technology stack: 
- HTML, 
- CSS, 
- JavaScript, 
- Parcel (for building and serving the app), 
- REST API (for retrieving images), 
- GIT (for version control).

## Installation

Clone the repository:

```bash
git clone https://github.com/aniyavolfman/search-images.git
```
Install the dependencies:

```bash
npm i
```
Start the application:
```bash
npm start
```
## How to use:

To use the app, simply enter a search query in the input field and press the "Search" button. The app will retrieve a list of images related to your query from the Pixabay API and display them on the page. You can load more images using the Load more button at the bottom of the page.

## Error Handling

If an error occurs during the search or loading of images, the app will display a message using Notiflix to notify the user. 

For example, if the user enters an invalid search query or if there is a problem with the API request, the app will display an error message using Notiflix. 
Similarly, if the search is successful, the app will display a notification message using Notiflix.
