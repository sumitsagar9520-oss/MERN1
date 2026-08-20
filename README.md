# 🃏 Interactive Flashcard

A simple and interactive **3D Flashcard** built using **HTML, CSS, and JavaScript**.

The flashcard displays a question/content on the front side and reveals the answer/content when clicked. The card uses a smooth **3D flip animation** created with CSS transforms.

## 🚀 Features

* ✨ Interactive 3D flip animation
* 🖱️ Click the card to flip
* 🎨 Clean and modern UI
* 📱 Responsive viewport setup
* ⚡ Built with pure HTML, CSS, and JavaScript
* 🔄 Front and back card faces

## 🛠️ Technologies Used

* **HTML5** – Structure of the webpage
* **CSS3** – Styling, 3D perspective, and flip animation
* **JavaScript** – Handles the card flip interaction

## 📂 Project Structure

```text
Interactive-Flashcard/
│
├── index.html
└── README.md
```

## 💻 How It Works

The card consists of two faces:

### Front Side

Displays:

> FlashCard
> Visiting Card

### Back Side

Displays:

> Guest
> Invertis University

When the user clicks on the card, JavaScript adds or removes the `flipped` class:

```javascript
function flipCard() {
    const card = document.getElementById('flashcard');
    card.classList.toggle('flipped');
}
```

The CSS then rotates the card by `180deg`:

```css
.flashcard.flipped {
    transform: rotateY(180deg);
}
```

## ▶️ How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/Interactive-Flashcard.git
```

2. Open the project folder.

3. Open `index.html` in any modern web browser.

4. Click the flashcard to see the 3D flip animation.

## 🎯 Learning Objectives

This project demonstrates:

* HTML page structure
* CSS Flexbox
* CSS `perspective`
* CSS `transform-style: preserve-3d`
* CSS `rotateY()`
* CSS `backface-visibility`
* CSS transitions
* JavaScript DOM manipulation
* JavaScript `classList.toggle()`
* Event handling with `onclick`

## 📸 Preview

You can add a screenshot or GIF of your project here:

```markdown
![Interactive Flashcard](screenshot.png)
```

## 🔮 Future Improvements

* Add multiple flashcards
* Add **Next** and **Previous** buttons
* Add random flashcard functionality
* Add question and answer categories
* Add a score system
* Store flashcards using Local Storage
* Make flashcards dynamically using JavaScript

## 👨‍💻 Author

**Sumit Sagar**

Learning and building projects with **HTML, CSS, JavaScript, Java, Python, and Data Science**.

---

⭐ If you found this project useful, consider giving the repository a star!
