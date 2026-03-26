---
layout: home
title: CSC Learning Materials
nav_order: 1
---

# CSC Learning Template
This is the official template for creating clean, branded self-learning course sites. By using this template, you ensure that your training materials match the **CSC** and **LUMI AI Factory** visual identity automatically.

For a quick overview of the Markdown syntax elements refer to [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/).

---

## 📄 Add more pages
1. **Create a New Page:** `index.md` is the 'landing page' of the website, do not rename it. You can easily add more pages by making new `.md` files in the root or in a subfolder. To remove chapter1 page, simply delete `chapter1.md`.
2. **Add Front Matter:** Every page needs these lines at the top:

```yaml
---
layout: default
title: Lesson 1 - Intro
nav_order: 1
---
```

Where: 
- `layout` should be 'home' for `index.md` and 'default' for other pages;
- `title` is the name of the page;
- `nav_order` defines the order in which the extra pages are listed on the left side.

## 🎨 Branded Learning Elements
This site is pre-configured with the LUMI AI Factory palette. You can use special "Callout Boxes" to highlight information for your students as follows:

{: .note }
> **LUMI Purple (Note)**
>
> Use this for additional context or general helpful information.

{: .warning }
> **LUMI Magenta (Warning)**
>
> Use this for critical warnings, security notices, or common errors to avoid.

---

## 💻 Technical Content
* **Inline Commands:** Use backticks to show code like `srun --pty bash`.
* **Code blocks** Use triple backticks to show multiline blocks of code. You must have an empty line before and after the block.
* **Sidebar Links:** Navigation links will turn Purple when you hover over them.

---

## 🧪 Mathematical Formulas
You can write beautiful LaTeX formulas easily using [MarhJax](https://just-the-docs.github.io/just-the-docs-tests/components/math/mathjax/tests/):

- **Inline math:** $$\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t}$$
- **Block math:** 

$$
\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t}
$$

---

## 🛠️ Need Help?
If you have questions or suggestions on how to improve the template or instructions, please reach out to me on RocketChat: Artúr Vojt-Antal
Instructions on how to structure your lessons, add images, and manage navigation can be found in our **[README](https://github.com/Arbruiser/CSC-branded-template/blob/main/README.md)**.