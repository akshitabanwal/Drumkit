# Drumkit
A small project based on javascript

# Drum Kit

This project is a simple Drum Kit web application built with HTML, CSS, and JavaScript. Users can play different drum sounds by clicking on the buttons or pressing the corresponding keys on their keyboard.

## Features

- **Interactive Buttons**: Click on the drum buttons to play sounds.
- **Keyboard Support**: Use the keys `w`, `a`, `s`, `d`, `j`, `k`, and `l` to trigger corresponding drum sounds.
- **Animations**: Buttons are visually animated when activated.

## Technologies Used

- **HTML**: For the structure of the web page.
- **CSS**: For styling and layout.
- **JavaScript**: For adding interactivity and sound effects.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/akshitabanwal/Drumkit.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Drumkit
   ```

3. **Open the Project**:
   Open `index.html` in your preferred web browser to start the Drum Kit.

## How to Use

1. Open the web page.
2. Click on any of the drum buttons (`w`, `a`, `s`, `d`, `j`, `k`, `l`) to play a sound.
3. Alternatively, press the corresponding keys on your keyboard to play sounds.

## File Structure

```
Drumkit/
├── index.html        # The main HTML file
├── styles.css        # The CSS file for styling
├── index.js          # The JavaScript file for interactivity
├── sounds/           # Folder containing sound files
│   ├── crash.mp3
│   ├── kick-bass.mp3
│   ├── snare.mp3
│   ├── tom-1.mp3
│   ├── tom-2.mp3
│   ├── tom-3.mp3
│   └── tom-4.mp3
└── images/           # (Optional) Placeholder for images
```

## JavaScript Implementation

- **Event Listeners**:
  - Adds a `click` event listener to all buttons.
  - Adds a `keypress` event listener to detect key presses.

- **makeSound Function**:
  - Plays the corresponding sound based on the key pressed or button clicked.

- **buttonAnimation Function**:
  - Adds a temporary CSS class to animate the button when pressed.







