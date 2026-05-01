# Certificate Editor Pro

**Certificate Editor Pro** is a free browser-based certificate editor for creating, customizing, and batch-exporting professional certificates.

Created by **Jimmy Lee**.

---

## Overview

Certificate Editor Pro is a lightweight HTML tool that runs directly in the browser.  
It allows users to design certificates visually without installing any design software.

You can drag and drop objects, edit text, upload custom backgrounds, add logos, seals, signatures or additional images, customize Vietnamese fonts, insert decorative lotus lines, save layouts, and export certificates as high-quality images.

The project is designed to be simple, portable, and useful for schools, training programs, communities, temples, academies, non-profit organizations, internal company programs, and anyone who needs to create certificates quickly.

---

## Giới thiệu

Certificate Editor Pro là công cụ thiết kế chứng nhận miễn phí chạy trực tiếp trên trình duyệt.  
Công cụ hỗ trợ kéo thả, chỉnh font tiếng Việt, upload background/logo/con dấu/chữ ký, thêm line hoa sen, lưu layout, nạp layout và xuất ảnh hàng loạt.

Dự án được phát triển miễn phí bởi **Jimmy Lee** với mong muốn hỗ trợ cộng đồng tạo chứng nhận nhanh, đẹp và dễ sử dụng.

Phiên bản mới tập trung vào nhu cầu sản xuất chứng nhận thực tế:

- Tự upload background riêng thay vì phụ thuộc background mẫu.
- Batch export từ Excel / CSV / TXT.
- Mapping linh hoạt nhiều cột dữ liệu vào nhiều object text.
- Tách nền AI để tạo ảnh PNG trong suốt.
- Chỉnh ảnh nâng cao cho logo, con dấu, chữ ký, chân dung và hình trang trí.
- Lưu/nạp JSON đầy đủ cả layout, export setting và batch mapping.

---

## Demo

```text
https://leanhtien.github.io/certificate-editor-pro/
```

---

## Features

### Core editor

- Browser-based certificate editor
- No installation required
- Single HTML file workflow
- Drag-and-drop object editing
- Edit object position, size, opacity, and layer
- Lock, hide, duplicate, and delete objects
- Bring object forward / send object backward
- Center selected object horizontally
- Upload custom certificate background
- Remove or replace certificate background
- Save layout configuration as JSON
- Load saved layout configuration
- Timestamp-based JSON file names to avoid overwriting old configurations
- Donation QR section for voluntary support

### Text editing

- Add and edit text objects
- Edit text directly on the certificate
- Support for Vietnamese fonts
- Support for handwriting-style fonts
- Font family selection
- Font size control
- Text color control
- Text alignment:
  - Left
  - Center
  - Right
- Text styling:
  - Bold
  - Italic
  - Underline
  - Strikethrough
- Text effects:
  - Gold 3D
  - Blue emboss
  - Soft shadow
  - Glow / halo effect
  - Buddhist-inspired visual effects
  - Lotus blue
  - Sutra ink
  - Bronze foil

### Image editing

- Upload logo, seal, signature, portrait, or additional image
- Replace selected image
- Fit image by original aspect ratio
- Keep aspect ratio while resizing
- AI background removal to create transparent PNG images
- Restore original image after background removal
- Crop transparent image tightly around the visible subject
- Rotate image
- Flip image horizontally
- Flip image vertically
- Adjust image brightness
- Adjust image contrast
- Adjust image saturation
- Blend modes:
  - Normal
  - Multiply
  - Screen
  - Overlay
  - Soft light
- Shadow presets:
  - No shadow
  - Soft shadow
  - Raised shadow
  - Seal shadow
  - Signature shadow
- Reset all image adjustments

### Decorative lotus line library

- Built-in lotus / Buddhist-inspired decorative line library
- Add decorative line elements directly to the certificate
- Resize decorative lines
- Change decorative line color after insertion
- Layer decorative lines like normal image objects

### Export

- Export one certificate as PNG
- Export one certificate as JPG
- Export quality scale options:
  - 2x
  - 3x
  - 4x
  - 5x
  - 6x
- Export presets:
  - Current canvas size
  - A4 150 DPI
  - A4 200 DPI
  - A4 300 DPI
  - Social vertical
- JPG quality control
- Export settings are saved inside the layout JSON

### Batch export

- Batch export certificates from data files
- Supported data formats:
  - `.xlsx`
  - `.xls`
  - `.csv`
  - `.txt`
- Flexible data mapping:
  - Map any data column to any text object
  - Add a custom prefix before each mapped value
  - Add multiple mapping rows for multiple fields
- Automatically remove duplicate data rows
- Export generated certificates as a ZIP file
- ZIP file name includes timestamp to avoid conflicts

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
- Student certificates
- Temple / academy programs
- Multi-recipient certificate campaigns

---

## How to Use

1. Open the app in your browser.
2. Upload your custom certificate background if needed.
3. Click any object on the certificate to edit it.
4. Change text, position, size, font, color, opacity, layer, or effect.
5. Upload a logo, seal, signature, portrait, or additional image if needed.
6. Use **Tách nền AI** if you need a transparent image.
7. Add decorative lotus lines from the built-in library.
8. Save your layout configuration if you want to reuse it later.
9. Export a single certificate as PNG/JPG, or upload a data file for batch export.

---

## Working with Backgrounds

The editor is designed for custom certificate backgrounds.

Recommended workflow:

1. Design or generate the certificate background externally.
2. Upload it into the editor.
3. Add editable text, logos, seals, signatures, and decorative elements on top.
4. Save the final layout as JSON.

This keeps the editor lightweight and gives users full control over certificate design.

---

## Image Transparent / AI Background Removal

The editor supports creating transparent images directly from uploaded images.

### How to create a transparent image

1. Click **+ Thêm ảnh**.
2. Upload a normal image.
3. Select the uploaded image on the certificate.
4. Click **Tách nền AI**.
5. The app removes the background and converts the result into a transparent PNG.
6. Click **Crop sát chủ thể** if the image has too much empty transparent space.
7. Use **Khôi phục ảnh gốc** if you want to return to the original image.

### Recommended use cases

- Logo
- Seal
- Signature
- Portrait
- Product image
- Decorative image asset

### Notes

- The first AI background removal may take longer because the browser needs to load the AI model.
- Internet connection may be required when the AI library/model is loaded for the first time.
- The result is best when the image has a clear subject and a background with enough contrast.
- Difficult cases such as hair, blurred edges, low-resolution images, white object on white background, or complex backgrounds may need manual review.

---

## Image Editing Tips

### Signature

Recommended settings:

```text
Blend mode: Multiply
Shadow: Signature shadow or Soft shadow
Brightness: adjust only if the scan is too dark or too light
Contrast: increase slightly if the signature is pale
```

### Seal / Stamp

Recommended settings:

```text
Blend mode: Multiply
Shadow: Seal shadow
Saturation: increase slightly if the stamp color is weak
Crop: Crop sát chủ thể after background removal
```

### Logo

Recommended settings:

```text
Blend mode: Normal
Shadow: No shadow or Soft shadow
Keep aspect ratio: enabled
```

### Portrait

Recommended settings:

```text
Background removal: optional
Crop: Crop sát chủ thể
Shadow: Soft shadow
Brightness / Contrast: adjust lightly
```

---

## Batch Export

The batch export feature allows you to generate many certificates from a data file.

### Supported files

- Excel: `.xlsx`, `.xls`
- CSV: `.csv`
- Text: `.txt`

### Example Excel data

```text
MÃ SỐ SINH VIÊN | PHÁP DANH
2350000057      | Thích Nữ Bảo Huệ
2350000058      | Thích Nữ Diệu Tâm
2350000059      | Thích Nữ Minh An
```

### Example mapping

```text
PHÁP DANH          → Pháp danh object     → Prefix: Pháp danh:
MÃ SỐ SINH VIÊN    → MSSV object          → Prefix: MSSV:
```

The app will generate one certificate for each data row.

### Flexible mapping

You are not limited to only names or student IDs.  
If your Excel file has more fields, you can map them to additional text objects.

Examples:

```text
HỌ TÊN             → Name object
NGÀY SINH          → Date of birth object
LỚP                → Class object
KHÓA               → Course object
XẾP LOẠI           → Ranking object
SỐ CHỨNG NHẬN      → Certificate number object
```

### ZIP export

When exporting in batch mode, the app creates a ZIP file containing all generated certificate images.

The ZIP file name includes a timestamp, for example:

```text
certificates_20260501_130435.zip
```

---

## Layout Configuration

The app supports saving and loading layout configuration as JSON.

This is useful when you want to:

- Reuse the same certificate layout
- Prepare multiple certificate templates
- Share layouts with other users
- Keep a backup of your design
- Edit the default certificate layout later
- Continue editing from a saved state

### Saved JSON includes

- Background image
- Background color / background style
- All text objects
- All image objects
- Object positions
- Object sizes
- Object layers
- Object opacity
- Font settings
- Text effects
- Image editing settings
- Transparent image state
- Original image and processed image when available
- Export settings
- Batch mapping settings

### JSON file name

Saved JSON files use timestamp-based names to avoid accidental overwriting.

Example:

```text
certificate-layout_20260501_130435.json
```

---

## Recommended Export Settings

### For print

```text
Format: PNG
Preset: A4 300 DPI
Scale: 5x or 6x
```

### For online preview

```text
Format: JPG
Preset: Current canvas
Scale: 2x or 3x
JPG Quality: 85–92
```

### For archival / best quality

```text
Format: PNG
Preset: A4 300 DPI
Scale: 6x
```

---

## Recommended Workflow

For professional certificate production:

1. Prepare a clean certificate background.
2. Open the editor.
3. Upload the background.
4. Add fixed text elements.
5. Add logo, seal, signature, and decorative lines.
6. Use **Tách nền AI** for signatures, seals, or logos if needed.
7. Use **Crop sát chủ thể** after background removal.
8. Adjust image blend mode and shadow if needed.
9. Save the layout as JSON.
10. Upload Excel / CSV / TXT data.
11. Map data columns to certificate text objects.
12. Preview the data.
13. Export all certificates as ZIP.
14. Review output files before printing, publishing, or sending.

---

## Recommended File Structure

Minimal version:

```text
certificate-editor-pro/
├── index.html
├── README.md
└── LICENSE
```

More organized version:

```text
certificate-editor-pro/
├── index.html
├── README.md
├── LICENSE
├── assets/
│   ├── backgrounds/
│   ├── logos/
│   ├── signatures/
│   └── screenshots/
├── layouts/
│   └── certificate-layout_YYYYMMDD_HHMMSS.json
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

Current demo:

```text
https://leanhtien.github.io/certificate-editor-pro/
```

---

## Browser and Internet Requirements

The app can be opened directly from a local HTML file.

Recommended browsers:

- Google Chrome
- Microsoft Edge
- Brave
- Safari

Some advanced features use CDN-loaded browser libraries:

- Image export
- ZIP export
- Excel reading
- AI background removal
- Web fonts

For the best experience, open the file with an Internet connection, especially when using Excel import or AI background removal for the first time.

---

## Privacy

Certificate Editor Pro runs directly in your browser.  
Your uploaded images, names, and layout data are processed locally in the browser and are not sent to any server by default.

Important note:

- The app may load external JavaScript libraries, fonts, AI models, or WASM files from CDN providers.
- The image processing itself is designed to happen in the browser.
- If you deploy or modify the project, review all external dependencies based on your privacy and compliance requirements.

---

## Third-Party Libraries

This project may use third-party browser libraries for features such as:

- Image export
- ZIP generation
- Excel reading
- AI background removal
- Web fonts

Third-party libraries are governed by their own licenses.  
If you plan to use this project commercially, distribute it publicly, or integrate it into a paid product, review the third-party licenses carefully.

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

Third-party libraries included or loaded by the app are governed by their own licenses.

See the `LICENSE` file and third-party library documentation for details.

---

## Disclaimer

This tool is provided as-is, without any warranty.

Users are responsible for checking the accuracy of:

- Certificate content
- Names and student IDs
- Organization names
- Course names
- Certificate numbers
- Signatures
- Seals
- Export quality
- Batch output accuracy
- Legal and academic validity of the final certificate

Always review exported certificates before printing, publishing, or sending them to recipients.
