# Noco

Noco is a desktop note editor with tab management and appearance customization.  
It supports reading and saving Markdown and text files with rich text editing.

日本語版: [README.md](README.md)

## Target OS

- Windows

## Key Features

- Multi-tab note management
  - New tabs, drag & drop reorder
  - Auto title from the first line, unsaved indicator and confirm before close
- Rich text editing
  - Headings, bold, italic, strikethrough, inline code
  - Blockquotes, code blocks, bullet lists, numbered lists
  - Link insertion, undo/redo
- Table editing
  - Insert tables with row/column size, add/remove rows and columns (context menu)
  - Copy tables as TSV
  - Paste TSV/CSV/HTML tables to create tables
- File I/O
  - Read and save Markdown (.md/.markdown) and text (.txt)
  - Choose .md or .txt when saving (Save As supported)
  - Markdown saves are converted to Markdown text (tables may be kept as HTML)
  - .txt saves write the Markdown text by default (choose TSV/CSV when tables exist)
  - .txt loads are not interpreted as Markdown
- Appearance customization
  - Font selection (standard fonts / TTF/OTF) with custom font removal
  - Apply the selected font to code blocks too
  - Background image with blur and opacity controls
  - Color overlay and opacity (HSV color picker)
  - Theme / accent / editor text colors
  - Blockquote and code block background color & opacity
  - Table border width
  - Line wrap toggle and toolbar visibility
- UI interactions
  - Toggle the settings panel (floating gear button)
  - Custom title bar and resize handles
- Editor zoom (Ctrl + mouse wheel, Ctrl + 0 to reset)
- Save tab state and settings on exit, restore on next launch

## Keyboard Shortcuts

- Ctrl + S: Save
- Ctrl + O: Open
- Ctrl + T: New tab
- Ctrl + W: Close tab
- Ctrl + B: Bold
- Ctrl + I: Italic
- Ctrl + Z: Undo
- Ctrl + Y or Ctrl + Shift + Z: Redo
- Ctrl + 0: Reset zoom
