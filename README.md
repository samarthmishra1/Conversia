# Conversia

> One workspace for every file.

Conversia is a cloud-based file conversion, editing, and file management platform designed to let users convert, edit, and manage almost any type of file from a single application.

The long-term goal of Conversia is to combine a powerful conversion engine, cloud storage integrations, document and image editing, and AI-powered tools into one unified workspace.

---

## 🚧 Project Status

**Early Development**

Conversia is currently being built from the ground up.

The current focus is establishing the frontend architecture and core application infrastructure before developing the full conversion engine.

---

# 🎯 Vision

Today, converting files often requires using multiple websites and applications.

Conversia aims to provide a single platform where users can:

- Convert files between different formats
- Upload and manage files
- Use their existing cloud storage
- Edit documents and images
- Perform batch conversions
- Extract text using OCR
- Edit images using AI-assisted tools
- Keep conversion history
- Automate file workflows

The goal is simple:

> **Upload it. Convert it. Edit it. Manage it.**

---

# ✨ Planned Features

## 🔄 Universal File Conversion

Conversia will support a wide range of file formats across multiple categories.

### Images

- PNG
- JPG / JPEG
- WEBP
- GIF
- TIFF
- BMP
- SVG

### Documents

- PDF
- DOCX
- DOC
- TXT
- HTML
- Markdown
- EPUB

### Spreadsheets

- XLSX
- XLS
- CSV
- ODS

### Presentations

- PPTX
- PPT
- ODP

### Audio

- MP3
- WAV
- FLAC
- AAC
- OGG
- M4A

### Video

- MP4
- MOV
- MKV
- AVI
- WEBM
- FLV

### Archives

- ZIP
- TAR
- GZIP
- 7Z

Additional formats will be added as the conversion engine develops.

---

# 🧠 Conversion Engine

The core of Conversia will be a modular conversion engine.

Instead of creating a separate application for every file type, Conversia will use a central conversion system that detects the input format and routes the file to the appropriate converter.

```text
                 Conversion Request
                         │
                         ▼
                  File Detection
                         │
                         ▼
                Conversion Router
                         │
        ┌────────────────┼────────────────┐
        ▼                ▼                ▼
      Images         Documents          Media
        │                │                │
        ▼                ▼                ▼
   Image Engine     Document Engine    FFmpeg
