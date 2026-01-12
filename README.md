# Computational Thinking for Business (BMIS 2402)

This repository contains the source code and course materials for **Computational Thinking for Business**, a course designed to help business students develop systematic problem-solving skills and technical fluency. The course materials are delivered as a modern, searchable documentation site built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

**Live Site:** [https://computethinking.github.io](https://computethinking.github.io)

---

## 👨‍🏫 For Instructors

This project is designed with modularity and reproducibility in mind. If you are an instructor looking to adopt or adapt these materials, you are welcome to do so.

- **Modular Curriculum:** The content is structured around the four pillars of computational thinking: **Decomposition, Abstraction, Algorithmic Thinking, and Pattern Recognition**.
- **Visual Learning:** Uses Python's Turtle Graphics (via `ColabTurtlePlus`) to demystify programming through immediate visual feedback.
- **Generative AI Integration:** Includes a comprehensive module on LLMs, Prompt Engineering, and hands-on usage of Google AI Studio and the Gemini API.
- **Modern Tech Stack:** Built using MkDocs, making it easy to host on GitHub Pages and maintain via Markdown.
- **Reproducible Environments:** Uses `uv` for Python dependency management and includes Jupyter Notebooks for interactive learning.

To adapt this for your own course, simply fork the repository and update the `mkdocs.yml` configuration and the files in `docs/syllabus/`.

## 🎓 For Students

Welcome! This site is your central hub for learning how to approach complex business problems with a "computational" mindset. Computational thinking is about more than just coding—it's about learning how to decompose complex problems so they can be solved systematically.

### What you will learn:
- **The Pillars of Logic:** Master decomposition, abstraction, algorithmic thinking, and pattern recognition.
- **Visual Programming:** Use Python Turtles to build complex shapes and understand the logic of loops and functions.
- **Generative AI & LLMs:** Move beyond simple chatting. Learn the "Anatomy of a Prompt" and how to use the Gemini API programmatically.
- **Data Proficiency:** Gain proficiency in Python and R, the foundational languages of modern business analytics.

Explore the [Syllabus](https://computethinking.github.io/syllabus/) to see the full schedule and required materials.

---

## 🛠 Development & Setup

If you wish to run this documentation site locally or contribute to it, we use `uv` for Python package management.

1. **Install uv:**
   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```

2. **Clone the repository:**
   ```bash
   git clone https://github.com/computethinking/computethinking.github.io.git
   cd computethinking.github.io
   ```

3. **Run the development server:**
   ```bash
   uv run mkdocs serve
   ```
   The site will be available at `http://127.0.0.1:8000`.

---

**Instructor:** [Midhubalan Balasubramanian](https://linkedin.com/in/midhubalan)  
**Copyright:** © 2025 Midhubalan Balasubramanian.