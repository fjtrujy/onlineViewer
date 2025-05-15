# onlineViewer
Dummy web app with a video tag

# Video Player

A simple static website that displays video content from blob URLs passed as query parameters.

## Usage

To use the video player, simply append a blob URL as a query parameter to the page URL:

```
https://[your-github-username].github.io/[repository-name]/?video=blob:https://example.com/your-blob-id
```

Example:
```
https://username.github.io/onlineViewer/?video=blob:https://streamtp4.com/fdd553ec-c945-4d23-97aa-bce4a891ff58
```

## Features

- Responsive video player
- Automatic validation of blob URLs
- Error handling for invalid or missing URLs
- Automatic deployment to GitHub Pages

## Development

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch. The deployment is handled by GitHub Actions.

## Local Development

To run the site locally, simply open the `index.html` file in a web browser. No build process is required as this is a static site.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
