# Interactive Particle Animation

A stunning front-end animation that creates an interactive particle system with multiple mouse interaction modes and visual effects.

## Features

### Interactive Particle System

- Dynamic particles that move around the screen
- Particles form connections when they get close to each other
- Connection opacity changes based on distance between particles
- Glowing particle effect with gradient colors

### Mouse Interaction Modes

- **Attract Mode**: Particles are drawn toward your cursor
- **Repel Mode**: Particles move away from your cursor
- **Swirl Mode**: Particles swirl around your cursor in a cyclonic pattern

### Click Effects

- Click anywhere to create a pulsing ripple effect
- Clicking also generates a burst of particles that fade out over time

### Customizable Settings

- **Particle Count**: Control how many particles appear on screen
- **Connection Distance**: Adjust how far particles can be to form connections
- **Particle Speed**: Change how quickly particles move around
- **Mouse Influence**: Set how strongly your cursor affects nearby particles

## How to Use

1. Open the HTML file in any modern web browser
2. Move your mouse to interact with the particles
3. Click to create pulse effects and particle bursts
4. Use the control panel in the bottom left to adjust settings
5. Switch between interaction modes using the buttons in the top right

## Technical Details

This animation is built using HTML5 Canvas and vanilla JavaScript. It doesn't require any external libraries or dependencies.

The animation creates a visual network of particles that:

- Move with randomized velocities
- Connect with lines when in proximity
- Respond to mouse movement with different behaviors
- React to clicks with special effects

## Customization

You can customize the animation further by:

- Changing the color palette in the `getRandomColor()` function
- Adjusting the background color in the CSS
- Modifying the particle size range
- Adding new interaction modes
- Tweaking the physics parameters

## Browser Compatibility

This animation works in all modern browsers that support HTML5 Canvas:

- Chrome
- Firefox
- Safari
- Edge

## Performance Notes

The animation performance depends on:

- The number of particles (higher counts require more processing power)
- The connection distance (larger distances create more connections to render)
- Your device's GPU and CPU capabilities

If you experience performance issues, try reducing the particle count or connection distance using the sliders.