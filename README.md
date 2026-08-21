
# Trafalgar Healthcare Landing Page

A clean, modern, and fully responsive landing page built with HTML5 and Tailwind CSS based on the Trafalgar Figma design.

![Live Demo Preview](https://trafalgar-landing-page-five.vercel.app)

---

## 🚀 Live Demo

- **Live URL:** [https://trafalgar-landing-page-five.vercel.app](https://trafalgar-landing-page-five.vercel.app)
- **Repository:** [https://github.com/yasin-coded/ostad_m14_assignment](https://github.com/yasin-coded/ostad_m14_assignment)

---

## ✨ Features

- **Responsive Layout:** Optimized for mobile, tablet, and desktop viewports using Tailwind CSS breakpoints (`sm:`, `lg:`).
- **Pixel-Consistent Typography:** Carefully styled heading hierarchies and text structures matching the original design spec.
- **Clean UI Elements:** Feature cards, service sections, testimonial slider layout, and footer navigation.
- **Mobile-Optimized:** Hidden decorative visual elements on small screens to prevent horizontal scroll and layout overflow.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic page structure.
- **Tailwind CSS:** Utility-first CSS framework for styling and layout responsiveness.
- **Vercel:** Fast static site deployment and continuous hosting.
- **Git & GitHub:** Version control.

---

## 📁 Project Structure

```text
ostad_m14_assignment/
├── assets/          # Images, logos, icons, and visual graphics
├── src/
│   ├── input.css    # Tailwind CSS input directives
│   └── output.css   # Compiled output CSS
├── index.html       # Primary HTML file
├── package.json     # Node scripts and dependencies
├── .gitignore       # Untracked Git files
└── README.md        # Project documentation
⚙️ Local Development Setup
To run this project locally on your machine:

Clone the repository:

Bash
git clone [https://github.com/yasin-coded/ostad_m14_assignment.git](https://github.com/yasin-coded/ostad_m14_assignment.git)
cd ostad_m14_assignment
Install dependencies:

Bash
npm install
Compile Tailwind CSS:

Bash
npm run build
(Or run the watcher mode during development)

Bash
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
Launch the site:
Open index.html directly in your browser or use VS Code's Live Server extension.