📐 Linear Interpolation — Lerp

<p align="center"> Exploring the math </p>

<p align="center"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" /> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" /> </p>

While learning about Linear Interpolation (Lerp), I explored how a simple formula can be used to smoothly transition between values and create different visual and audio effects.

I wanted to understand the formula and how it works in practice. Especially how it can be applied to different things.

Linear interpolation calculates a value between a starting point and an ending point using a parameter t.

lerp
⁡
(
𝑎
,
𝑏
,
𝑡
)
=
𝑎
+
(
𝑏
−
𝑎
)
𝑡

Where:

a is the starting value.
b is the ending value.
t controls the interpolation, typically between 0 and 1.

As t changes, the result moves between the two values.

The basic formula can be implemented in JavaScript with just one function:

function lerp(a, b, t) {
    return a + (b - a) * t;
}

Built With
    HTML5 — Page structure and canvas.
    CSS3 — Styling and visual presentation.
    JavaScript — Interpolation logic and animation.
    Canvas API — Drawing points and text.
    Web Audio API — Experimenting with sound.

What is Demonstrated
    How linear interpolation works mathematically.
    How to interpolate between two positions.
    How the same formula can work with colours and sound.

Running the Project
    Clone or download this repository.
    Open the project folder in your code editor.
    Open the HTML file in your browser.
    Experiment with the code and see how changing the interpolation parameter affects the results.

No external libraries are required.
