# Path of Exile 2 Keyboard Overlays

This folder contains different keyboard overlay styles for Path of Exile 2, designed for 2560x1440 resolution.

## Available Styles

### Movement Keys (WASD)

Simple text overlay for movement keys.

![WASD Demo](assets/wasd-demo.gif)  
_Movement keys with minimalist text display_

### Glow Style

Shows skill and flask usage with glowing effects.

![Flasks Demo](assets/flasks-glow-demo.gif)  
_Flask keys (1-2) with glow effect when pressed_

![Skills Demo](assets/skills-glow-demo.gif)  
_Skill keys (QWERT) and mouse buttons with glow effect when pressed_

#### OBS/Streamlabs Filter Settings

To achieve the proper glow effect, add a Color Key filter with these settings:

- Key Color Type: Custom Color
- Key Color: `#00000000`
- Similarity: 80
- Smoothness: 50
- Opacity: 100
- Contrast: 0.00
- Brightness: 0.00
- Gamma: 0.00

### Text Style

Simple text overlay, highlighting the key pressed with high white.

![Text Overlay Demo](assets/text-overlay-demo.gif)  
_Minimalist text overlay showing key presses_

## Features

### Movement

- WASD keys shown as plain text
- High contrast for better visibility
- No background images for clean appearance

### Combat

- Skill slots (QWERT) with glow effects
- Flask slots (1-2) with custom flask animations
- Mouse buttons and speed indicator included

### Display Options

- Glow style: Animated effects for skills and flasks
- Text style: Clean, minimal text overlay
- Mix of styles: Plain WASD with styled combat keys

## Resolution Support

Currently supports 2560x1440 resolution

## Installation

1. Choose your preferred style folder:
   - `2560x1440_glow/` for glow effects
   - `2560x1440/` for text overlay
2. Copy the corresponding files to your NohBoard installation
3. For glow style: Add the Color Key filter in OBS/Streamlabs with the settings above

## Contributing

Feel free to contribute additional styles or resolution support by creating a pull request. At some point we will add a PR to the official NohBoard repo.
