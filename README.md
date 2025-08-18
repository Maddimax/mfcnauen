# Nauen Static Jekyll Site

This is a minimal Jekyll website setup.

## Getting Started

### Prerequisites
- Ruby (>= 2.5)
- Bundler (`gem install bundler`)
- Jekyll (`gem install jekyll`)

### Setup
1. Install dependencies:
   ```sh
   bundle install
   ```
2. Serve the site locally:
   ```sh
   bundle exec jekyll serve
   ```
3. Visit `http://localhost:4000` in your browser.

## Structure
- `_config.yml`: Jekyll configuration
- `index.md`: Homepage
- `_posts/`: Blog posts (optional)

---

Replace content as needed for your project.

## Hinweis zur Logo-Einbindung
Das Theme "minima" bindet eigene Includes wie `custom-header.html` nicht automatisch ein. Um das Logo im Header sichtbar zu machen, muss entweder das Theme forkiert und angepasst werden, oder du überschreibst die Datei `_includes/header.html` direkt im Projekt und fügst dort den Logo-Code ein.
