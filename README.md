HalftoneLab

https://aacd164.github.io/HalftoneLab/
https://www.aarondey.design/

HalftoneLab is a browser-based image tool that converts uploaded images into print-inspired halftone graphics. It recreates images using dot screens, line screens, bitmap effects, and CMYK-style process colour patterns, with controls for paper texture, ink spread, misregistration, and rough printed edges.

The project is built as a single-page web app using HTML, CSS, JavaScript, and the Canvas API. All image processing happens locally in the browser, so uploaded images are not sent to a server.

Features
Upload or drag and drop an image
Convert images into CMYK halftone dots
Generate mono dot, line screen, and hard bitmap effects
Adjust dot spacing, dot size, angle, and threshold
Simulate rough printed dots
Add ink spread and paper grain
Add CMYK misregistration for a more realistic print effect
Adjust brightness, contrast, scale, and image positioning
Export the final result as a PNG
Fully client-side processing
Why This Project Exists

HalftoneLab was created as an experimental design tool for generating print-style graphics directly in the browser. It is inspired by traditional printmaking, offset printing, screen printing, risograph textures, and CMYK process colour separation.

The goal is not to perfectly simulate commercial print production, but to create a fast and flexible visual tool for making expressive halftone artwork.

How It Works

The app loads an uploaded image into an HTML canvas, samples brightness and colour data from the image, then redraws the image using procedural halftone marks.

In CMYK mode, the image is converted into cyan, magenta, yellow, and black channel values. Each channel is drawn with its own screen angle and slight offset, creating a printed registration effect.

Roughness, grain, and ink spread are generated procedurally to make the dots feel less digital and more physical.

Tech Stack
HTML
CSS
JavaScript
Canvas API
Browser File API

No external libraries or frameworks are required.
