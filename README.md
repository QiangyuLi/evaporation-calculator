# Interactive Nomograph for Sprinkler Evaporation Loss

A digital implementation of the Frost and Schwalen nomograph for estimating evaporation loss in sprinkler irrigation systems.

## Overview

This interactive web application digitizes the classic nomograph developed by K.R. Frost and H.C. Schwalen for calculating evaporation losses during sprinkler irrigation. The tool provides real-time calculations and visualizations based on key environmental and system parameters.

## Features

- **Interactive Input Controls**: Adjust parameters using intuitive sliders
  - Vapor-pressure deficit (0-1.0 psi)
  - Nozzle diameter (8-64 sixty-fourths of an inch)
  - Nozzle pressure (20-80 psi)
  - Wind velocity (0-15 mph)

- **Real-time Visualization**: Watch the nomograph lines and intersections update dynamically
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern Interface**: Clean, professional design with smooth animations

## Usage

1. **Access the Tool**: Visit the [live application](https://yourusername.github.io/repository-name)
2. **Adjust Parameters**: Use the sliders in the left panel to set your irrigation conditions
3. **View Results**: The evaporation loss percentage updates automatically
4. **Interpret Nomograph**: Observe how the connecting lines intersect to determine the result

## Technical Implementation

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS via CDN
- **Canvas Graphics**: HTML5 Canvas for nomograph visualization
- **Responsive**: Mobile-first design approach

## Scientific Background

This tool is based on the research published by K.R. Frost and H.C. Schwalen in their seminal paper:

**"Evapotranspiration During Sprinkler Irrigation"**  
*Transactions of the ASAE, Vol. 3, No. 1, 1960, pp. 18-20*  
DOI: [10.13031/2013.41072](https://doi.org/10.13031/2013.41072)

The original nomograph provides a graphical method for estimating water loss due to evaporation during sprinkler irrigation, which is crucial for efficient water management in agricultural systems.

## Installation & Development

### Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/repository-name.git
cd repository-name

# Open in browser
open index.html
```

### GitHub Pages Deployment
This project is automatically deployed via GitHub Pages. Any changes pushed to the `main` branch will update the live application.

## File Structure
```
├── index.html          # Main application file
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Contributing

This is an academic tool. If you notice any discrepancies with the original Frost-Schwalen nomograph or have suggestions for improvements, please open an issue or submit a pull request.

## Disclaimer

**FOR ACADEMIC AND RESEARCH USE ONLY**

This tool is provided for educational and research purposes. While based on established scientific principles, users should:

- Verify results with original published sources
- Consider local environmental factors not captured in the model
- Consult with irrigation specialists for practical applications
- Use appropriate safety factors for critical irrigation decisions

The authors and contributors assume no responsibility for any consequences arising from the use of this tool in practical irrigation planning or water management decisions.

## License

This project is open source and available under the [MIT License](LICENSE).

## Citation

If you use this tool in academic research, please cite both the original work and this implementation:

```
Original Research:
Frost, K.R., & Schwalen, H.C. (1960). Evapotranspiration During Sprinkler Irrigation. 
Transactions of the ASAE, 3(1), 18-20. https://doi.org/10.13031/2013.41072

Digital Implementation:
[Your Name]. (2025). Interactive Nomograph for Sprinkler Evaporation Loss [Computer software]. 
GitHub. https://github.com/yourusername/repository-name
```

## Contact

For questions or feedback regarding this digital implementation, please open an issue on this repository.

---

*Based on the original Frost-Schwalen nomograph for agricultural irrigation planning.*
