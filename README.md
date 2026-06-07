# DeCodeX - Interactive DNA Structure Explorer 🧬

## Overview
DeCodeX is a classroom-ready, interactive web-based tool for exploring DNA structure. Students can visualize the B-form double helix, examine base pairing rules, and learn about transcription through interactive 3D visualization.

## Features
- **Interactive 3D Helix**: Rotate and explore the DNA double helix
- **Bond Visualization**: View hydrogen bonds between base pairs
- **Base Pair Details**: Inspect A-T and G-C pairing with bond counts
- **Coding/Non-Template Strand**: Toggle visibility of both DNA strands
- **DNA → mRNA Transcription**: Watch real-time transcription animation
- **Purine/Pyrimidine Diagrams**: Learn base structure differences
- **Responsive Design**: Works on desktop, tablet, and mobile

## Teacher Customization

### Color Scheme
Search for `COLOR SCHEME` in the HTML file to modify:
- Base pair colors (A-T, G-C)
- Backbone colors (5'→3', 3'→5')
- Highlight colors

### Animation Speed
Modify `ROTATE_SPEED` constant in the JavaScript section:
```javascript
const ROTATE_SPEED = 0.009; // Higher = faster rotation
```

### Base Pair Sequence
Edit the `SEQ_NC` array to change the DNA sequence:
```javascript
const SEQ_NC = ['A','G','T','C','A','G','T','C','A','G'];
```

## Usage
1. Open `index.html` in a modern web browser
2. Use the control buttons to:
   - **Rotate**: Start/stop helix rotation
   - **Labels**: Show base pair labels
   - **H-Bonds**: Toggle hydrogen bond visualization
   - **Coding/Non-Template**: Show second strand bases
   - **ℹ**: Display helix dimensions
   - **DNA → mRNA**: Visualize transcription
   - **↺**: Reset view

## Educational Benefits
- Visual learning for DNA structure
- Interactive exploration encourages discovery
- Aligned with AP Biology and NCERT Grade 12 curricula
- Supports multiple learning styles

## Browser Support
- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge

## File Structure
```
DNA-DecodeX/
├── index.html    (Main application file)
└── README.md     (This file)
```

## Technical Details
- Pure HTML/CSS/JavaScript (no dependencies)
- Canvas-based rendering for smooth animations
- Responsive design with media queries
- Accessibility features (ARIA labels, semantic HTML)

## License
Open source educational tool

## Contact
For questions or suggestions, please open an issue on GitHub.
