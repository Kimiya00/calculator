# Web Calculator
 
A clean, responsive calculator built with vanilla JavaScript. No frameworks, just solid fundamentals.

## Features

- Basic arithmetic operations
- Keyboard support
- Calculation history
- Error handling for edge cases
- Mobile-friendly design
- Dark mode support

## Demo

[Live Demo](https://kimiya00.github.io/Calculator)

## Getting Started

Just download and open `index.html` in your browser. That's it.

Or clone and serve locally:
```bash
git clone https://github.com/Kimiya00/Calculator.git
cd Calculator
python -m http.server 8000  # or any local server
```

## How to Use

**Mouse/Touch:**
- Click buttons to calculate

**Keyboard:**
- Numbers: `0-9`
- Operations: `+ - * /`
- Calculate: `Enter` or `=`
- Clear: `Escape` or `C`
- Delete: `Backspace`
- History: Click the 📋 button

## Why I Built This

I wanted to create something that looked modern but worked everywhere - no build tools, no dependencies, just clean code that runs in any browser. It started as a basic calculator but I kept adding features as I thought of edge cases users might encounter.

The glassmorphism design was inspired by current design trends, and I added the history feature because I found myself wishing calculators remembered previous calculations.

## Technical Stuff

**Built with:**
- HTML5
- CSS3 (Grid, Flexbox, custom properties)
- Vanilla JavaScript
- Tailwind CSS for base styles

**Key challenges solved:**
- **State management** - Keeping track of operands and operations across multiple calculations
- **Input validation** - Preventing overflow and handling edge cases gracefully  
- **Responsive design** - Making sure it works on phones without feeling cramped
- **Keyboard integration** - Full keyboard support without breaking browser shortcuts

## What I Learned

This project taught me a lot about handling user input edge cases and state management without a framework. The trickiest part was getting the operator chaining to feel natural - like when you type `5 + 3 * 2` and expect it to work intuitively.

I also spent way too much time on the button hover animations, but they make it feel more polished.

## Browser Support

Works in all modern browsers. Tested on:
- Chrome/Edge 90+
- Firefox 88+  
- Safari 14+
- Mobile browsers

---

**Contact:** [Razdarkim@gmail.com](mailto:Razdarkim@gmail.com) | [Portfolio](https://github.com/Kimiya00)
