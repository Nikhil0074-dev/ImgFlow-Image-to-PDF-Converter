# ImgFlow - Image to PDF Converter

A modern, client-side image to PDF converter that runs entirely in your browser. No uploads to servers, no limits.

## Features

- **Drag & Drop Upload** - Easily upload images by dragging them into the upload zone
- **Multiple Format Support** - Supports JPG, PNG, BMP, GIF, and WEBP images
- **Reorder Pages** - Drag and drop to reorder pages in the PDF
- **Preview Images** - Click on any image to preview it in full size
- **Customizable Settings**:
  - Page sizes: A4, A3, A5, US Letter, Square
  - Orientation: Portrait, Landscape, Auto (per image)
  - Image fit: Fit, Fill, Stretch, Center
  - Page margins: None, Small, Medium, Large
  - Quality toggle: High/Low JPEG quality
- **Client-Side Processing**  All conversion happens in your browser. Your images never leave your device.
- **No Limits** - Convert as many images as you want

## Usage

1. Open `index.html` in a modern web browser
2. Drag and drop images into the upload zone, or click to browse
3. Reorder images by dragging the cards if needed
4. Adjust settings (page size, orientation, margins, etc.)
5. Click "Generate PDF" to create your PDF
6. Download the generated PDF

## Browser Support

- Chrome 
- Firefox
- Edge

## Technical Details

- Uses [pdf-lib](https://pdf-lib.js.org/) for PDF generation
- No server-side processing - everything runs locally
- Responsive design for desktop and mobile
