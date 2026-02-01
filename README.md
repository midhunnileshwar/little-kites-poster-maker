Little KITES Poster Generator

A client-side web app for generating congratulatory posters for students.

1. Setup Images

You need one image file named template.png inside the main folder.

Requirements for template.png:

Format: PNG (Must support transparency).

Size: Recommended 1080x1350px (Portrait) or 1080x1080px (Square).

The "Hole": The area where the student's photo should appear must be transparent in the PNG.

The Text Area: Leave a blank/solid space at the bottom of the design where the name and school will be written.

2. Adjusting Text Position

Since I don't know the exact size of your poster, the text might appear too high or too low initially.

Open index.html in a text editor (Notepad, VS Code).

Scroll down to the script section (approx line 150).

Look for CONFIG.

Change the y value to move text up or down.

Higher number = Text moves Down.

Lower number = Text moves Up.

const CONFIG = {
    name: {
        y: 920,  // <--- CHANGE THIS NUMBER
        // ...
    },
    school: {
        y: 1000, // <--- AND THIS NUMBER
        // ...
    }
};


3. How to Run

Place index.html and template.png in the same folder.

Open index.html in your browser.

Upload to GitHub Pages for public access.
