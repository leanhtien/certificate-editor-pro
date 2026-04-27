# Certificate Editor Pro

**Certificate Editor Pro** is a free browser-based certificate editor for creating, customizing, and batch-exporting professional certificates.

Created by **Jimmy Lee**.

---

## Overview

Certificate Editor Pro is a lightweight HTML tool that runs directly in the browser.  
It allows users to design certificates visually without installing any software.

You can drag and drop objects, edit text, upload custom backgrounds, add logos or signatures, customize Vietnamese fonts, insert decorative lotus lines, save layouts, and export certificates as images.

The project is designed to be simple, portable, and useful for schools, training programs, communities, temples, academies, non-profit organizations, and anyone who needs to create certificates quickly.

---

## Demo

After enabling GitHub Pages, the app can be accessed at:

```text
https://YOUR_USERNAME.github.io/certificate-editor-pro/
```

Replace `YOUR_USERNAME` with your GitHub username.

---

## Features

- Browser-based certificate editor
- No installation required
- Drag-and-drop object editing
- Edit object position, size, opacity, and layer
- Upload custom certificate background
- Upload logo, seal, signature, or additional images
- Add and edit text objects
- Support for Vietnamese fonts
- Support for handwriting-style fonts
- Text styling:
  - Bold
  - Italic
  - Underline
  - Strikethrough
- Text effects:
  - Gold 3D
  - Blue emboss
  - Soft shadow
  - Glow effect
  - Buddhist-inspired visual effects
- Decorative lotus line library
- Adjustable line color
- Lock, hide, duplicate, and delete objects
- Save layout configuration as JSON
- Load saved layout configuration
- Export one certificate as PNG
- Batch export certificates from a list of names
- Automatically remove duplicate names during batch export
- Export files as ZIP for batch download
- Donation QR section for voluntary support

---

## Use Cases

Certificate Editor Pro can be used for:

- Course completion certificates
- Training certificates
- Buddhist academy certificates
- Community event certificates
- Workshop certificates
- Online class certificates
- Volunteer certificates
- Internal company certificates
- Award certificates
- Appreciation certificates

---

## How to Use

1. Open the app in your browser.
2. Upload your custom background if needed.
3. Click any object on the certificate to edit it.
4. Change text, position, size, font, color, opacity, layer, or effect.
5. Upload a logo, seal, signature, or additional image if needed.
6. Add decorative lotus lines from the built-in library.
7. Save your layout configuration if you want to reuse it later.
8. Export a single certificate as PNG, or upload a name list for batch export.

---

## Batch Export

You can upload a `.txt` or `.csv` file containing a list of names.

Example:

```txt
Nguyễn Văn A
Trần Thị B
Lê Văn C
```

The app will generate one certificate for each name.

Duplicate names will be removed automatically before exporting.

When exporting in batch mode, the app creates a ZIP file containing all generated certificate images.

---

## Layout Configuration

The app supports saving and loading layout configuration as JSON.

This is useful when you want to:

- Reuse the same certificate layout
- Prepare multiple certificate templates
- Share layouts with other users
- Keep a backup of your design
- Edit the default certificate layout later

---

## Recommended File Structure

```text
certificate-editor-pro/
├── index.html
├── README.md
└── LICENSE
```

For a more organized version:

```text
certificate-editor-pro/
├── index.html
├── README.md
├── LICENSE
├── assets/
│   ├── screenshots/
│   └── backgrounds/
└── docs/
    └── usage-guide.md
```

---

## GitHub Pages Deployment

You can publish this project for free using GitHub Pages.

Steps:

1. Create a public GitHub repository.
2. Upload `index.html`, `README.md`, and `LICENSE`.
3. Go to **Settings**.
4. Go to **Pages**.
5. Under **Build and deployment**, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save.
7. Wait for GitHub Pages to generate your website link.

The website URL will look like this:

```text
https://YOUR_USERNAME.github.io/certificate-editor-pro/
```

---

## Donation

This project is free to use.

If you find it useful, you can support the author through the donation QR included in the app.

> Mọi sự ủng hộ sẽ chỉ dùng để duy trì máy chủ và làm từ thiện nhé các bạn!

Donation is completely voluntary and not required to use the tool.

---

## Author

**Jimmy Lee**

---

## License

This project is licensed under the **MIT License**.

You are free to use, modify, and share this project, as long as the original license and copyright notice are included.

See the `LICENSE` file for details.

---

## Disclaimer

This tool is provided as-is, without any warranty.

Users are responsible for checking the accuracy of certificate content, organization names, signatures, seals, and exported files before publishing or printing.
