# PyPrompter - AI Prompt Generator

A simple Python script to generate structured prompts for AI assistants.

## Features

- 🎨 Beautiful ASCII art interface
- 📝 Interactive questionnaire to build prompts
- 📋 Copy to clipboard functionality
- 💾 Multiple export formats:
  - XML format with structured data
  - Plain text (.txt)
  - Markdown (.md)
- 🌍 Cross-platform compatibility

## Installation

1. Make sure you have Python 3 installed
2. The script will automatically install required dependencies (`pyperclip`)

## Usage

Run the script with:

```bash
python pyprompter.py
```

Or if you made it executable:

```bash
./pyprompter.py
```

## How it works

1. The script will display an ASCII art banner
2. You'll be asked a series of questions:
   - **Role**: What is the AI's role?
   - **Context**: What is the context?
   - **Objectives**: What are the objectives?
   - **Methodology**: What methodology should be followed?
   - **Avoid**: What should be avoided?
   - **Output Format**: What output format is expected?
   - **Constraints**: Are there any specific constraints?
   - **Examples**: Do you have any examples to provide?

3. Press Enter to skip any question
4. The script will generate a structured prompt based on your answers
5. Choose how to export your prompt:
   - Copy to clipboard
   - Save as XML
   - Save as text file
   - Save as Markdown
   - Do all of the above

## Example Output

```
You are a Python expert developer.

Context: Working on a web scraping project

Objectives:
Create a robust web scraper that can handle dynamic content

Methodology to follow:
Use best practices and error handling

Things to avoid:
Don't violate robots.txt or terms of service

Expected output format:
Clean, well-documented Python code
```

## Requirements

- Python 3.6+
- pyperclip (automatically installed)

## License

Free to use and modify! 
