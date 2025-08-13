# One Typed Page Mobile Viewer

A mobile-optimized web application for viewing and interacting with [One Typed Page](https://onetypedpage.com/) - Daniel Marleau's daily typewriting project.

## 📖 About One Typed Page

One Typed Page is a commitment by Daniel Marleau to type one page every day on a manual typewriter. Each page is typed once, with no corrections, no edits, no spell-check. What you see is what came out of the typewriter, mistakes and all. It's about embracing imperfection and finding beauty in the process.

## ✨ Features

### 🎯 Core Functionality
- **Real-time RSS Integration** - Automatically fetches the latest posts from onetypedpage.com
- **Multi-day Navigation** - Browse through up to 10 recent posts with smart date labels (Today, Yesterday, X Days Ago)
- **Dual Navigation Modes** - Switch between page navigation (within a post) and day navigation (between posts)
- **Mobile-First Design** - Optimized specifically for mobile viewing with touch-friendly interfaces

### 📱 Mobile Experience
- **Native Pinch-to-Zoom** - Full support for mobile image zooming and panning
- **Tap-to-Hide UI** - Tap any image to hide all interface elements for unobstructed viewing
- **Auto-Hide Interface** - UI automatically hides after 4 seconds of inactivity on mobile
- **Touch-Optimized Controls** - All buttons and navigation designed for finger-friendly interaction

### 🔍 OCR Text Extraction
- **Four Different OCR Engines**:
  - **Legacy Engine** - Traditional character recognition with artifact prevention
  - **Neural LSTM** - Modern AI-based recognition with strict character validation
  - **Enhanced Image** - Pre-processed image analysis or enhanced Tesseract settings
  - **Character-Limited** - Restrictive approach with dictionary validation
- **Editable Results** - All extracted text can be manually edited and corrected
- **Smart Character Filtering** - Prevents common OCR artifacts like spurious "I" and "l" characters
- **Export Options** - Copy text to clipboard or download as .txt files

### 🌐 Cloud OCR Integration
- **Professional Service Recommendations** - Links to high-accuracy cloud OCR services
- **Mobile App Suggestions** - Recommendations for Adobe Scan, Microsoft Office Lens, Google Keep
- **Easy Image Download** - One-click download of images for use with external OCR services

### 💾 Export & Download
- **Image Downloads** - Proper blob-based downloads that work on both mobile and desktop
- **Smart Filenames** - Automatically generated names like "one-typed-page-today-1.jpg"
- **Markdown Export** - Generate comprehensive markdown documents of your viewed pages
- **Copy/Download Markdown** - Export markdown to clipboard or download as .md files

### 🎨 Interface Features
- **Streamlined Navigation** - Single combined navigation bar saves screen space
- **Mode Switching** - Toggle between Pages and Days navigation with visual indicators
- **View Toggle** - Switch between image and text views
- **Responsive Design** - Works perfectly on phones, tablets, and desktop browsers

### 🔧 Technical Robustness
- **CORS Proxy Handling** - Multiple fallback proxies ensure reliable RSS feed access
- **Manual RSS Input** - Fallback option if all automated methods fail
- **Image Deduplication** - Automatically removes duplicate image sizes from WordPress
- **Error Handling** - Graceful handling of network issues and missing images
- **Keyboard Shortcuts** - Full keyboard navigation support for desktop users

## 🚀 Usage

### Getting Started
1. Simply open the HTML file in any modern web browser
2. The app will automatically load the latest posts from One Typed Page
3. Use the navigation controls to browse between days and pages

### Navigation
- **Pages Mode**: Navigate between pages within the current day's post
- **Days Mode**: Navigate between different days (Today → Yesterday → etc.)
- **Toggle**: Click the mode button in the navigation bar to switch between modes
- **Hide UI**: Tap any image to hide/show the interface

### OCR Text Extraction
1. Switch to "Text" view
2. Click "Extract Text" 
3. Choose from four different OCR methods
4. Edit the extracted text as needed
5. Copy to clipboard or download as .txt file

### Exporting
- **Images**: Use the "Save" button to download images to your device
- **Markdown**: Use the "MD" button to export a markdown document of all viewed pages

## 🔧 Technical Details

### Built With
- **Vanilla JavaScript** - No frameworks, maximum compatibility
- **Tesseract.js** - Client-side OCR processing
- **CSS Grid/Flexbox** - Modern responsive layout
- **Web APIs** - Canvas, Blob, Clipboard for advanced functionality

### Browser Compatibility
- **Mobile**: iOS Safari, Chrome, Firefox, Samsung Internet
- **Desktop**: Chrome, Firefox, Safari, Edge
- **Minimum**: ES6 support required

### CORS Proxy Services
The app uses multiple CORS proxy services to access the RSS feed:
- corsproxy.io
- allorigins.win
- corsproxy.org
- cors.bridged.cc
- And several fallbacks

## 🎯 Key Features Summary

| Feature | Description |
|---------|-------------|
| **Mobile-First** | Designed specifically for mobile viewing |
| **Native Zoom** | Full pinch-to-zoom support without conflicts |
| **Smart Navigation** | Dual-mode navigation (Pages/Days) |
| **Advanced OCR** | Four different engines with artifact prevention |
| **Proper Downloads** | Blob-based downloads that actually save files |
| **Markdown Export** | Complete export functionality with copy/download |
| **UI Flexibility** | Tap-to-hide and auto-hide interface |
| **Attribution** | Proper credit to Daniel Marleau and One Typed Page |

## 📱 Installation

No installation required! This is a single HTML file that runs in any web browser.

1. Download the HTML file
2. Open in your web browser
3. Bookmark for easy access on mobile devices

For the best mobile experience, consider adding it to your home screen:
- **iOS**: Safari → Share → Add to Home Screen
- **Android**: Chrome → Menu → Add to Home Screen

## 🤝 Contributing

This is an independent project created to enhance the One Typed Page viewing experience. 

### Ideas for Contribution
- Additional OCR engine integrations
- Enhanced image preprocessing algorithms
- Better mobile gesture handling
- Accessibility improvements
- Additional export formats

## 📜 Attribution

This mobile viewer is built for **One Typed Page**, a daily project by **Daniel Marleau**.

- **Original Project**: [onetypedpage.com](https://onetypedpage.com/)
- **About the Project**: [onetypedpage.com/about](https://onetypedpage.com/about/)
- **Submit Your Own**: [onetypedpage.com/submissions](https://onetypedpage.com/submissions/)

*This mobile viewer is an independent project created to enhance the One Typed Page experience and is not officially affiliated with Daniel Marleau or One Typed Page.*

## 📄 License

This project is open source and available under the MIT License.

## 🔗 Links

- [One Typed Page](https://onetypedpage.com/) - The original daily typing project
- [About Daniel Marleau](https://onetypedpage.com/about/) - Learn about the creator
- [Submit Your Page](https://onetypedpage.com/submissions/) - Contribute to the project

---

*Created with ❤️ for the typewriting community*