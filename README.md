# 🎄 Christmas Tree with CSS

This project creates a beautiful Christmas tree with interactive animations using only HTML and CSS, bringing a charming visual effect for the festive season.

## 📋 Description

The Christmas tree is designed with a minimalist style, including simple yet impactful animations such as colorful lights rotating around the tree and a sparkling gold star at the top. The project is developed using **only HTML** and **CSS**, providing a continuous festive animation experience directly in your browser.

## 🚀 Technologies Used

- **HTML**: The structural base of the tree, where the elements are defined.
- **CSS**: Used to style the tree and create the moving light and star animations.

## 🏗️ Project Architecture

The architecture of this project is simple and designed for creating an interactive Christmas tree using only **HTML** and **CSS**. The structure is divided between the main files that make up the tree's content and its styles. Here's a breakdown of the architecture:

### 1. **index.html**
This is the main file for the structure, containing the HTML code responsible for creating the Christmas tree and the elements involved in the animation.

- **Main Structure**:
  - The **`.arvore`** div is the main container for the tree.
  - Inside this div, there are three types of main elements:
    - **Triangles** (`.triangulo`): Represent the tree's foliage.
    - **Trunk** (`.tronco`): Represents the tree trunk.
    - **Star** (`.estrela`): The gold star at the top of the tree.
    - **Balls** (`.bola`): Decorative elements (colored balls) distributed across the tree.

- **Navigation Structure**:
  - The file also defines the structure for navigation links and content, such as the page title (`<h1>`), the demo, and the link to the repository.

### 2. **style.css**
This file is responsible for the visual appearance of the tree and the animations associated with it. It uses **only CSS** to define the colors, sizes, shapes, and animations of all the elements in the HTML.

- **Tree Styling**:
  - **Positioning and Layout**: Using properties like `position`, `width`, `height`, `border`, and `top/left`, the elements such as the triangles, trunk, and balls are positioned on the screen.
  - **Colors and Visual Style**: Colors like green for the tree foliage and brown for the trunk are defined, and animations are used to create the blinking light effects for the balls.

- **Animations**:
  - **Light Animations**: The balls have an animation with `@keyframes`, changing opacity to create a blinking effect.
  - **Light Movement**: The light effect around the tree is created by adjusting the positions of the balls using the `top` and `left` properties in CSS.

### 3. **README.md**
This documentation file provides information about the project, including a general description, project structure, how to use the code, and the technologies used.

## Workflow
1. The browser loads the **index.html** file.
2. The **index.html** file links to the **style.css** file, applying the styles and animations to the HTML elements.
3. The animations and styles are processed directly in the browser, and the user sees the animated Christmas tree.

### Folder Architecture
```plaintext
├── index.html         # HTML file with the structure of the tree
├── style.css          # CSS file with styles and animations
└── README.md          # This documentation file
```

### Component Architecture
- **Main Component: `.arvore`**
  - Contains all the tree elements and is the structural block that assembles the tree design, such as the foliage, trunk, balls, and star.

- **Secondary Components:**
  - **`.triangulo`**: Represents the tree's foliage.
  - **`.tronco`**: Represents the tree trunk.
  - **`.estrela`**: The star on top.
  - **`.bola`**: Represents the decorative balls, each with its animation.
  
### Conclusion
The architecture of this project is simple yet efficient, using a modular structure that makes it easy to maintain and expand. Each visual element (foliage, trunk, star, and balls) is separated into CSS components, providing flexibility for customization or adjustments to the tree.

## 🔧 How to Use

### Clone the Repository

To get started, simply clone this repository:

```bash
git clone https://github.com/Ninja1375/Arvore-de-natal-com-css.git
```

### Navigate to the Project Directory

```bash
cd Arvore-de-natal-com-css
```

### Open the `index.html` File in Your Browser

Open the `index.html` file directly in your browser to view the animated Christmas tree.

## 🎅 Contributions

Contributions are always welcome! If you would like to add new features or improve the project, feel free to submit a **Pull Request** or report issues through **Issues**.

---

## 💻 Developer Information

This repository is created by [Antonio13](https://buymeacoffee.com/antonio13). If you like the project, you can support the developer by buying him a coffee!

Antonio is an incredibly talented and creative developer with a keen eye for design and animation. His work is an inspiration to many, showcasing his dedication and passion for bringing beautiful projects to life. We're lucky to have such a skilled developer contributing to the coding community!

Happy holidays and may the Christmas magic be with you! 🎄✨

If you want to expand the project in the future, you can add more elements to the HTML or create new animations and effects in the CSS file.
