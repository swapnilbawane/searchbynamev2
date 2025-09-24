# 🔍 Search Query Generator

A powerful web tool that generates dynamic Google Search links to find people across educational institutions. Built to solve the problem of broken LinkedIn profile URLs and provide reliable, always-updated search results.

## 🚀 Live Demo

**[Try it now →](https://yourusername.github.io/search-query-generator)**

## 🎯 Problem Solved

Traditional alumni lookup tools rely on direct LinkedIn URLs that frequently break due to:
- Profile URL changes
- Privacy settings
- LinkedIn's anti-scraping measures
- Outdated or moved profiles

## ✨ Solution

This tool generates **Google Search links** instead of direct URLs, ensuring:
- ✅ Results stay current and relevant
- ✅ Works even when profiles change
- ✅ No broken links
- ✅ Multiple search strategies for better discovery

## 🛠️ Features

### Core Functionality
- **Multi-Institution Search**: Target specific colleges or search across multiple institutions
- **Flexible Name Matching**: Handles name variations and different profile formats
- **Search Strategy Options**: LinkedIn-focused, comprehensive, or broad web searches
- **Custom Keywords**: Add graduation year, department, location for refined results

### Supported Institutions
- Sardar Patel Institute of Technology (SPIT)
- Sardar Patel College of Engineering (SPCE)
- University of Mumbai
- Easily extensible for other institutions

### Search Types Generated
1. **LinkedIn Institution-Specific**: `site:linkedin.com/in "John Doe" "Institution Name"`
2. **Multi-Institution OR Logic**: `"John Doe" ("SPIT" OR "SPCE" OR "University of Mumbai")`
3. **Broad Institutional**: `"John Doe" "Sardar Patel"`
4. **Custom Keywords**: `"John Doe" "Additional Keywords"`

## 🖥️ Tech Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with responsive design
- **Deployment**: GitHub Pages ready
- **Dependencies**: None (vanilla JavaScript)

## 📱 Responsive Design

- ✅ Desktop optimized
- ✅ Mobile friendly
- ✅ Tablet compatible
- ✅ Cross-browser support

## 🚀 Quick Start

### Option 1: Use GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings > Pages
3. Select "Deploy from branch" > "main"
4. Your tool will be live at `https://yourusername.github.io/search-query-generator`

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/search-query-generator.git

# Navigate to directory
cd search-query-generator

# Open in browser
open index.html
# or
python -m http.server 8000  # Then visit localhost:8000
```

## 📖 Usage Guide

1. **Enter Name**: Type the person's name you want to search for
2. **Select Institutions**: Choose which colleges/universities to include
3. **Add Keywords** (optional): Include graduation year, department, etc.
4. **Generate Links**: Click to create multiple search variations
5. **Search**: Click any generated link to search Google with that query

### Pro Tips
- Try name variations: "John Smith" vs "J Smith" vs "John S"
- Start with Multi-Institution search for broader coverage
- Use additional keywords for more targeted results
- Try multiple generated links - people list different affiliations

## 🔧 Customization

### Adding New Institutions
Edit the `institutionNames` object in the JavaScript:

```javascript
const institutionNames = {
    spit: 'Sardar Patel Institute of Technology',
    spce: 'Sardar Patel College of Engineering',
    mumbai: 'University of Mumbai',
    // Add your institution here
    newcollege: 'Your College Name'
};
```

Then add corresponding HTML checkboxes in the institution grid.

### Modifying Search Strategies
Update the `generateLinks()` function to customize:
- Search query formats
- URL structures  
- Additional search platforms
- Logic operators (AND/OR)

## 🤝 Contributing

Contributions are welcome! Here are ways you can help:

- 🐛 **Report bugs** via GitHub Issues
- 💡 **Suggest features** or improvements
- 🏫 **Add new institutions** to the search database
- 🎨 **Improve UI/UX** design
- 📝 **Enhance documentation**

### Development Workflow
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes
4. Test thoroughly
5. Commit: `git commit -m 'Add amazing feature'`
6. Push: `git push origin feature/amazing-feature`
7. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Swapnil Bawane**
- LinkedIn: [@swapnilbawane](https://www.linkedin.com/in/swapnilbawane/)
- GitHub: [@swapnilbawane](https://github.com/swapnilbawane)

## 🙏 Acknowledgments

- Inspired by the need for reliable alumni discovery tools
- Built for the Mumbai engineering college community
- Thanks to all contributors and users providing feedback

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/swapnilbawane/search-query-generator?style=social)
![GitHub forks](https://img.shields.io/github/forks/swapnilbawane/search-query-generator?style=social)
![GitHub issues](https://img.shields.io/github/issues/swapnilbawane/search-query-generator)
![GitHub license](https://img.shields.io/github/license/swapnilbawane/search-query-generator)

---

⭐ **Star this repo** if it helped you find the people you were looking for!

**[🔍 Try the Search Query Generator →](https://yourusername.github.io/search-query-generator)**
