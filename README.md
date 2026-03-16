# 🌐 Personal Website – Raghuwansh Raj

This repository contains the source code for my personal academic website:

👉 **https://rajraghuwansh.github.io**

The site is built using **Hugo** with the **HugoBlox** framework and is automatically deployed using **GitHub Pages**.

---

# 👨‍💻 About Me

I am a **PhD student at the University of Luxembourg** working in the area of:

- Geometric & Topological Deep Learning  
- Graph Neural Networks  
- Mathematical Foundations of Artificial Intelligence  
- Machine Learning for Scientific Systems  

This website serves as my personal academic homepage where I share:

- Blog posts on mathematics and AI  
- Research interests  
- Projects and technical work  
- Professional experience  
- Publications and notes  

---

# 🛠 Technology Stack

The website is built using the following tools:

- **Hugo** – static site generator  
- **HugoBlox** – academic website framework  
- **Markdown** – content writing  
- **GitHub Pages** – website hosting  
- **GitHub Actions** – automatic deployment  

---

# 📂 Repository Structure

```
.
├── content/          # Blog posts, projects, and pages
│   ├── post/
│   ├── project/
│   └── authors/
│
├── assets/           # CSS, JS, and images
├── static/           # Static files (CV, images, PDFs)
├── data/             # Data files used by Hugo
├── layouts/          # Custom layout overrides
├── config/           # Hugo configuration files
│
├── .github/          # GitHub Actions workflow
│   └── workflows/
│
├── hugo.yaml         # Main site configuration
└── README.md
```

---

# 🚀 Running the Website Locally

To run the website locally you need the **extended version of Hugo**.

Install Hugo and run:

```bash
hugo server
```

Then open in your browser:

```
http://localhost:1313
```

---

# ✍️ Creating New Content

Create a new blog post:

```bash
hugo new post/my-post/index.md
```

Create a new project page:

```bash
hugo new project/my-project/index.md
```

After editing content, Hugo will automatically reload the site when using `hugo server`.

---

# 🌍 Deployment

Deployment is handled automatically using **GitHub Actions**.

Whenever changes are pushed to the `main` branch:

1. Hugo builds the static website  
2. The generated site is deployed to **GitHub Pages**  
3. The website is updated automatically  

---


