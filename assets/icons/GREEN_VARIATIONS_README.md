# Green Icon Variations for Cline Extension

This directory contains green variations of the original Cline extension icons. All variations maintain the same design and dimensions as the original while offering different green color schemes.

## Available Green Variations

### 1. Forest Green (`icon-green.*`)
- **Color**: #2E7D32
- **Style**: Professional, nature-inspired
- **Best for**: Corporate environments, professional use
- **Files**: `icon-green.svg`, `icon-green.png`

### 2. Emerald Green (`icon-emerald.*`)
- **Color**: #00C851
- **Style**: Vibrant, modern
- **Best for**: Creative environments, modern interfaces
- **Files**: `icon-emerald.svg`, `icon-emerald.png`

### 3. Mint Green (`icon-mint.*`)
- **Color**: #4CAF50
- **Style**: Softer, friendly
- **Best for**: Accessible design, gentle on the eyes
- **Files**: `icon-mint.svg`, `icon-mint.png`

### 4. Matrix Green (`icon-matrix.*`)
- **Color**: #00FF41
- **Style**: Cyberpunk, tech-inspired
- **Best for**: Developer themes, high-contrast environments
- **Files**: `icon-matrix.svg`, `icon-matrix.png`

## Panel Icons

Green panel icons (16x16 pixels) have been created for each color variation:

### Forest Green Panel Icons
- `robot_panel_dark_green.png` - For dark VSCode themes
- `robot_panel_light_green.png` - For light VSCode themes

### Additional Panel Icon Variations
- `robot_panel_emerald.png` - Emerald green panel icon
- `robot_panel_mint.png` - Mint green panel icon  
- `robot_panel_matrix.png` - Matrix green panel icon

All panel icons are properly sized (16x16) and maintain the robot character design in their respective green colors.

## Usage

To use any of these green variations in your Cline extension:

1. **For main extension icon**: Replace the `icon` field in `package.json`:
   ```json
   "icon": "assets/icons/icon-green.png"
   ```

2. **For activity bar icon**: Update the `icon` field in the `viewsContainers` section:
   ```json
   "icon": "assets/icons/icon-green.svg"
   ```

3. **For panel icons**: Use the appropriate green panel icons in your webview or UI components.

## File Formats

- **SVG files**: Vector format, scalable, recommended for VSCode activity bar
- **PNG files**: Raster format, good for extension marketplace and package.json icon field

## Color Accessibility

All green variations have been chosen to maintain good contrast and readability in both light and dark VSCode themes. The colors are:
- Web-safe and widely supported
- Accessible for most users including those with color vision differences
- Professional and suitable for development environments

## Original Files

The original icon files remain unchanged:
- `icon.svg` - Original SVG icon
- `icon.png` - Original PNG icon
- `robot_panel_dark.png` - Original dark panel icon
- `robot_panel_light.png` - Original light panel icon
