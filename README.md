# IntersectionObserver Visualization Demo

This project demonstrates a practical implementation of the IntersectionObserver API in JavaScript. It provides a visual representation of how IntersectionObserver works with custom rootMargin settings.

## Features

- Visual representation of IntersectionObserver's observation area
- Dynamic updating of observed elements
- Customizable rootMargin
- Real-time feedback on element intersection
- Responsive design that adapts to window resizing

## How it works

The demo displays a series of boxes on a scrollable page. A green dashed border represents the IntersectionObserver's effective viewport, which is set to the middle 50% of the screen using rootMargin.

As you scroll, boxes entering this area turn red, illustrating when elements are considered "intersecting" by the IntersectionObserver. The demo ensures only one box is highlighted at a time, showcasing how to manage multiple intersecting elements.

This visualization is particularly useful for understanding:
- How rootMargin affects the observation area
- The behavior of IntersectionObserver during scrolling
- Techniques for managing multiple observed elements

## Usage

Simply open the HTML file in a web browser to see the demo in action. Scroll to observe how elements interact with the IntersectionObserver.

This demo serves as an educational tool for developers looking to understand and implement IntersectionObserver in their projects.
