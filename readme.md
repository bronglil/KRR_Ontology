# KRR Ontology Visualization

## Overview
This repository contains an interactive visualization for Knowledge Representation and Reasoning (KRR) ontology.

## Access Options

### Option 1: Online Deployed Version
Access the deployed visualization directly at:
```
https://krr-ontology.onrender.com/index-en.html
```

### Option 2: Local Setup
If the online version isn't accessible, run locally:

1. Clone this repository
2. Navigate to the parent directory in terminal
3. Start a Python HTTP server:
   ```bash
   python3 -m http.server 8000
   ```
4. Open in browser:
   ```
   http://localhost:8000/output/index-en.html
   ```

## Features
- Interactive ontology exploration
- Hierarchical concept navigation
- Relationship visualization
- Detailed component information

## Directory Structure
```
.
├── Output/
│   ├── resources      
│   ├── section/              
│   └── webvowl/  
|   └── index-en.html/                # Main file
└── ...
```

## Troubleshooting

### Common Issues
- **Port already in use**: Try another port (e.g., `python3 -m http.server 8080`)
- **Access denied**: Check firewall settings
- **Visualization not loading**: Ensure all files are present in the output directory

### Requirements
- Python 3.x
- Modern web browser (Chrome, Firefox, Safari, Edge)
