# Quiz Master

🚀 **Overview**  
Quiz Master is a dynamic and interactive web-based quiz application designed to provide a seamless and engaging trivia experience. Built with modern web standards, it offers a clean, responsive interface and supports Progressive Web App (PWA) features for offline accessibility.

Challenge your knowledge across various categories and difficulties, track your high scores, and customize the app's appearance with a vibrant theme switcher!

---

✨ **Features**

- **Dynamic Quiz Generation:** Fetches questions from the [Open Trivia Database (OpenTDB)](https://opentdb.com/) API based on user-selected categories, difficulty levels, and number of questions.
- **Interactive UI:**  
  - Clear display of current question, question number (e.g., "Question 3 of 10"), and a countdown timer.  
  - Intuitive answer selection with visual feedback (green for correct, red for incorrect).  
  - Progress bar to visualize quiz completion.
- **Responsive Design:** Optimized for seamless experience across devices (mobile, tablet, desktop).
- **Theme Switcher:** Personalize the app's look with a variety of vibrant gradient themes.
- **High Score Tracking:** Best scores are saved locally using `localStorage`.
- **Progressive Web App (PWA):**  
  - Offline Support: Caches essential resources (HTML, CSS, JS) allowing offline usage.  
  - Installable: Users can install the app on their home screen.  
  - Error Handling: Gracefully handles API fetch errors.

---

🛠️ **Technologies Used**

- HTML5 (Structure & content)
- CSS3 (Styling, gradients, animations, responsive design)
- JavaScript (ES6+) (Core logic, API interaction, DOM manipulation, PWA functionality)
- [Open Trivia Database (OpenTDB)](https://opentdb.com/) API
- Font Awesome (for icons, e.g., `fa-palette`)

---

🚀 **Live Demo**  
[https://quizmasterz.netlify.app/]

---

⚙️ **Installation & Setup**

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/swiftquiz-app.git
   cd swiftquiz-app
---
## Open index.html in your browser

- You can open it directly in most modern browsers.
- For full PWA functionality (offline caching, "Add to Home Screen"), serve files via a local server:

Example using `http-server` (install globally with `npm install -g http-server`):

```bash
http-server .
```

## 🎮 Usage

### Start Screen:
- Select category, difficulty (Any, Easy, Medium, Hard), and number of questions (1–50).
- Click **Start Quiz**.

### Quiz Screen:
- Answer each question before the timer runs out.
- Selected answers highlight green (correct) or red (incorrect).
- The correct answer is shown if your choice was wrong.
- Click **Next** to proceed.

### Results Screen:
- View your score and percentage.
- See if you achieved a new high score!
- Click **Back** to restart.

### Theme Switcher:
- Click the palette icon (🎨) top right to open the theme menu.
- Select a gradient to change the app’s background instantly.

---

## 🌐 PWA Features

- **Offline Access:** Caches core files enabling offline use once loaded.
- **Installability:** Prompts users to add the app to their device home screen for a native-app-like experience.

---

## 🎨 Customization

- **Themes:**  
  Edit the `themes` array in the `<script>` section of `index.html` to add or modify gradient color schemes.

- **Styling:**  
  Modify CSS in the `<style>` block of `index.html` for fonts, spacing, sizes, and colors.

- **Quiz Logic:**  
  Adjust `timeLeft` in the `startTimer` function to change the time limit per question.  
  Modify `amount-input` min/max values in `index.html` to change question count limits.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name ```

3.Make your changes.

4.Commit your changes:
5.Push to the branch:
```bash
git commit -m 'Add new feature X' 
```
6.Open a Pull Request.
## ✉️ Contact

Created with ❤️ by AbdElRahman  
[abdelrahmanz.netlify.app](https://abdelrahmanz.netlify.app)

Feel free to connect or open an issue for questions or feedback.
