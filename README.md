[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Try_Now-blue?style=for-the-badge)](https://xraman-71.github.io/Deep-Work-Tab-Manager-project/)

# Deep-Work — Tab Manager

<!-- SEO Keywords: tab manager, browser tab organizer, session manager, productivity tool, vanilla javascript, tab saver, browser organization, workspace manager, tab groups, browser productivity -->

A beautiful, minimalist tab management solution that helps you organize your browsing sessions and eliminate tab clutter. Built with vanilla JavaScript, featuring an elegant design and powerful productivity features.

## 🏷️ Topics

`tab-manager` `session-manager` `browser-tabs` `productivity` `vanilla-javascript` `tab-organizer` `workspace-manager` `browser-extension-alternative` `tab-saver` `browser-productivity` `web-app` `single-page-app` `local-storage` `no-framework` `minimalist-design`

## ✨ Features

### 🎯 Session Management
- **Save Current Tabs**: Instantly save all open tabs into organized sessions
- **One-Click Restore**: Reopen entire sessions with a single click
- **Smart Organization**: Group related tabs by project, task, or context
- **Demo Data**: Pre-loaded example sessions to help you get started

### 🔍 Command Palette
- **Quick Search**: Find sessions instantly with `Ctrl/Cmd + K`
- **Keyboard Navigation**: Navigate through sessions without touching your mouse
- **Fast Actions**: Open, export, or delete sessions directly from the palette

### 📊 Dashboard Analytics
- **Session Stats**: Track total sessions, tabs, and storage usage
- **Activity Overview**: Visualize your browsing organization
- **Color Coding**: Assign custom colors to different sessions for visual identification

### 💾 Data Management
- **Local Storage**: All data stays in your browser—complete privacy
- **Export/Import**: Backup sessions as JSON files
- **Persistent Data**: Sessions survive browser restarts
- **Demo Mode**: Includes sample sessions for first-time users

### 🎨 Beautiful Design
- **Modern UI**: Clean, minimal interface with smooth animations
- **Particle Effects**: Subtle interactive background on landing page
- **Responsive**: Works seamlessly on desktop and mobile
- **Dark UI Elements**: Professional black-and-white color scheme
- **Custom Fonts**: Uses Syne and DM Sans for typography

## 🚀 Getting Started

### Quick Start

1. **Download**: Clone this repository or download `deep-work.html`
2. **Open**: Double-click the HTML file to open in your browser
3. **Launch**: Click "Launch Dashboard" to start organizing your tabs

### First-Time Use

1. The app loads with demo sessions to help you understand the interface
2. Click any demo session to see how tab restoration works
3. Create your first real session by clicking "Save Current Tabs"
4. Give it a name and optional emoji, then save

## 📖 How to Use

### Saving a Session

1. Open the tabs you want to save
2. Navigate to the Deep-Work dashboard
3. Click the floating "+" button (bottom right)
4. Name your session and choose a color
5. Click "Save Session"

### Restoring a Session

**Method 1: From Dashboard**
- Click "Open Session" on any session card

**Method 2: Command Palette**
- Press `Ctrl/Cmd + K`
- Type session name
- Press Enter

### Managing Sessions

- **Edit**: Click the edit icon to change session name or color
- **Delete**: Click the delete icon to remove a session
- **Export**: Use the export button to download as JSON
- **Stats**: View tab count and creation date on each card

### Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + K` | Open command palette |
| `Esc` | Close modals/palette |
| `Enter` | Confirm actions |
| Arrow keys | Navigate palette |

## 🛠️ Technical Details

### Built With

- **HTML5**: Semantic, accessible markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript**: No frameworks or dependencies
- **LocalStorage API**: For data persistence
- **Canvas API**: For particle effects

### Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Any modern browser with LocalStorage support

### File Structure

```
deep-work.html          # Single-file application
├── HTML Structure      # Semantic markup
├── CSS Styles          # Embedded styles with animations
└── JavaScript          # All logic and interactivity
```

## 🎨 Customization

### Color Themes

Sessions support 8 color themes:
- Blue (`#3B82F6`)
- Purple (`#8B5CF6`)
- Pink (`#EC4899`)
- Green (`#10B981`)
- Orange (`#F59E0B`)
- Red (`#EF4444`)
- Teal (`#14B8A6`)
- Indigo (`#6366F1`)

### Modifying Colors

Edit the color swatches in the JavaScript section:

```javascript
var colorSwatches = [
  { name: 'Blue', value: '#3B82F6' },
  // Add your custom colors here
];
```

## 📊 Data Structure

Sessions are stored in localStorage as JSON:

```json
{
  "id": "unique-timestamp",
  "name": "Project Name",
  "emoji": "🚀",
  "color": "#3B82F6",
  "created": 1640000000000,
  "tabs": [
    {
      "title": "Example Page",
      "url": "https://example.com",
      "favicon": "https://example.com/favicon.ico"
    }
  ]
}
```

## 🔒 Privacy & Security

- **Local-Only**: All data stays in your browser
- **No Tracking**: No analytics or external requests
- **No Sign-Up**: Works completely offline
- **Your Control**: Export and delete data anytime

## 💡 Use Cases

### For Developers
- Separate sessions for different projects
- Keep documentation tabs organized
- Quick context switching between codebases

### For Researchers
- Organize research by topic
- Save article collections
- Manage reference materials

### For Students
- Group resources by course or subject
- Save study material sessions
- Organize assignment research

### For Remote Workers
- Separate work and personal browsing
- Project-specific tab collections
- Meeting prep resources

## 🤝 Contributing

Contributions are welcome! This is a single-file application, making it easy to:

1. Fork the repository
2. Make your changes to `deep-work.html`
3. Test thoroughly in multiple browsers
4. Submit a pull request

### Ideas for Contributions

- [ ] Session folders/grouping
- [ ] Session sharing via export
- [ ] Browser extension version
- [ ] Tab deduplication
- [ ] Search within sessions
- [ ] Session templates
- [ ] Dark mode toggle
- [ ] Multiple themes

## 📝 License

MIT License - feel free to use this project for personal or commercial purposes.

## 🐛 Known Issues

- Some browser extensions may interfere with tab access
- Very large sessions (100+ tabs) may slow down restoration
- Favicons may not load for all websites

## 📞 Support

Having issues? Here's how to get help:

1. Check the in-app Help modal (? icon)
2. Review the FAQ section on the landing page
3. Open an issue on GitHub
4. Ensure you're using a modern browser version

## 🎯 Roadmap

- [ ] Browser extension for seamless integration
- [ ] Cloud sync option for multiple devices
- [ ] Session scheduling (auto-open at specific times)
- [ ] Tab search across all sessions
- [ ] Session analytics and insights
- [ ] Bulk operations on sessions

## ⭐ Acknowledgments

- Design inspired by modern productivity tools
- Icons and visual elements are custom-created
- Uses Google Fonts: Syne and DM Sans

---

**Made with ❤️ .By- AMANXR.For productivity enthusiasts**

*Keep your browser organized. Keep your mind clear.*
