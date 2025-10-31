# Release-tracking
Tracking of releases for executive summary

## 🌐 View Release Notes

Visit our GitHub Pages site to view all release notes: [Release Notes](https://thomas-tnt.github.io/Release-tracking/)

## 📝 How to Add New Releases

1. Edit the `index.html` file in this repository
2. Copy an existing release article block (the `<article class="release">` section)
3. Update the following information:
   - Version number
   - Release date
   - Release type badge (`major`, `minor`, or `patch`)
   - Release notes content (features, improvements, bug fixes, etc.)
4. Commit and push your changes to GitHub
5. GitHub Pages will automatically update within a few minutes

## 🏷️ Release Type Guidelines

- **MAJOR**: Breaking changes or significant new features
- **MINOR**: New features without breaking changes  
- **PATCH**: Bug fixes and minor improvements

## 🎨 Customization

The `index.html` file includes embedded CSS styling. You can customize:
- Colors and theme
- Typography and fonts
- Layout and spacing
- Section headers and badges

## 🚀 Setting Up GitHub Pages

To enable GitHub Pages for this repository:

1. Go to repository Settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the branch you want to deploy (e.g., `main`)
4. Select "/ (root)" as the folder
5. Click "Save"
6. Your site will be published at `https://thomas-tnt.github.io/Release-tracking/`

## 📄 File Structure

```
.
├── index.html          # Main release notes page with styling
└── README.md          # This file
```
