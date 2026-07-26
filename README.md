# ⚡ Single-File Holographic App Baseline

This repository serves as the master template for single-file, zero-dependency, mobile-optimized HTML applications.

---

## 🚀 How to Start a Brand-New App (Quick Start Guide)

Follow these steps to instantiate a new project using this template:

1. **Use This Template:**
   * At the top of this repository page, click the green **`Use this template`** button.
   * Select **`Create a new repository`**.
2. **Name Your New Repository:**
   * Give your new app a project name (e.g., `my-new-tool`).
   * Keep it **Public** and click **`Create repository`**.
3. **Enable Live Hosting (GitHub Pages):**
   * In your new repository, click **`Settings`** $\rightarrow$ **`Pages`**.
   * Under **Build and deployment** $\rightarrow$ **Branch**, select **`main`** (or `master`) and click **`Save`**.
   * Your app will be live at `https://<your-username>.github.io/<repository-name>/` in ~60 seconds.
4. **Kick Off Development with Gemini:**
   * Open the `GEMINI_PROMPT.md` file in this repository.
   * Copy the entire prompt text.
   * Paste it into a new chat with Gemini, fill in the `THE NEW APP WILL BE:` section at the bottom, and attach your `index.html` file!

---

## 🏗️ Core Design Criteria & Architecture Rules

* **Single-File Build:** Everything (HTML markup, CSS styling, JavaScript engines) must reside within `index.html`.
* **Zero Dependencies:** No external fonts, icon packs, CSS frameworks (Tailwind/Bootstrap), or JS libraries.
* **Mobile-First Layout:** Designed for 9:16 / 9:20 portrait viewports (optimized for mobile screens).
* **Anti-Clipping UI:** Deep inset container padding with negative margins on all overflow scroll elements to prevent glowing UI effects from clipping.
* **Single Source of Truth:**
  * **Design Criteria:** Stored inside the JS `MODAL_PAGES.design` string.
  * **Audit Log:** Stored inside the JS `AUDIT_LOG_ENTRIES` array.
  * **Editing Instructions:** Referenced at the very top of `index.html`.
