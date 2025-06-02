# Jan-1
# Jan-1: Math & Sound

**Created by Ale Mustafa**  
_"Mathematics is like a music of reason — you just have to hear it."_ — (Inspired by Niels Bohr)

## About

**Jan-1** is a project that shows math can be experienced with both the eyes and ears. Users can type in math functions, see their graphs, and hear sound waves that reflect those functions.

This project was created to make math more interactive and meaningful — especially for students who want to connect creativity with logic.

## Features

- Enter any math function (e.g., `sin(x)`, `x^2`, `|x^3|`)
- See the graph using Plotly.js
- Hear a matching tone for each function
- Styled with neon green text on black background

## Sound Mapping

| Function Type | Example     | MP3 Link (auto-plays on click)                         |
|---------------|-------------|--------------------------------------------------------|
| Sine          | `sin(x)`    | [sine-440hz.mp3](https://cdn.jsdelivr.net/gh/jackw01/sine-wave-tone/sine-440hz.mp3) |
| Cosine        | `cos(x)`    | [sine-880hz.mp3](https://cdn.jsdelivr.net/gh/jackw01/sine-wave-tone/sine-880hz.mp3) |
| Tangent       | `tan(x)`    | [square-440hz.mp3](https://cdn.jsdelivr.net/gh/jackw01/sine-wave-tone/square-440hz.mp3) |
| x²            | `x^2`       | [sine-220hz.mp3](https://cdn.jsdelivr.net/gh/jackw01/sine-wave-tone/sine-220hz.mp3) |
| Other         | `x^3`, etc. | [sine-330hz.mp3](https://cdn.jsdelivr.net/gh/jackw01/sine-wave-tone/sine-330hz.mp3) |

These are public MP3s from a GitHub CDN. They play directly in the browser.

## How to Use

1. Open `index.html` in your browser.
2. Type any math function (example: `sin(x)`)
3. Click **"Plot Graph"** to draw the function
4. Click **"Play Sound"** to hear it

## Technologies Used

- **HTML** – for structure  
- **CSS** – for visual design  
- **JavaScript** – for interactivity  
- **Math.js** – to evaluate math expressions ([https://mathjs.org/](https://mathjs.org/))  
- **Plotly.js** – to draw interactive graphs ([https://plotly.com/javascript/](https://plotly.com/javascript/))  
- **MP3s** – hosted via jsDelivr CDN ([https://www.jsdelivr.com/](https://www.jsdelivr.com/))

## License

Free to use for educational and creative projects.
