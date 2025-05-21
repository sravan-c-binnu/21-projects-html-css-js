# 🎨 Color Changer Project

This is a beginner-friendly web project that allows users to change the background color of a webpage by clicking buttons.

## 📚 What I Learned
- How to use HTML to create buttons and structure a page.
- How to use CSS to style buttons and add smooth transitions.
- How to use JavaScript to interact with HTML elements and change styles.

## 💡 Features
- Click the **Red**, **Blue**, or **Green** button to change the background color of the page.
- Smooth transition effect when colors change.

## 🛠️ Tech Stack
- HTML
- CSS
- JavaScript

## 🧠 How It Works
1. Each button is connected to JavaScript using `document.querySelector()`.
2. When you click a button, JavaScript runs a function.
3. That function sets the `document.body.style.backgroundColor` to the selected color.

This single line changes the background color of the entire webpage. Here’s what each part means:
	•	document — Refers to the entire webpage.
	•	.body — Targets the <body> section of the page (where all visible content is).
	•	.style — Allows JavaScript to change the CSS styles of an element.
	•	.backgroundColor — The specific CSS property we’re changing (the background color).
	•	'red' — The new value we’re assigning to the background color.

📌 Result: When this line runs, it tells the browser:

“Change the background color of the webpage to red.”