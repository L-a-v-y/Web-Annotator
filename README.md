# Web Annotator

Web Annotator is a Chrome extension that allows users to annotate webpages by highlighting content, adding notes, and customizing their annotation experience. Annotations persist across browser sessions, ensuring that users can revisit their highlighted content and notes even after closing and reopening the browser.

## Features

- **Highlight Content:** Users can select and highlight text on any webpage using customizable color-coded highlights to mark and categorize significant sections.
- **Add Notes:** Ability to attach contextual notes to highlighted content, allowing users to add personal insights, comments, or additional information for future reference.
- **Persistence:** Annotations persist across browser sessions, ensuring users can revisit annotated pages with their highlights and notes intact.
- **Customization Options:** Provide options for users to customize highlight colors and styles to suit their preferences.
- **Search and Filter:** Enable users to search for specific annotations or filter annotations based on criteria such as date, category, or keyword.
- **Export and Share:** Allow users to export annotated pages with highlights and notes to share with others or save for offline reference.
- **Keyboard Shortcuts:** Offer keyboard shortcuts for efficient annotation, highlighting, and navigation within the extension.
- **Responsive Design:** Ensure that the extension interface is responsive and works seamlessly across different screen sizes and resolutions.

## Installation

### Manual Installation

1. Clone the repository or download the ZIP file and extract it.
2. Open the Chrome browser and navigate to `chrome://extensions/`.
3. Enable "Developer mode" by toggling the switch in the top right corner.
4. Click on the "Load unpacked" button and select the extracted folder or the cloned repository folder.
5. The Web Annotator extension should now appear in your list of installed extensions.

## Usage
1. Click on the Web Annotator extension icon in the Chrome toolbar to open the popup interface.
2. Use the provided options to highlight content, add notes, customize annotations, and manage your annotations.
3. Highlights and notes will persist across sessions, allowing you to revisit them anytime.
4. Use the search bar and filters to quickly find specific annotations.
5. Export your annotated pages using the "Export" button in the popup interface.

## Files and Structure

- **background.js**: Handles background processes and persistent data storage.
- **clear_storage.js**: Contains functions to clear stored annotations.
- **comment.js**: Manages note-taking functionality.
- **content.js**: Injects the necessary scripts and styles into webpages for annotation.
- **injection.js**: Facilitates text highlighting and annotation insertion on webpages.
- **manifest.json**: Metadata and configuration for the Chrome extension.
- **popup.css**: Styles for the popup interface.
- **popup.html**: HTML structure for the popup interface.
- **popup.js**: Logic for the popup interface including search, export, and note management.
- **style.css**: General styles for the extension.

## Keyboard Shortcuts
- Well, you can set whatever you want from the Keyboard Shortcuts Page in Extensions Section of the Browser.
- `Ctrl + Shift + H`: Highlight selected text.
- `Ctrl + Shift + N`: Add a note to the selected text.
- `Ctrl + Shift + E`: Export annotations.

### Prerequisites

- JavaScript
- Node.js
- HTML
- CSS
- JSON
- npm
- Chrome Extension APIs
- DOM Manipulation
- Event Handling
- Asynchronous JavaScript
- Local Storage and Sync Storage:
- Browser DevTools

### Setup

1. Clone the repository.
2. Install the dependencies. ('npm install') 

