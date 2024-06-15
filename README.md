
# Claude Book Generator Application

![Book Generator](https://i.imgur.com/6lyacES.png)

This project is a graphical application built with Python's Tkinter library that allows users to generate a book with multiple chapters using the Anthropic Claude API. The generated content is saved as a PDF file.

## Features

- **Generate Book Content:** Automatically generates book chapters based on user input, including book title, author name, and a brief description.
- **Model Selection:** Allows selection of different Claude API models for content generation.
- **Retry Mechanism:** Implements a retry mechanism for handling API rate limits and other errors.
- **Post-Processing:** Replaces incompatible characters and removes large blank spaces in the generated content.
- **Originality Check:** Performs basic checks for originality to avoid repeated phrases, clichés, and common character names or settings.
- **Save as PDF:** Saves the generated book content as a PDF file.

## Requirements

- `Python 3.7+` 
- `Tkinter` 
- `anthropic` library
- `fpdf` library

## Installation

1. **Clone the repository:**
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Install the required Python packages:**
   ```bash
   pip install tkinter anthropic fpdf
   ```

3. **Set the Anthropic API Key:**
   Ensure you have your Anthropic API key set in your environment variables:
   ```bash
   export ANTHROPIC_API_KEY=your_api_key_here
   ```

## Usage

1. **Run the application:**
   ```bash
   python BookWriterClaude3.py
   ```

2. **Fill in the details:**
   - **Book Title:** Enter the title of your book.
   - **Author Name:** Enter the name of the author.
   - **Description:** Provide a brief description of the book's plot or theme.
   - **Number of Chapters:** Select the number of chapters to generate.
   - **Model Version:** Choose the Claude API model for content generation.

3. **Generate the book:**
   Click the "Generate Book" button to start generating the book content. The progress will be displayed in the console.

4. **Save as PDF:**
   Once the book is generated, click the "Save as PDF" button to save the content as a PDF file.

## Contact

Creator: Legend of Ray

Join Ray's Discord: [Link to Discord](https://discord.gg/FPN7vx4eVY)
