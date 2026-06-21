# Pokédex Explorer

## Description

**Objective:** Provide a fast and responsive way to browse the Pokémon universe through a clean UI.

**Problem Solved:** Consuming and displaying data from large-scale public APIs requires efficient data handling. This project resolves that by delivering a seamless, real-time search and filter experience without overloading the client.

**Project Context:** Front-end project built to explore asynchronous JavaScript and advanced array manipulation (`map`, `filter`, `reduce`, `find`) while consuming real-time data from the PokéAPI.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

## Preview

<img width="800" height="450" alt="gravacao-pokedex-ezgif com-optimize" src="https://github.com/user-attachments/assets/d6dcc045-8895-4388-8c55-2ea5645e0072" />

---

## About the Project

The Pokédex Explorer is a responsive, mobile-first web application designed to interface with the external PokéAPI. It features a smart, text-based search engine with category separation and real-time filtering, allowing users to quickly find specific Pokémon and their statistics.

The project relies purely on vanilla web technologies (HTML, CSS, and JavaScript), utilizing CSS Grid and custom variables for the layout. The core logic is split into dedicated files for API communication and DOM manipulation, ensuring a clean architecture and robust error handling through `try/catch` blocks for failed API requests.

---

## Features

- Real-time data fetching from the PokéAPI using `fetch` and `async/await`
- Advanced data manipulation to process and display Pokémon statistics
- Smart search system with category separation and real-time filtering
- Responsive mobile-first grid layout
- Robust error handling to manage API request failures gracefully

---

## Deploy

The project is hosted and running through GitHub Pages.

**Access the application:** [Deploy on GitHub Pages](https://v-charles.github.io/pokedex-explorer/)

---

## How to Run

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- A local server environment (like VS Code's "Live Server" extension) is recommended.

---

### Clone the Repository

```bash
git clone git@github.com:V-Charles/pokedex-explorer.git
cd pokedex-explorer

```

---

### Installation

```bash
# This is a Vanilla JS project, so no dependency installation (like npm) is required.

```

---

### Configuration and Execution

1. Open the project folder in your preferred code editor.
2. Start your local server environment. If using VS Code, right-click the `index.html` file and select **"Open with Live Server"**.
3. Alternatively, you can simply double-click the `index.html` file to open it directly in your browser.

The system will be available at your local server port, typically:

```bash
http://127.0.0.1:5500/index.html

```

---

## Environment Variables

This project consumes a public API (PokéAPI) and does not require authentication keys or environment variables to run locally.

---

## API Endpoints

Instead of a custom back-end, this project consumes the public [PokéAPI](https://pokeapi.co/). Communication is handled via `fetch` requests in the `api.js` file.

| HTTP Method | External API Route | Description |
| --- | --- | --- |
| GET | `https://pokeapi.co/api/v2/pokemon` | Fetches the main list of Pokémon |
| GET | `https://pokeapi.co/api/v2/pokemon/{id_or_name}` | Fetches specific details for a single Pokémon |

---

## Author

Developed by [Vinicius Charles Macedo Dias](https://www.linkedin.com/in/vinicius-charles/)
