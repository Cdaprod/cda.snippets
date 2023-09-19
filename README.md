[![Jekyll site CI](https://github.com/Cdaprod/cda.snippets/actions/workflows/jekyll-docker.yml/badge.svg)](https://github.com/Cdaprod/cda.snippets/actions/workflows/jekyll-docker.yml) 
[![Deploy static content to Pages](https://github.com/Cdaprod/cda.snippets/actions/workflows/static.yml/badge.svg)](https://github.com/Cdaprod/cda.snippets/actions/workflows/static.yml)

[Demo Site Page](https://ghpages.cdaprod.dev/cda.snippets/)

A vanillajs web app for locally managing my snippets which i use directly from my Files app on IOS. 

Easy Import from apps like [ShellFish IOS application](https://apps.apple.com/app/id1336634154).

This keeps your snippets saved locally, so to avoid putting your secrets on the web!

If you use an application like [WorkingCopy](https://apps.apple.com/app/id896694807) then you can even avoid saving them to your browser and view your `localStorage.json` file directly from your directory!

---

# Snippet App Web UI

A user-friendly and modular web application that enables users to effortlessly create, import, and export code snippets. With a simplistic design and intuitive user interface, the Snippet App also offers the added advantage of caching snippets using the browser's local storage for quick access.

## Features

- **Create Snippets**: Easily add new snippets right from the main dashboard.
- **Import Snippets**: Import your pre-existing snippets from a JSON file.
- **Export Snippets**: Download your snippets in a JSON format.
- **LocalStorage Cache**: Your snippets are automatically saved to the browser's local storage, ensuring that they are available even after you close the tab or browser.
- **Simplistic UI**: A clean, intuitive, and distraction-free design that focuses on user experience.
- **Modular Design**: Designed with modularity in mind, making it easy to expand or integrate into other projects.
- **Responsive**: Works seamlessly across devices, be it desktop or mobile.

## Usage

1. **Adding a New Snippet**: 
   - Click on the "New Snippet" button.
   - Provide a description and the actual snippet content.
   - Click save.

2. **Searching for Snippets**:
   - Use the search bar at the top to quickly filter and find snippets based on their description or content.

3. **Importing Snippets**:
   - Click on the "Import" button.
   - Choose a `.json` file that contains your snippets.
   - The snippets will be automatically added to your existing collection.

4. **Exporting Snippets**:
   - Click on the "Export" button.
   - Your snippets will be downloaded in a `.json` format.

5. **LocalStorage**:
   - Your snippets are automatically saved in the browser's local storage.
   - They'll be available for you the next time you access the app, even if you close the browser or tab.

## Technical Details

- **Framework**: The app utilizes Tailwind CSS for its styling, ensuring a sleek and modern design.
- **Storage**: Snippets are stored in the browser's local storage for persistence and quick access.

## Contributions

Contributions are always welcome! If you find a bug or would like to add a feature, feel free to create a pull request.

## License

MIT

---

Feel free to fork and modify or expand upon this template to better suit the specifics of your application or personal style!
