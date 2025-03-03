# NinjaSketch

An Excalidraw clone with React and TypeScript. Rough.js is used for the sketchy, hand-drawn style. I built the side project for learning purposes. I mainly focused on the functionalities since I already have plenty of projects that are responsive.

## Technologies

- `Vite`
- `React.js`
- `TypeScript`
- `Rough.js`
- `CSS`
- `Vitest`
- `Cypress` 
- `Testing Library`

## Features

Here's what you can do with NinjaSketch:

- **Choose a Tool**: You have pencils, lines, rectangles, and text tools. Pick one and start creating.

- **Draw and Move**: Click and drag on the canvas to draw. To move something, select it and drag it to a new spot. Also, resize elements by dragging the corners. Resizing only works on rectangles or lines.

- **Edit Text**: Click on the canvas and start typing to add text to your drawings. You can also edit existing text.

- **Zoom**: Use Ctrl + Scroll or click on the buttons to zoom in for detail or out to see the whole picture.

- **Pan**: Hold the Space bar and drag or use the middle mouse button to move around the whiteboard canvas.

### Keyboard Shortcuts:

Speed up your work with these shortcuts:

- **Canvas Navigation**: Press the Space bar and drag or use the middle mouse button.
- **Undo**: Ctrl + Z.
- **Redo**: Ctrl + Y or Ctrl + Shift + Z.
- **Zoom In**: Ctrl + Plus.
- **Zoom Out**: Ctrl + Minus.

## The Process

I started by rendering a canvas with rough.js to create the base for all the drawings. Then, I focused on drawing on the canvas, allowing users to make lines, rectangles, and other shapes.

Next, I made sure users could move elements around. This was important for adjusting drawings. After that, I added the ability to resize elements to give more control over the shapes.

To make sure mistakes could be fixed, I implemented undo and redo features. I also added freehand drawing for a more natural sketching experience and a text tool to label or note on the canvas.

To navigate larger drawings, I put in pan and zoom tools. With everything functioning, I designed the whole UI to make it user-friendly and appealing.

Finally, I added testing with Cypress and Testing Library. I conducted end-to-end tests on drawing and manipulating text, lines, rectangles, and freehand drawings to make sure everything worked smoothly.

Along the way, while building everything, I took notes on what I've learned so I don't miss out on it. I also documented the behind-the-scenes processes every time a feature was added.

This way, I understood what I've built. The funny thing is, as soon as I started to document what happened behind the scenes and the features I've added, it made me realize that we fully understand something once we've actually taken a step back, thought about it, and documented what we've done. I think this is a good practice to follow when learning something new.

### Discovering Rough.js:

- **New Tools**: I found out about Rough.js, which lets me make graphics look hand-drawn. This was a new and exciting tool for me.

### Deep Dive into Functions:

- **Complex Functions**: I spent time understanding the `getSvgPathFromStroke` function, which turns drawing movements into smooth paths.

### Managing Points and Drawing:

- **Working with Points**: I learned how to collect and use points from drawings, which involved understanding and managing data to reflect what the user does.

### React Hooks and Rendering:

- **New Knowledge**: I learned about `useLayoutEffect`, which helps make sure changes are done before the screen updates. This was useful for certain drawing functions.

### Advanced Event Handling:

- **User Interaction**: I worked with the wheel event listener, which allowed me to add zooming and panning features. This made the app more interactive and user-friendly.
