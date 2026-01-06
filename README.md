# Profilo Neocities Site

Welcome to the Profilo Neocities Site project! This project is designed to create a simple and engaging website hosted on Neocities. Below you will find information about the project structure, setup instructions, and usage.

## Project Structure

The project consists of the following files and directories:

- `public/`
  - `index.html`: The main entry point of the website.
  - `about.html`: A page providing information about the site or its creator.
  - `css/`
    - `styles.css`: The stylesheet for the website.
  - `js/`
    - `main.js`: The JavaScript file for client-side interactivity.

- `src/`
  - `pages/`
    - `index.md`: A Markdown file for content that may be converted to HTML.
  - `assets/`
    - `fonts/`: Directory containing custom font files.

- `.dockerignore`: Specifies files to ignore when building Docker images.
- `.gitignore`: Specifies files to ignore in Git version control.
- `package.json`: Configuration file for npm, listing dependencies and scripts.
- `README.md`: Documentation for the project.

## Setup Instructions

1. **Clone the Repository**: 
   Clone this repository to your local machine using:
   ```
   git clone <repository-url>
   ```

2. **Install Dependencies**: 
   Navigate to the project directory and install the necessary dependencies:
   ```
   npm install
   ```

3. **Run the Project**: 
   You can start the project using:
   ```
   npm start
   ```

4. **Deploy to Neocities**: 
   Follow the instructions on Neocities to upload your `public` directory contents to your Neocities site.

## Usage

- Open `public/index.html` in your browser to view the website.
- Modify the HTML, CSS, and JavaScript files to customize the site as needed.
- Use the Markdown file in `src/pages/index.md` to add content that can be rendered on the site.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Your contributions are welcome!

## License

This project is open-source and available under the [MIT License](LICENSE).