# 🐸 Flexbox Froggy Master Demo: The Evolution

An interactive, live-preview tool designed to turn the "dry" theory of CSS Flexbox into a hands-on visual experience. 

## 🚀 Project Origins & Pivot
This project originally began as a collaboration with **DeepSeek AI**. The goal was to build a comprehensive suite of live demos for every major Flexbox property. 

As the project grew in complexity, the original model began to "drift"—missing specific CSS property naming conventions (using JavaScript camelCase instead of CSS kebab-case) and struggling to implement advanced formatting for the live code snippets. To ensure the highest level of technical accuracy and user experience, the project was transitioned to **Gemini AI** to finalize the logic and polish the educational tools.

## 🛠️ The Gemini Corrections & Refinement
During the transition, several key technical and educational fixes were implemented:
* **Syntax Accuracy**: Converted all live code displays from JS property names (e.g., `justifyContent`) to valid CSS syntax (e.g., `justify-content`).
* **Snippet Formatting**: Fixed the live code blocks for `order` and `align-self` to include `display: flex;` and proper multi-line indentation for readability.
* **Logic Fixes**: Adjusted the `align-content: stretch` demo by switching item heights to `auto`, allowing the browser to actually demonstrate the stretching behavior.

## 🎓 Beginner-Focused Features
Flexbox can be difficult to grasp through reading alone. This version went through **multiple iterations** specifically to make it a better teaching tool:
* **The "Default Zero" Concept**: Section 7 was expanded to 5 items, each labeled with `order: 0` to visually prove that items only move when their value differs from the default.
* **Interactive Notifications**: Added styled reminder boxes to properties like `flex-wrap` and `flex-flow` to encourage users to **resize their browser window**, which is the only way to see responsive wrapping in action.
* **Comprehensive Value Sets**: Every property now includes the full range of standard CSS values (e.g., `space-evenly`, `baseline`, `wrap-reverse`) rather than just the basics.

## 💡 How to Use
1.  Clone this repository or download the `.html` file.
2.  Open the file in any modern web browser.
3.  Interact with the dropdowns and sliders to see real-time changes.
4.  **Pro Tip:** Resize your window while viewing sections 4, 5, and 6 to see how Flexbox handles layout overflow!

---
*Created with initial assistance from DeepSeek and perfected with Gemini AI.*
