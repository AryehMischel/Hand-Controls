# Hand-Controls Component for A-Frame 
[Live Glitch Example](https://glitch.com/edit/#!/hand-controls-with-customizable-offsets)
<br/>
<br/>A custom **A-Frame Hand-Controls** component which allows adjusting the hand model's position and rotation offsets.

## Features

- Customizable offsets for hand position and rotation.
- Works just like the default **hand-controls** component with added flexibility.

## Installation

Since this is a custom component, the modified script needs to be included in your A-Frame build. To make integration easy, I've provided a pre-built version of A-Frame 1.6.0 with the custom hand-controls script included.

Alternatively, you can integrate this into any A-Frame version by following these steps:
1. Clone the desired version of A-Frame from the official repository.
2. Replace the default `hands-component` script with the custom script from this repository.
3. Rebuild the A-Frame project.

## Usage

The component behaves exactly like the default **hand-controls** component, but with the added ability to pass two optional arguments:

- `offSetPosition` - Adjusts the position of the hand (e.g., `0 0 -0.02`).
- `offSetRotation` - Adjusts the rotation of the hand (e.g., `45 0 90`).

### Example:

```html
<a-entity hand-controls="hand: left; handModelStyle: toon; offSetPosition: 0 0 -0.02; offSetRotation: 45 0 90"></a-entity>


