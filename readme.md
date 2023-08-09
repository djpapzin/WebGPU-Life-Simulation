![WebGPU Life Demo](demo.gif)

# WebGPU Life

This project demonstrates the capabilities of the WebGPU API by implementing Conway's Game of Life. WebGPU is a modern API for accessing GPU capabilities in web apps, providing both rendering and compute functionalities. This project leverages WebGPU's rendering capabilities to draw a grid representing the Game of Life and its compute capabilities to simulate the game's state.

## Tech Stack

- **HTML5**: For the structure of the web page.
- **JavaScript**: For the application logic and interaction with the WebGPU API.
- **WebGPU API**: A modern API that offers advanced graphics and computation capabilities, surpassing its predecessor, WebGL.

## Project Structure

The primary file of this project is `index.html`, which contains the HTML structure and the JavaScript code that interacts with the WebGPU API.

## How to Run

1. Ensure you have a recent version of Chrome (113 or later) on ChromeOS, macOS, or Windows. While WebGPU aims to be a cross-browser, cross-platform API, it hasn't been universally adopted yet.
2. Open the `index.html` file in a browser that supports the WebGPU API.
   
   **Important:** WebGPU is still an experimental feature in many browsers. You might need to enable it manually in your browser settings. Refer to your browser's documentation for guidance.

## WebGPU Overview

### What is WebGPU?

WebGPU is a successor to WebGL, bringing the advancements of modern GPU APIs like Direct3D 12, Metal, and Vulkan to the web platform. It offers a cross-platform approach to harness GPU features in a manner that feels natural for web development.

#### Rendering

While GPUs are often associated with rendering detailed graphics, WebGPU is designed to support popular rendering techniques across both desktop and mobile GPUs. It also provides a foundation for adding new features as hardware capabilities evolve.

#### Compute

Beyond rendering, WebGPU provides the ability to perform general-purpose, highly parallel workloads using compute shaders. These shaders can operate independently or integrate seamlessly with the rendering pipeline.

### Conway's Game of Life

In this project, you'll be building [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), a cellular automaton where a grid of cells evolves over time based on specific rules. Cells can become active or inactive depending on their neighboring cells' states, leading to captivating patterns that change as the game progresses.

## Learning Outcomes

By exploring this project, you'll learn:

- How to set up WebGPU and configure a canvas for rendering.
- Drawing simple 2D graphics using WebGPU's rendering capabilities.
- Using vertex and fragment shaders to modify the rendered content.
- Employing compute shaders to simulate the Game of Life.
- Gaining a foundational understanding of WebGPU without diving deep into related topics like 3D matrix math.

## Additional Resources

For those interested in diving deeper into WebGPU or looking for a comprehensive guide, consider checking out [Your first WebGPU app](https://codelabs.developers.google.com/your-first-webgpu-app) on Google Codelabs.