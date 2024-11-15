# Link Saver Chrome Extension

![Link Saver](icons.png)

## Overview

Link Saver is a Chrome extension that allows you to save links with custom titles directly in your browser. You can easily delete them, and even generate a shareable link to send all saved links to others.

## Features

-  Save links with custom titles
-  Delete saved links
-  Generate a shareable text file containing all saved links

## How to Use the Link Saver Chrome Extension

### 1. Clone or Download the Repository

First, you need to clone this repository to your local machine or download it as a ZIP file:

#### Cloning the Repository

To clone the repository using Git, open your terminal and run:

```bash
git clone https://github.com/Debanjan-dev/Link_saver-Extension
```

### Downloading as a ZIP

Alternatively, you can download the repository as a ZIP file:

1. Go to the GitHub repository page.
2. Click the "Code" button and select "Download ZIP."
3. Extract the contents of the ZIP file to a folder on your computer.

### 2. Load the Extension in Chrome

1. Open Google Chrome.
2. Go to the Extensions page by entering `chrome://extensions/` in the address bar.
3. Enable **Developer mode** by clicking the toggle switch in the top right corner.
4. Click the **Load unpacked** button that appears.
5. In the file dialog, navigate to the folder where you cloned or extracted the extension files.
6. Select the folder containing the `manifest.json` file and click "Select Folder."

The extension will now be installed and should appear in your list of Chrome extensions.

### 3. Use the Extension

-  **Open the Extension:**

   -  Click on the Link Saver icon in your Chrome toolbar.

-  **Save a Link:**

   -  Enter a title in the "Enter a title" field.
   -  Enter a URL in the "Enter a link" field.
   -  Click the "Save Link" button.

-  **Manage Saved Links:**

   -  The saved links will be displayed in a list.
   -  Each link can be deleted by clicking the "Delete" button next to it.

-  **Generate a Shareable Link:**
   -  Click the "Generate Shareable Link" button to download a text file (`saved_links.txt`) containing all your saved links and their titles.

### 4. Uninstall the Extension

If you want to remove the extension:

1. Go to `chrome://extensions/`.
2. Find the Link Saver extension in the list.
3. Click the "Remove" button to uninstall it.

### Troubleshooting

-  **Extension Not Working:** Ensure that all files are properly loaded and that you followed the steps correctly. Open the Chrome Developer Tools (`Ctrl + Shift + I`) and check the "Console" tab for any error messages.
-  **No Links Displayed:** Make sure you've entered a valid title and URL before clicking "Save Link."
