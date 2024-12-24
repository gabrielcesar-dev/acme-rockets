# Acme Rockets

## Project Overview

Acme Rockets is a simple starter project to get familiar with Tailwind CSS. It showcases a fictional rocket company and includes a responsive design with animations.

## Features

- Responsive design with custom breakpoints for different screens.
- Animated mobile menu toggle.
- Dark mode support.
- Sections for hero, rockets, testimonials, and contact.

## Technologies Used

- HTML
- CSS (Tailwind CSS)
- JavaScript

## Getting Started

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/gabrielcesar-dev/acme-rockets.git
    ```

2. Navigate to the project directory:

    ```sh
    cd acme-rockets
    ```

3. Install the dependencies:

    ```sh
    npm install
    ```

### Running the Project

To start the Tailwind CSS build process and watch for changes, run:

```sh
npm run tailwind
```

### Building for Production

To build the project for production, run:

```sh
npx tailwindcss -i ./src/input.css -o ./build/css/style.css --minify
```

## Project Structure

```
acme-rockets/
├── build/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── index.html
├── src/
│   └── input.css
├── tailwind.config.js
├── package.json
└── README.md
```

## Acknowledgements

This project is based on a course tutorial by [Dave Gray](https://www.youtube.com/@DaveGrayTeachesCode).

## License

This project is licensed under the MIT License.
