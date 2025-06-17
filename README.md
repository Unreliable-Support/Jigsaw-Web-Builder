# Jigsaw Web Builder 🧩

**Jigsaw Web Builder** is a lightweight, zero-dependency, in-browser tool for visually creating simple web pages. Built entirely with vanilla JavaScript, it provides a drag-and-drop interface to design layouts, add content, and customize styles in real-time.

The entire application is contained within a **single HTML file**, making it incredibly portable and easy to use. No builds, no dependencies, no setup required.

## ✨ Features

- **Visual Page Building**: Drag and drop components onto the canvas to build your page.
- **Component-Based**: Includes essential web components:
    - Headings, Paragraphs, Images, Buttons/Links
    - Multi-column layouts (2 or 3 columns)
    - Dividers, Lists, and embedded Videos.
- **Real-Time Inspector Panel**: Select any element on the canvas and instantly edit its properties (text, color, font size, URL, margins, etc.) in the right-hand panel.
- **Drag & Drop Reordering**: Easily rearrange elements on the page.
- **Clean Code Generation**: Generates a clean, self-contained HTML file with embedded CSS for the final page.
- **Zero Dependencies**: Runs entirely in the browser. No Node.js, no libraries, no frameworks. Just pure HTML, CSS, and JavaScript.
- **Downloadable Output**: View the generated code in a modal and download it as a complete `.html` file.

## 🚀 How to Use

It couldn't be simpler:

1.  **Download** the `yb2.html` file.
2.  **Open it** in your favorite modern web browser (like Chrome, Firefox, or Edge).
3.  That's it! You're ready to start building.

### The Workflow

1.  **Add Components**: Click on components in the left panel to add them to the workspace.
2.  **Arrange & Select**: Drag elements within the workspace to reorder them. Click on an element to select it.
3.  **Customize**: Use the right-hand Inspector panel to change the styles and content of the selected element. All changes are reflected live.
4.  **Generate & Download**: When you're done, click the "🚀 HTML Oluştur" (Generate HTML) button to see the final code and download your page.

## 🏛️ Core Concepts

The builder is organized into three main panels:

1.  **Component Panel (Left)**: A library of all available elements you can add to your page.
2.  **Workspace (Center)**: The main canvas where you build your page. It acts as a live preview.
3.  **Inspector Panel (Right)**: A context-aware panel that displays the editable properties of the currently selected element.

## 📂 File Structure

The project is intentionally contained within a **single file (`yb2.html`)** for maximum simplicity and portability. All the logic, styling, and structure are self-contained.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
