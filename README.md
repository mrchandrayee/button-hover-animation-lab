# Button Hover Animation

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/button-hover-animation-lab/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

Responsive standalone project reconstructed from the supplied 19.6-second screen recording.

## Eight hover effects
1. Slide Fill
2. Border Draw
3. Shine Sweep
4. Gradient Move
5. Ripple Hover
6. Neon Border
7. Flip Button
8. Glow Button

Each button is interactive on hover (and touch devices can tap to activate supported hover styles). Each card includes the corresponding CSS snippet.

## Run
Open `index.html` directly, or run:
```bash
python3 -m http.server 8000
```
Then visit http://localhost:8000.

## Source-derived code details
Readable values/declarations from the recording have been retained where visible:
- Slide Fill: `background: #22c55e`, `width: 0`, `height: 100%`, `transition: 0.4s`, `z-index: -1`
- Border Draw: `height: 2px`, `background: #f59e0b`, `transition: .3s`
- Shine Sweep: `.btn:hover::after { animation: shine .8s; }`, keyframe `100% { left: 150%; }`
- Gradient Move: `animation: gradientMove 2s linear infinite`, keyframe background-position `0%` to `300%`
- Ripple Hover: `box-shadow: 0 0 0 10px rgba(16,185,129,0.3)`
- Neon Border: shadows at `10px`, `20px`, and `40px` using `#0ff`
- Flip Button: `transform: rotateX(360deg)`
- Glow Button: blue button shown; hover glow is a runnable reconstruction because its full CSS is not legible in the recording.

The video shows snippets and preview states, not the complete source repository. Unreadable declarations were reconstructed to make all eight demos work. No external dependencies are used.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
