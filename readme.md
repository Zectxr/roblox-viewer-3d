# Roblox 3D Viewer

A web-based 3D clothing preview application for Roblox avatars, built with React and Three.js.

## Features

- **3D Avatar Models**: Preview clothing on different Roblox avatar types (Blocky R15, Man R15, Woman R15)
- **OBJ Model Support**: Uses Wavefront OBJ files for 3D models
- **Three.js Rendering**: High-quality 3D rendering in the browser
- **Client-side Processing**: All previewing happens locally - no data sent to servers
- **Responsive Design**: Works on desktop and mobile devices

## Avatar Models Included

- `blocky-r15.obj` - Classic blocky Roblox avatar
- `man-r15.obj` - Male R15 avatar
- `woman-r15.obj` - Female R15 avatar

## Getting Started

### Prerequisites

- A modern web browser with WebGL support
- Python 3.x (for local development server)

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Zectxr/roblox-viewer-3d.git
   cd roblox-viewer-3d
   ```

2. Start a local HTTP server:
   ```bash
   python -m http.server 8000
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

### Usage

1. Upload your Roblox clothing images (PNG/JPG)
2. Select an avatar model from the dropdown
3. View the 3D preview with your clothing applied
4. Export or save your designs

## Project Structure

```
├── index.html              # Main HTML file
├── static/
│   ├── css/
│   │   └── main.bf854d51.css    # Compiled CSS
│   ├── js/
│   │   └── main.8f927e24.js     # Compiled React/Three.js app
│   └── media/              # Fonts and assets
├── models/                 # OBJ 3D model files
│   ├── blocky-r15.obj
│   ├── man-r15.obj
│   └── woman-r15.obj
└── readme.md               # This file
```

## Technologies Used

- **React** - UI framework
- **Three.js** - 3D rendering engine
- **Webpack** - Build system (original)
- **HTTrack** - Website mirroring tool (for initial setup)

## Development

This project was created by mirroring the original ingame.clothing website and enhancing it with local OBJ model support.

### Building from Source

The original source code would need to be de-minified and reconstructed from the bundled files for development.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## License

This project is for educational purposes. Please respect Roblox's terms of service and intellectual property.

## Disclaimer

This is a client-side preview tool. Your clothing designs are not uploaded or stored anywhere - everything runs locally in your browser.

## Support

For issues or questions, please open an issue on GitHub.