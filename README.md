# Swagger Master

<p align="center">
  <img src="docs/images/swagger-master-logo.svg" alt="Swagger Master Logo" width="200"/>
  <br>
  <i>A lightweight, single-file Swagger UI manager for multiple OpenAPI specifications</i>
  <br>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#demo">Demo</a> •
  <a href="#quick-start">Quick Start</a> •
  <a href="#usage">Usage</a> •
  <a href="#customization">Customization</a> •
  <a href="#deployment">Deployment</a> •
  <a href="#contributing">Contributing</a>
</p>

<p align="center">
  <a href="https://github.com/tobyqin/swagger-master/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/tobyqin/swagger-master" alt="license">
  </a>
  <a href="https://github.com/tobyqin/swagger-master/stargazers">
    <img src="https://img.shields.io/github/stars/tobyqin/swagger-master" alt="stars">
  </a>
  <a href="https://github.com/tobyqin/swagger-master/network/members">
    <img src="https://img.shields.io/github/forks/tobyqin/swagger-master" alt="forks">
  </a>
</p>

## Features

- 📦 **Single File** - No build process, no dependencies to install
- 🔄 **Multiple API Support** - Switch between different OpenAPI specifications seamlessly
- 🚀 **Easy Deployment** - Host anywhere as a static file
- ⚡ **Fast Loading** - Uses CDN for all external resources
- 🎨 **Clean UI** - Intuitive interface with API selector
- 🔧 **Easy Configuration** - Simple API list customization

## Screenshot

<p align="center">
  <img src="docs/images/swagger-master.png" alt="Swagger Master Screenshot" width="800"/>
  <br>
  <i>Swagger Master in action - managing multiple API specifications</i>
</p>

## Demo

Visit our [live demo](https://tobyqin.github.io/swagger-master) to see Swagger Master in action.

## Quick Start

1. Download the `index.html` file
2. Add your API list to the `API_LIST` array in the `index.html` file
3. Open the `index.html` file in your browser to test it out
4. Host anywhere as a static file

## Customization

### Styling

The UI is customizable through the CSS section in the `index.html` file. Key style classes:

- `#api-selector` - The API selection dropdown container
- `#swagger-ui` - The main Swagger UI container
- `.info-icon` - The information icon styling

### Configuration Options

The API list is configured in the `index.html` file. The `API_LIST` array contains the API specifications. Each API specification is an object with a `name` and `url` property.

```javascript
const API_LIST = [
  {
    name: "This is the Petstore API",
    url: "https://petstore3.swagger.io/api/v3/openapi.json",
  },
  // Add more APIs as needed
];
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Swagger UI](https://github.com/swagger-api/swagger-ui) for the amazing API documentation tool
- [Font Awesome](https://fontawesome.com) for the icons

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/tobyqin">Toby Qin</a>
</p>
