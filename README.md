# Collaborative Whiteboard

**Live Demo:** [https://collaborative-whiteboard-madhurpareek.vercel.app](https://collaborative-whiteboard-madhurpareek.vercel.app/)

An interactive, browser-based digital whiteboard application built with React and HTML5 Canvas. Designed for smooth freehand sketching, geometric shape drawing, and quick diagramming with a responsive, distraction-free interface.

## Features

- **Drawing Tools:** Freehand brush, straight lines, rectangles, circles, arrows, and text insertion.
- **Customization Toolbox:** Dynamic stroke color picker, fill color options, and adjustable brush/line width.
- **Canvas Actions:** Precision eraser tool, undo/redo history management, and one-click canvas export/download.
- **State Management:** Modular state architecture using React Context API (`BoardProvider` and `ToolboxProvider`) for clean separation between canvas rendering and tool settings.

## Tech Stack

- **Frontend:** React.js (Functional Components & Hooks)
- **Graphics & Rendering:** HTML5 Canvas API / Rough.js
- **Styling:** Tailwind CSS & CSS Modules
- **State Management:** React Context API

## Getting Started

Follow these steps to run the project locally on your machine:

### Prerequisites
- Node.js (v16 or higher)
- npm

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MadhurPareek06/collaborative-whiteboard.git
   cd collaborative-whiteboard
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser to use the whiteboard.