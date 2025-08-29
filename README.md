# Google Gemini Citation Remover

🧹 **Clean up your Google Gemini responses instantly!**

A simple web tool that removes citation markers from Google Gemini 2.5 Pro and Flash responses, fixing formatting issues when you copy and paste AI-generated text.

## 🌟 Live Demo

**[Try it now →](https://yourusername.github.io/gemini-citation-remover)**

*(Replace `yourusername` with your actual GitHub username after deployment)*

## 🔧 What It Does

When you click "Copy response" in Google Gemini 2.5 Pro or Gemini Flash, the text includes citation markers that break formatting:

- `[cite_start]` at the beginning of sentences
- `[cite: 1, 8, 15]` number references 
- `[cite_end]` markers
- Markdown formatting conflicts with bullet points and bold text

This tool **removes all citation markers** while:
✅ Preserving document structure and line breaks  
✅ Fixing markdown formatting conflicts  
✅ Producing clean, properly formatted text  
✅ Ready to paste anywhere without formatting issues  

## 🚀 Deploy to GitHub Pages

### Option 1: Use This Repository as Template

1. **Fork this repository** or click "Use this template"
2. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Set Source to "Deploy from a branch"
   - Select `main` branch and `/ (root)` folder
   - Click Save
3. **Access your site**: `https://yourusername.github.io/gemini-citation-remover`

### Option 2: Create New Repository

1. **Create a new GitHub repository** (public)
2. **Clone the repository** to your computer:
   ```bash
   git clone https://github.com/yourusername/gemini-citation-remover.git
   cd gemini-citation-remover
   ```
3. **Add the files**:
   - Save the HTML code as `index.html`
   - Add this README as `README.md`
   - Optionally add `_config.yml` (see below)
4. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial commit: Gemini citation remover tool"
   git push origin main
   ```
5. **Enable GitHub Pages** (same as Option 1, steps 2-3)

## 📁 Repository Structure

```
gemini-citation-remover/
├── index.html          # Main application file
├── README.md          # This file
└── _config.yml        # Optional Jekyll config
```

## ⚙️ Optional Jekyll Configuration

Create `_config.yml` for better SEO and metadata:

```yaml
title: "Google Gemini Citation Remover"
description: "Remove citation markers from Google Gemini AI responses. Fix formatting issues when copying from Gemini 2.5 Pro and Flash."
url: "https://yourusername.github.io"
baseurl: "/gemini-citation-remover"

# SEO settings
lang: en
author: "Your Name"

# GitHub Pages settings
plugins:
  - jekyll-sitemap
  - jekyll-seo-tag
```

## 🎯 SEO & Discoverability

This tool is optimized for search terms like:
- "Remove Gemini citations"
- "Fix Gemini copy response"
- "Clean Gemini text formatting" 
- "Gemini cite_start remover"
- "Google AI citation cleanup"

## 🔒 Privacy & Security

- **100% client-side**: No data sent to servers
- **No tracking**: No analytics or cookies
- **Open source**: All code visible and auditable
- **No dependencies**: Pure HTML/CSS/JavaScript

## 🛠️ Technical Features

- Removes all Gemini citation patterns: `[cite_start]`, `[cite: numbers]`, `[cite_end]`
- Fixes markdown formatting conflicts (bullet points + bold text)
- Preserves document structure and line breaks
- Real-time statistics and feedback
- One-click copy functionality
- Responsive design for mobile and desktop

## 📞 Support & Issues

- **Found a bug?** [Open an issue](https://github.com/yourusername/gemini-citation-remover/issues)
- **Want a feature?** [Request it here](https://github.com/yourusername/gemini-citation-remover/issues)
- **Need help?** Check the [Discussions](https://github.com/yourusername/gemini-citation-remover/discussions)

## 📝 License

MIT License - feel free to use, modify, and distribute!

## 🌟 Star This Repo

If this tool helped you, consider starring the repository to help others discover it!

---

**Made for the Google Gemini AI community** 🤖✨