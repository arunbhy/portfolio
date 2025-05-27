# Portfolio Website

This is my personal portfolio website built with React and Vite, deployed using GitHub Pages.

## Features

- 🌓 Dark/Light mode toggle
- 📱 Fully responsive design
- 🎨 Modern UI with smooth animations
- 📝 Sections for About, Skills, Projects, Education, and Contact
- 🔗 Social media integration
- 🎯 Smooth scrolling navigation

## 🚀 Deployment

The website is automatically deployed to GitHub Pages whenever changes are pushed to the main branch. The deployment process is handled by the `gh-pages` package.

### Deployment Steps

1. Make your changes to the codebase
2. Run the following commands:
   ```bash
   npm run build
   npm run deploy
   ```

The site will be deployed to: https://arunbhy.github.io/portfolio/

## 🛠️ Development

### Prerequisites

- Node.js (Latest LTS version recommended)
- npm (comes with Node.js)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/arunbhy/portfolio.git
   cd portfolio
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run deploy` - Deploy to GitHub Pages
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint

## 📦 Dependencies

### Main Dependencies
- React 18
- Bootstrap 5
- React Bootstrap
- React Anchor Link Smooth Scroll
- React Type Animation

### Development Dependencies
- Vite
- ESLint
- gh-pages

## 🔧 Troubleshooting

If you encounter any issues with deployment:

1. Clean the gh-pages cache:
   ```bash
   rm -rf node_modules/.cache/gh-pages
   ```

2. Clean git references:
   ```bash
   git gc --prune=now
   git remote prune origin
   ```

3. Try deploying again:
   ```bash
   npm run deploy
   ```

## 📝 License

This project is open source and available under the MIT License.

## Project Structure

```
portfolio/
├── src/
│   ├── components/     # React components
│   ├── assets/        # Images and other static files
│   ├── context/       # React context providers
│   ├── App.jsx        # Main App component
│   └── main.jsx       # Entry point
├── public/            # Static files
└── index.html         # HTML template
```

## Customization

### Changing Content
- Update text content in respective component files
- Modify images in the `src/assets` directory
- Update project details in `src/assets/files/ProjectDetails.js`
- Update skills in `src/assets/files/SkillsDetails.js`

### Styling
- Main styles are in individual component CSS files
- Global styles in `src/App.css`
- Theme colors can be modified in CSS variables

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Contact

Your Name - [@your_twitter](https://twitter.com/your_twitter) - email@example.com

Project Link: [https://github.com/arunbhy/portfolio](https://github.com/arunbhy/portfolio) 