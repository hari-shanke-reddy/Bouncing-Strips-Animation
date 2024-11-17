Bouncing Strips Animation
This project showcases an engaging bouncing animation of colorful strips created using HTML, CSS, and JavaScript. The animation is fully customizable, responsive, and provides user controls to start, stop, and reset the animation.

Features
Interactive Animation: Colorful strips bounce up and down within a container.
Customizable Speeds: Each strip has a unique bounce speed defined by data-speed attributes.
User Controls:
Start: Begin the animation.
Stop: Pause the animation.
Reset: Return the strips to their initial positions.
Responsive Design: Adjusts seamlessly to different screen sizes.
Code Highlights
HTML Structure:

A container (.animation-container) holds five strips, each styled and animated individually.
CSS Styling:

Strips: Styled with unique colors and aligned horizontally within the container.
Controls: Buttons styled with a clean, modern look for interaction.
JavaScript Logic:

Implements an animation loop using requestAnimationFrame for smooth, efficient animations.
Tracks the position and direction of each strip using an array of objects.
Provides robust control functions:
Start Animation: Begins or resumes the bouncing motion.
Stop Animation: Pauses all animations.
Reset Animation: Resets all strips to their initial positions.
How It Works
Animation Logic:

Each strip moves vertically based on its data-speed value.
When a strip reaches the top or bottom boundary of the container, it reverses direction, creating a smooth bouncing effect.
User Interaction:

Start Button: Triggers the animation by iterating over each strip and applying its unique speed and direction.
Stop Button: Halts the animation without resetting positions.
Reset Button: Stops the animation and resets all strips to their initial positions.
