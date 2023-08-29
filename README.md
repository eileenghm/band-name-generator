# Express Band Name Generator

## Overview

This project is a simple Express.js web application that generates random band names using a combination of adjectives and nouns.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies using the following command:

   ```bash
   npm install
   ```

## Code Explanation
The main server file is index.js, which sets up an Express application. It serves static files from the "public" directory and uses the body-parser middleware to parse incoming form data.

The application has two routes:

1. The root route (/) renders the index.ejs template file, which displays the band name generator form.
2. The /submit route handles the form submission. It generates a random adjective and noun, then renders the index.ejs template with the generated words.

The index.ejs template file includes dynamic rendering of the generated band name and provides a form to trigger the name generation.

