📐 Linear Interpolation (Lerp)

Explore the mathematics behind Linear Interpolation (Lerp) and discover how a simple formula can create smooth transitions between values, positions, colours, and even sound.

This project demonstrates how Lerp works mathematically and how it can be applied in practice using HTML5, CSS3, and JavaScript.

🧮 The Mathematics

Linear interpolation calculates a value between a starting point and an ending point using a parameter 
𝑡
.

The formula is:

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

a — The starting value.
b — The ending value.
t — The interpolation parameter, typically between 0 and 1.

As t changes, the result moves between the two values.

For example:

When t = 0, the result is a.
When t = 0.5, the result is halfway between a and b.
When t = 1, the result is b.

For the simplest setup, open the HTML file directly in your browser. If your project uses browser features that require a local server, run it using your editor's local development server.

No external libraries are required.
