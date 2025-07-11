# ASCII-me-nbd
# ASCII Art Converter

A web application that converts uploaded images into animated ASCII art.

## Features

- **Drag & Drop Interface**: Simply drag and drop images or click to select files
- **Multiple Image Formats**: Supports JPEG, PNG, GIF, and other common image formats
- **Customizable Output**: 
  - Adjustable width (20-200 characters)
  - **Multiple character sets simultaneously**: Mix and match Standard, Detailed, Blocks, and Dots
  - Animation effects (Glow, Matrix, Wave)
- **Download Functionality**: 
  - Download as plain text (.txt) file
  - Download as styled HTML (.html) file with animations preserved
- **Real-time Preview**: See both original image and ASCII conversion
- **Responsive Design**: Works on desktop and mobile devices

## How to Use

1. Open `index.html` in your web browser
2. Upload an image by:
   - Dragging and dropping a file onto the upload area
   - Clicking "Choose Image" to select a file
3. Adjust settings as desired:
   - **Width**: Controls the number of characters per line
   - **Animation**: Adds visual effects to the ASCII art
   - **Character Sets**: Select multiple character sets to create unique combinations
4. View your animated ASCII art!
5. Download your creation:
   - Click "Download as .txt" for a plain text file
   - Click "Download as .html" for a styled version with animations

## Technical Details

The application uses:
- HTML5 Canvas API for image processing
- FileReader API for handling file uploads
- CSS3 animations for visual effects
- Responsive design with CSS Grid and Flexbox

## Browser Compatibility

Works with all modern browsers that support:
- HTML5 Canvas
- FileReader API
- CSS3 animations
- ES6 JavaScript features

## Installation

No installation required! Just open `index.html` in your web browser.

## License

This project is open source and available under the MIT License.
