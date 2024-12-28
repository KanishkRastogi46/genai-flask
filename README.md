# Gemini-Powered Web Application

## Project Description

This project is a web application that leverages the Gemini API to enhance user interaction and potentially provide AI-driven features. The application appears to be centered around a bakery theme, as indicated by the presence of image files related to baked goods. It includes a front-end built with HTML, CSS, and JavaScript, and a back-end implemented with Python.

## Project Structure

The project's file structure is organized as follows:

*   **`devserver.sh`**: A shell script likely used to start a local development server.
*   **`main.py`**: The main Python file, probably containing the back-end logic and API interaction code.
*   **`requirements.txt`**: Lists the Python dependencies needed to run the project.
*   **`.idx/dev.nix`**: A Nix configuration file, potentially used for development environment setup.
*   **`.idx/icon.png`**: An icon file, possibly for the development environment or project branding.
*   **`.vscode/settings.json`**: VS Code-specific settings for the project.
*   **`web/`**: A directory containing all front-end web assets:
    *   **`baked_goods_1.jpg`**, **`baked_goods_2.jpg`**, **`baked_goods_3.jpg`**: Images of baked goods.
    *   **`gemini-api.js`**: JavaScript file likely containing code for interacting with the Gemini API.
    *   **`gemini.svg`**: An SVG image, possibly a logo or icon related to Gemini.
    *   **`index.html`**: The main HTML file for the web application.
    *   **`main.js`**: The main JavaScript file for the front-end application logic.
    *   **`style.css`**: The CSS file for styling the web application.

## Setup and Installation

1.  **Clone the Repository:**
```
bash
    git clone <repository_url>
    cd <project_directory>
    
```
2.  **Install Python Dependencies:**
```
bash
    pip install -r requirements.txt
    
```
3.  **Setup development environment (optional):**
    If using nix, you can use the dev.nix file for consistent environment setup

4.  **Navigate to the web folder:**
```
bash
    cd web
    
```
## Running the Project

1.  **Start the Back-End Server:**
```
bash
    python main.py
    
```
*Note:* The specific command to start the server might be different depending on the content of `main.py`. The `devserver.sh` file may include a command to start the dev server as well.

2.  **Start the front end application**
    *   Open the `web/index.html` file in your web browser.

3. **Alternative:**
    *   Run `./devserver.sh` to handle both of the above.

## Key Technologies

*   **Python:** For the back-end and potential Gemini API integration.
*   **HTML, CSS, JavaScript:** For the front-end web application.
*   **Gemini API:** Likely used for AI-powered features within the application.
* **Nix:** used for the development environment setup

## Contributing

Contributions to this project are welcome. Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Commit your changes with clear messages.
4.  Submit a pull request.

## License

[Specify the project license here, e.g., MIT License]