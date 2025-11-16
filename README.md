# WikiPulse
This project is a lightweight, interactive tool that fetches a random fact from Wikipedia and presents it in a clean, modern interface. It’s built to be fast, simple, and slightly addictive for users who enjoy learning something new with one click.
Features
🔍 “I’m Feeling Curious” Button

A single click triggers a call to the Wikipedia API and fetches a random extract from a real article. Perfect for curiosity bursts.

📚 Wikipedia API Integration

Uses the standard MediaWiki query endpoint with proper parameters (including origin=* to avoid CORS issues).
The app retrieves:

Article title

A short extract summary

The article link

⏱ Reading Time Estimate

Each fact includes an estimated reading time, calculated using a simple 200 words-per-minute baseline. Quick, informative, and user-friendly.

📤 Share Options

Users can share what they discover through:

Copy Link: Instantly copies the article URL to the clipboard

Tweet Button: Generates a pre-filled tweet with the article title and link

🎨 Modern UI with Tailwind CSS

Styled with Tailwind CSS for a crisp, modern, responsive layout.
Includes:

Smooth transitions

Clean spacing

A minimalist card layout

A loading spinner while the API fetches data

⚡ Fast & Lightweight

No frameworks required. Just clean JavaScript, an optimized UI, and a tiny footprint.

Tech Stack

HTML5

CSS (Tailwind CSS)

JavaScript (vanilla)

Wikipedia MediaWiki API

How It Works

User clicks I’m Feeling Curious

App fetches a random page extract via Wikipedia API

Loading spinner appears during the fetch

Result displays with:

Title

Summary

Estimated reading time

Buttons to visit the article, copy the link, or share

Installation & Usage
# Clone the repo
git clone https://github.com/YOUR-USERNAME/feeling-curious-app.git

# Open the project folder
cd feeling-curious-app

# Open the index.html file in your browser


Tailwind is included via CDN, so there’s no build process needed.

Future Improvements (Optional)

Add dark mode

Save previously viewed facts

Support more languages

Add animations for transitions
