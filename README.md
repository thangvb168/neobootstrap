# Neobootstrap

Neobootstrap is a learning project aimed at exploring and practicing Bootstrap Core and its Design System. This project helps in understanding Bootstrap components, using them effectively in web development, and optimizing UI/UX design.

This project is inspired by and based on [Bootstrap](https://github.com/twbs/bootstrap).

## 🚀 Goals
- Gain a deep understanding of Bootstrap Core
- Apply Bootstrap's Design System
- Rewrite Bootstrap components from scratch

## 🛠 Technologies Used
- **Bootstrap**: A popular CSS framework for fast UI development
- **SCSS**: Enables easy customization and extension of Bootstrap
- **HTML, CSS, JavaScript**: Core web development technologies

## 📌 How to Use

### 1. Clone Repository
```sh
git clone https://github.com/thangvb168/neobootstrap.git
cd neobootstrap
```

### 2. Compile SCSS to CSS
There are two ways to compile SCSS into CSS:

#### Step 1: Install Extensions Live Sass Compiler

#### Step 2: Create a `.vscode/settings.json` file with the following content:
```json
{
    "liveSassCompile.settings.formats": [
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "/assets/css"
        }
    ],
    "liveSassCompile.settings.generateMap": true,
    "liveSassCompile.settings.autoprefix": ["last 2 versions", "> 1%"],
    "liveSassCompile.settings.showOutputWindowOn": "Debug"
}
```
#### Step 3: Click on the "Watch Sass" button in the bottom right corner.

### 3. Open `index.html` in Browser to test NeoBootstrap

## 📂 Project Structure
```
neobootstrap/
│── scss/
│   ├── mixins/                     # SCSS Mixins
│   ├── neobootstrap.scss           # Main SCSS file
│── assets/ 
│   |──css/
│       ├── neobootstrap.css        # Main CSS file
│       ├── neobootstrap.css.map    # CSS source map
│── index.html                      # Main page
|── README.md                       # Project documentation
|── .gitignore                      # Git ignore file
|── .vscode/                        # VS Code settings
└── README.md                       # Project documentation
```

## 📖 Learning & References
- [Github Bootstrap](https://github.com/twbs/bootstrap)
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- [SCSS Guide](https://sass-lang.com/guide/)

## 📌 Notes
This project is for learning purposes only. It is not intended to be used in production.

---
## Author
This project is maintained by [thangvb168](https://github.com/thangvb168). Feel free to reach out if you have any questions or suggestions.