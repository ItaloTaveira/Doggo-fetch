# Doggo Fetch

Doggo Fetch is a simple web-based quiz game where users guess the breed of a dog based on a randomly fetched image. The project uses the [Dog CEO API](https://dog.ceo/dog-api/) to fetch random dog images and provides multiple-choice options for the user to select the correct breed.

## Project Structure

    Doggo/

├── assets/
│ ├── css/
│ │ └── style.css # Arquivo de estilos
│ ├── js/
│ │ └── main.js # Arquivo JavaScript principal
│ └── images/ # Diretório para imagens estáticas (se necessário)
├── index.html # Arquivo HTML principal renomeado para "index.html"
├── README.md # Documentação do projeto
└── LICENSE # Licença do projeto (opcional)

### Files

- **Doggo.html**  
  The main HTML file that structures the webpage. It includes the header, main content area, and links to the CSS and JavaScript files.

- **style.css**  
  Contains the styles for the webpage, including layout, button designs, and responsiveness.

- **main.js**  
  The JavaScript file that powers the functionality of the quiz. It fetches random dog images, generates multiple-choice options, and handles user interactions.

## Features

- Fetches random dog images from the Dog CEO API.
- Extracts the breed name from the image URL.
- Generates multiple-choice options, including the correct breed and random incorrect options.
- Highlights correct and incorrect answers when a user makes a selection.

## How to Run

1. Clone or download this repository.
2. Open `Doggo.html` in any modern web browser.
3. The game will automatically fetch a random dog image and display multiple-choice options for the user to guess the breed.

## Technologies Used

- **HTML5** for structuring the webpage.
- **CSS3** for styling and layout.
- **JavaScript (ES6)** for functionality and interactivity.
- **Dog CEO API** for fetching random dog images.

## Future Improvements

- Add a scoring system to track user performance.
- Include a timer for each question to make the game more challenging.
- Enhance the UI/UX with animations and transitions.
- Add support for more languages.

## License

This project is open-source and available under the [MIT License](LICENSE).
