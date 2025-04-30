# 🃏 Digimon Digi-Matching Card Game

A browser-based memory matching game themed around nostalgic Digimon characters. Flip two cards at a time, test your memory, and see how quickly you can find all the matching pairs!

🔗 **Live Demo**: [Digimon Card Game](https://digimatches-cvan-creations.netlify.app/)  
📷 **Screenshot**:  
![Gameplay Screenshot](https://github.com/CodingWCal/digimon-digimatch-game/blob/main/digimon-screenshot.png) 

---

## 🛠️ How It's Made:

**Tech used:**  
HTML, CSS, JavaScript (Vanilla), Node.js

This project was built from the ground up using DOM manipulation and simple event-driven logic in JavaScript. Each Digimon card uses a `data-digi` attribute to store its identity, and clicking a card triggers flip animations and matching logic.

- The game board is randomly shuffled on every load using the CSS `order` property.
- It tracks selected cards, locks the board to prevent double-clicking, and resets turns accordingly.
- The reset button reloads the page for a fresh shuffle and replay.

The UI is styled with custom fonts, card back images, and character art to give it that authentic Digi-vibe from the early 2000s.

---

## 🧠 Optimizations (optional):

I used a basic shuffling method with `Math.random()` and ensured the logic avoids bugs like double-clicking the same card. While minimal, the project lays a solid foundation for future improvements like:

- Animating card flips more smoothly
- Adding a score counter or timer
- Enhancing responsiveness for mobile users

---

## 📚 Lessons Learned:

This was my first time combining **custom HTML data attributes** with DOM event logic to create a dynamic game experience. I gained a stronger understanding of:

- How to prevent bugs like flipping the same card twice
- Controlling game state with boolean flags (like `lockBoard`)
- Writing clear, reusable functions for better readability

I also learned how important small UX decisions (like a 1-second delay on mismatched cards) are for making a game feel polished and playable.

---

💬 Whether you're a Digimon fan or just love simple games that test your memory, I hope this gives you a smile—and a challenge!

