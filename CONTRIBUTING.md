# Chama Aí!

A comercial landing page for an application that seeks freelancers for occasional services to be hired by the population.

## 📁 Project Structure & Conventions

- All HTML files are in the root or organized in folders with `index.html` to allow clean URLs (e.g., `/about/index.html` → `/about/`).
- All JS are inside `/src/js/`.
- The pages stylize may to be Tailwind CSS. Any most complexity, put inside `/src/css/`.

## 📝 File Naming

- Use **kebab-case** for file and folder names:  
  - ✅ `about-us.html`  
  - ✅ `/images/team-photo.jpg`  
  - ❌ `AboutUs.html`, `TeamPhoto.jpg`

- Use **lowercase** for image and asset names.

- JavaScript and CSS files use **kebab-case** too:  
  - ✅ `main.js`  
  - ✅ `site-styles.css`

## 🎨 HTML/CSS Best Practices

- Always set `<meta charset="UTF-8">` and responsive `<meta name="viewport">`.
- Use semantic HTML elements (`<header>`, `<main>`, `<section>`, `<footer>`) when possible.
- Avoid inline styles; keep CSS in Tailwind CSS.

## 📐 JavaScript Best Practices

- Use `const` and `let`, avoid `var`.
- Keep functions short and focused.
- Name functions and variables in **camelCase**.
- Add comments for non-obvious code.

## 🚀 Conventional Commits

This project uses [Conventional Commits](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13) for commit messages.

Basic format:

``` bash
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

### Common commit types:

- `feat`: Commits that add, adjust or remove a new feature to the API or UI
  - ✅ `feat: add contact form to homepage`
- `fix`: Commits that fix an API or UI bug of a preceded feat commit
  - ✅ `fix: correct navbar toggle on mobile`
- `refactor`: Commits that rewrite or restructure code without altering API or UI behavior
- `perf`: Commits are special type of refactor commits that specifically improve performance
- `style`: Commits that address code style (e.g., white-space, formatting, missing semi-colons) and do not affect application behavior
- `test`: Commits that add missing tests or correct existing ones
- `docs`: Commits that exclusively affect documentation
- `build`: Commits that affect build-related components such as build tools, dependencies, project version, CI/CD pipelines, ...
- `ops`: Commits that affect operational components like infrastructure, deployment, backup, recovery procedures, ...
- `chore`: Miscellaneous commits e.g. modifying .gitignore, ...

### Examples:

- ✅ `feat: implement about page layout`
- ✅ `fix(navbar): resolve overlap on small screens`
- ✅ `docs(readme): add section about image naming conventions`

🔗 **Learn more at [Conventional Commits](https://www.conventionalcommits.org/)**

---

## ✅ Additional Notes

- Always test your pages on different screen sizes.
