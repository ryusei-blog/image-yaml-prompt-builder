# 🖼️ Image YAML Prompt Builder
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/ryusei-blog/image-yaml-prompt-builder.svg)](../../commits/main)
[![Stars](https://img.shields.io/github/stars/ryusei-blog/image-yaml-prompt-builder?style=social)](../../stargazers)

**Visual YAML-prompt composer for AI image generation** — pure PHP & vanilla JS, theme-agnostic for WordPress or standalone use.

---

## ✨ Features
- **YAML-first** prompt export for highly controllable image generation  
- **Dynamic section builder**: add / reorder blocks on the fly  
- **Clean 2-column UI** (controls left, YAML preview right)  
- **Mobile-friendly** layout with sticky heading  
- **Ad slot** ready in bottom-right corner  

---

## 🚀 Quick Start
### WordPress Template
```bash
git clone https://github.com/ryusei-blog/image-yaml-prompt-builder.git
# copy the template file into your active theme folder
cp image-yaml-prompt-builder.php /path/to/wp-content/themes/your-theme/
# visit https://your-site.com/image-yaml-prompt-builder/
```

### Stand-alone PHP
```bash
php -S localhost:8080
# open http://localhost:8080/image-yaml-prompt-builder.php
```

No additional dependencies — works on any server running **PHP 7.4+**.

---

## 📸 Demo
| UI Snapshot | YAML Preview | Mobile View |
|-------------|--------------|-------------|
| ![full-ui](https://ryusei-komada.com/wp-content/uploads/2025/04/4959873bc5667520cb27ac817a33504a.webp) | ![yaml](https://ryusei-komada.com/wp-content/uploads/2025/04/0b8d9f2c0f5369e0ff8a982deec41103.webp) | ![mobile](https://ryusei-komada.com/wp-content/uploads/2025/04/c98615228f9320929b3c62bbd084b909.webp) |

Additional screenshots:
- Dynamic section buttons:  
  ![section-buttons](https://ryusei-komada.com/wp-content/uploads/2025/04/92213c79f33afe093d58edbe2610667a.webp)
- Side-by-side panel layout:  
  ![ui-structure](https://ryusei-komada.com/wp-content/uploads/2025/04/98836661ee3b79a65964aba13c977d93.webp)
- Tutorial overlay:  
  ![tutorial](https://ryusei-komada.com/wp-content/uploads/2025/04/adc9c585b6087881f0ce79af7cd8b4f9.webp)
- Sticky heading on scroll:  
  ![sticky-title](https://ryusei-komada.com/wp-content/uploads/2025/04/120db295a75477a874093ea921208575.webp)

---

## 🤖 Supported Models
- **Primary**: ChatGPT-4o Image Generation  
- **Compatible**: any AI image service that accepts YAML prompts (e.g., SDXL, custom diffusion back-ends)

---

## 🗺️ Roadmap
- [ ] **Live YAML Render** — update preview in real time as you type  
- [ ] Continually expand **Art Styles** / **Compositions**  
- [ ] **Negative Prompt** field  
- [ ] **Logic Flags** (e.g., experimental prompt directives)

Feel free to open Issues or PRs for feature requests!

---

## 🤝 Contributing
1. `git clone` & open in your favourite editor  
2. Run the built-in PHP server for local testing  
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
