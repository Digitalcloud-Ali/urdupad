# UrduPad - Advanced Urdu Text Editor

![UrduPad Logo](https://img.shields.io/badge/UrduPad-v2.0-blue?style=for-the-badge&logo=windows)
![.NET](https://img.shields.io/badge/.NET-6.0-purple?style=for-the-badge&logo=dotnet)
![Platform](https://img.shields.io/badge/Platform-Windows-lightblue?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A modern, feature-rich Urdu text editor built with .NET 6 and Windows Forms, designed specifically for Urdu language writing and editing with professional-grade features.

## 🌟 Features

### 📝 Core Editing Features
- **Multi-Document Interface**: Tabbed interface for working with multiple documents
- **Rich Text Formatting**: Bold, italic, underline, font size, color, and alignment
- **Auto-Save**: Automatic document saving every 5 minutes
- **Version History**: Track and restore previous versions of your documents
- **Find & Replace**: Advanced search with regex support and case sensitivity

### 🎨 Modern UI/UX
- **Dark Mode**: Toggle between light and dark themes
- **Focus Mode**: Distraction-free writing environment
- **Modern Design**: Windows 11-inspired interface
- **Custom Styles**: Create and apply custom text styles
- **Responsive Layout**: Adaptive interface that scales with window size

### 📄 Document Management
- **Multiple Formats**: Support for RTF, PDF, and DOCX formats
- **Templates**: Pre-built document templates for common use cases
- **Recent Files**: Quick access to recently opened documents
- **Page Setup**: Configure margins, orientation, and paper size
- **Headers & Footers**: Add page numbers, dates, and custom text

### 🔤 Urdu-Specific Features
- **Auto Keyboard Switching**: Automatically switches to Urdu keyboard when typing
- **Urdu Spell Checker**: Built-in spell checking for Urdu text
- **Right-to-Left Support**: Full RTL text support for Urdu
- **Urdu Fonts**: Optimized for Jameel Noori Nastaleeq and other Urdu fonts

### 📊 Advanced Features
- **Footnotes & Endnotes**: Add and manage footnotes and endnotes
- **Batch Operations**: Process multiple files simultaneously
- **Print Support**: Print documents with headers, footers, and page numbers
- **Export Options**: Export to PDF and Word formats
- **Keyboard Shortcuts**: Comprehensive keyboard shortcuts for power users

## 🚀 Quick Start

### Prerequisites
- Windows 10/11 (64-bit)
- .NET 6.0 Runtime (included in installer)

### Installation

1. **Download the latest release** from the [Releases](https://github.com/digitalcloud-ali/urdupad/releases) page
2. **Extract the ZIP file** to your desired location
3. **Run UrduPad.exe** to start the application

### First Run
1. The application will start with a new document
2. Urdu keyboard will automatically activate when you start typing
3. Use `Ctrl+N` to create new documents
4. Use `Ctrl+S` to save your work

## 📖 User Guide

### Basic Operations

| Action | Shortcut | Description |
|--------|----------|-------------|
| New Document | `Ctrl+N` | Create a new document |
| Open Document | `Ctrl+O` | Open an existing document |
| Save Document | `Ctrl+S` | Save current document |
| Save As | `Ctrl+Shift+S` | Save with new name |
| Print | `Ctrl+P` | Print current document |
| Find | `Ctrl+F` | Search in document |
| Replace | `Ctrl+H` | Find and replace text |

### Formatting

| Action | Shortcut | Description |
|--------|----------|-------------|
| Bold | `Ctrl+B` | Make text bold |
| Italic | `Ctrl+I` | Make text italic |
| Underline | `Ctrl+U` | Underline text |
| Font Size | `Ctrl+Shift+>` | Increase font size |
| Font Size | `Ctrl+Shift+<` | Decrease font size |
| Align Left | `Ctrl+L` | Align text left |
| Align Center | `Ctrl+E` | Center text |
| Align Right | `Ctrl+R` | Align text right |

### View & Navigation

| Action | Shortcut | Description |
|--------|----------|-------------|
| Dark Mode | `Ctrl+Shift+D` | Toggle dark theme |
| Focus Mode | `F11` | Toggle focus mode |
| Zoom In | `Ctrl++` | Increase zoom level |
| Zoom Out | `Ctrl+-` | Decrease zoom level |
| Reset Zoom | `Ctrl+0` | Reset to 100% zoom |

## 🎯 Use Cases

### Academic Writing
- Research papers and theses
- Academic articles and journals
- Student assignments and reports
- Bibliography and citations

### Professional Documents
- Business letters and proposals
- Technical documentation
- Reports and presentations
- Official correspondence

### Creative Writing
- Novels and short stories
- Poetry and literature
- Scripts and screenplays
- Personal journals

### Publishing
- Book manuscripts
- Magazine articles
- News articles
- Content creation

## 🔧 Technical Details

### System Requirements
- **OS**: Windows 10 version 1903 or later / Windows 11
- **Architecture**: x64 (64-bit)
- **RAM**: 4 GB minimum, 8 GB recommended
- **Storage**: 100 MB free space
- **Display**: 1024x768 minimum resolution

### Dependencies
- .NET 6.0 Runtime
- Windows Forms
- iTextSharp (PDF export)
- DocumentFormat.OpenXml (Word support)
- System.Text.Json (JSON serialization)

### File Formats
- **Input**: RTF, TXT, DOCX
- **Output**: RTF, PDF, DOCX, TXT
- **Templates**: RTF format
- **Settings**: JSON format

## 🛠️ Development

### Building from Source

1. **Clone the repository**:
   ```bash
   git clone https://github.com/digitalcloud-ali/urdupad.git
   cd urdupad
   ```

2. **Install .NET 6.0 SDK**:
   - Download from [Microsoft's website](https://dotnet.microsoft.com/download/dotnet/6.0)

3. **Build the project**:
   ```bash
   dotnet build -c Release
   ```

4. **Run the application**:
   ```bash
   dotnet run --project UrduPad
   ```

### Project Structure
```
UrduPad/
├── UrduPad/                 # Main application
│   ├── EnhancedMainForm.cs  # Main UI form
│   ├── DocumentTab.cs       # Document tab implementation
│   ├── ThemeManager.cs      # Theme management
│   ├── PdfExporter.cs       # PDF export functionality
│   ├── DocxExporter.cs      # Word document support
│   ├── StyleManager.cs      # Custom styles system
│   ├── VersionManager.cs    # Version control
│   └── ...                  # Other components
├── README.md               # This file
└── UrduPad.sln            # Solution file
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

**DigitalCloud.no** - *Development Team*
- **Lead Developer**: Rayice
- **Organization**: DigitalCloud Ali

## 🙏 Acknowledgments

- Urdu language community for feedback and suggestions
- .NET community for excellent documentation
- Open source contributors who made this possible

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/digitalcloud-ali/urdupad/issues)
- **Discussions**: [GitHub Discussions](https://github.com/digitalcloud-ali/urdupad/discussions)
- **Email**: support@digitalcloud.no

## 🔄 Changelog

### Version 2.0 (Latest)
- ✨ Modern UI with Windows 11 design
- ✨ Tabbed document interface
- ✨ Dark mode support
- ✨ PDF and Word export
- ✨ Version history system
- ✨ Custom styles management
- ✨ Advanced find/replace
- ✨ Batch operations
- ✨ Footnotes and endnotes
- ✨ Auto Urdu keyboard switching
- ✨ Urdu spell checker
- ✨ Focus mode
- ✨ Document templates

### Version 1.0
- 🎉 Initial release
- ✨ Basic text editing
- ✨ Urdu language support
- ✨ File operations

---

**Made with ❤️ by DigitalCloud.no**

*Empowering Urdu writers with modern technology*
