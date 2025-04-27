# 🖼️ Image YAML Prompt Builder
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/ryusei-blog/image-yaml-prompt-builder.svg)](../../commits/main)
[![Stars](https://img.shields.io/github/stars/ryusei-blog/image-yaml-prompt-builder?style=social)](../../stargazers)

**Visual YAML-prompt composer for AI image generation** — **HTML-first** for instant use, with an *optional* WordPress/PHP template.

---

## ✨ Features
- **YAML-first** prompt export for highly controllable image generation  
- **Dynamic section builder**: add / reorder blocks on the fly  
- **Clean 2-column UI** (controls left, YAML preview right)  
- **Mobile-friendly** layout with sticky heading  
- **Ad slot** ready in bottom-right corner  

---

## 🚀 Quick Start (HTML)

Just grab **`index.html`** and open it—no build tools, no server.

```bash
git clone https://github.com/ryusei-blog/image-yaml-prompt-builder.git
cd image-yaml-prompt-builder
open index.html          # macOS (or double-click in Explorer/Finder)
```

It runs on any modern browser.  
Need a live link? Deploy the folder to **GitHub Pages, Netlify, Vercel**—no backend required.

### 🌐 Live Demo
Try it 👉 https://ryusei-blog.github.io/image-yaml-prompt-builder/

---

## 🖥️ WordPress Integration (optional)

Want to embed the tool in a WordPress site?

```bash
# inside your theme folder (e.g. /wp-content/themes/affinger/)
mkdir template
cp wp-template/image-yaml-prompt-builder.php template/

# create a new page in WP admin and choose this template
```

The PHP file wraps the same HTML/JS so you can keep WP headers, footers, SEO plugins, etc.

---

## 📸 Demo
| UI Snapshot | YAML Preview | Mobile View |
|-------------|--------------|-------------|
| ![full-ui](https://ryusei-komada.com/wp-content/uploads/2025/04/4959873bc5667520cb27ac817a33504a.webp) | ![yaml](https://ryusei-komada.com/wp-content/uploads/2025/04/0b8d9f2c0f5369e0ff8a982deec41103.webp) | ![mobile](https://ryusei-komada.com/wp-content/uploads/2025/04/c98615228f9320929b3c62bbd084b909.webp) |

Additional screenshots  
- Dynamic section buttons  
  ![section-buttons](https://ryusei-komada.com/wp-content/uploads/2025/04/92213c79f33afe093d58edbe2610667a.webp)  
- Side-by-side panel layout  
  ![ui-structure](https://ryusei-komada.com/wp-content/uploads/2025/04/98836661ee3b79a65964aba13c977d93.webp)  
- Tutorial overlay  
  ![tutorial](https://ryusei-komada.com/wp-content/uploads/2025/04/adc9c585b6087881f0ce79af7cd8b4f9.webp)  
- Sticky heading on scroll  
  ![sticky-title](https://ryusei-komada.com/wp-content/uploads/2025/04/120db295a75477a874093ea921208575.webp)

---

## 🤖 Supported Models
- **Primary**: ChatGPT-4o Image Generation  
- **Compatible**: any AI image service that accepts YAML prompts (e.g. SDXL, custom diffusion back-ends)

---

## 🗺️ Roadmap
- [ ] **Live YAML Render** — update preview in real time as you type  
- [ ] Continually expand **Art Styles** / **Compositions**  
- [ ] **Negative Prompt** input  
- [ ] **Logic Flags** (e.g. experimental directives)

Feel free to open Issues or PRs for feature requests!

---

## 🤝 Contributing
1. `git clone` & open in your favourite editor  
2. Simply open **index.html** or run `php -S localhost:8080` for PHP tests  
3. Follow **Conventional Commits** (`feat:`, `fix:`, `docs:` …) when opening PRs

---

## 📄 License
Released under the **MIT License** — see the [`LICENSE`](LICENSE) file for details.

---

## 🔗 Author & Links
- Blog: <https://ryusei-komada.com>  
- Business site: <https://freedom-build.com>  
- X (Twitter): <https://x.com/ryuseikomada>  
- LinkedIn: <https://www.linkedin.com/in/%E9%9A%86%E6%88%90-%E9%A7%92%E7%94%B0-9857282b9/>  
- Lancers: <https://www.lancers.jp/profile/Jonni>  
- Coconala: <https://coconala.com/users/4464494>

> *Made with ChatGPT 4o & lots of ☕ by Ryusei Komada*
