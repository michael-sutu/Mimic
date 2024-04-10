# Mimic

Mimic is a lightweight proxy server designed to simplify and assist in the development and testing of web applications by modifying request URLs on the fly. It intercepts requests and can modify them based on specified rules, making it ideal for testing different environments or configurations without changing the actual codebase.

## Features

- **URL Rewriting:** Dynamically rewrites URLs in HTML, CSS, and JavaScript files.
- **MIME Type Handling:** Automatically adjusts the MIME type for certain file types to ensure proper handling.
- **Live Demo:** A live demo of Mimic can be accessed [here](https://mimic-bfcf.onrender.com/).

## Getting Started

### Prerequisites

Before you begin, ensure you have Node.js installed on your system. You can download and install Node.js from [here](https://nodejs.org/).

### Installation

1. Clone the repository to your local machine:

```sh
git clone https://github.com/michael-sutu/Mimic
cd mimic
```

2. Install the required dependencies:

```sh
npm install
```

### Running the Server

To start the Mimic server, run:

```sh
npm start
```

By default, the server will listen on port 3000, but you can customize this by setting the `PORT` environment variable.

## Usage

To use Mimic, direct your web requests to `http://localhost:3000/?url=<URL_TO_MIMIC>`, replacing `<URL_TO_MIMIC>` with the URL of the web resource you want to mimic.
