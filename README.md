# TheGrowthClub.Website

A professional website for The Growth Club, dedicated to empowering personal and professional development.

## 🌐 Live Website

This website is hosted on GitHub Pages and can be accessed at:
- `https://TheGrowthClub.github.io`

## 🚀 GitHub Pages Setup (Organization Page)

This repository is configured as an **organization GitHub Pages site** for a cleaner URL (`https://TheGrowthClub.github.io` instead of `https://username.github.io/repository-name/`).

### Steps to Set Up Organization GitHub Pages:

#### 1. Create GitHub Organization
- Go to GitHub and create a new organization named **"TheGrowthClub"**
- Navigate to: https://github.com/organizations/plan

#### 2. Transfer Repository
- Go to this repository's **Settings**
- Scroll down to the **Danger Zone**
- Click **Transfer ownership**
- Enter the organization name: `TheGrowthClub`
- Complete the transfer

#### 3. Rename Repository
- After transfer, go to the repository **Settings** in the organization
- Change the repository name to: `TheGrowthClub.github.io`
- This special naming convention makes it the organization's primary GitHub Pages site

#### 4. Enable GitHub Pages
- Go to repository **Settings** → **Pages**
- Under **Source**, select:
  - Branch: `main` (or your default branch)
  - Folder: `/ (root)`
- Click **Save**
- Your site will be published at `https://TheGrowthClub.github.io`

### Alternative: Project Page Setup

If you prefer to keep it as a project page under a personal account:
1. Go to your repository on GitHub
2. Click on **Settings**
3. Navigate to **Pages** in the left sidebar
4. Under **Source**, select:
   - Branch: `main` (or your default branch)
   - Folder: `/ (root)`
5. Click **Save**
6. Your site will be published at `https://<username>.github.io/<repository-name>/`

## 📁 Project Structure

```
TheGrowthClub.Website/
├── index.html          # Main landing page
├── styles.css          # CSS styling
├── _config.yml         # GitHub Pages configuration
├── README.md           # This file
└── LICENSE             # MIT License
```

## 🛠️ Local Development

To view the website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/TheGrowthClub/TheGrowthClub.github.io.git
   ```
   
   *Note: If the repository hasn't been transferred yet, use the current URL:*
   ```bash
   git clone https://github.com/VishalCodingNinja/TheGrowthClub.Website.git
   ```

2. Open `index.html` in your web browser

That's it! The website uses plain HTML and CSS, so no build process is required.

## ✨ Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Easy to Customize**: Simple HTML/CSS structure for easy modifications
- **Fast Loading**: Lightweight static website with no dependencies
- **SEO Friendly**: Proper meta tags and semantic HTML

## 🎨 Customization

To customize the website:

1. **Content**: Edit `index.html` to change text, sections, and structure
2. **Styling**: Modify `styles.css` to adjust colors, fonts, and layout
3. **Theme**: Update the color scheme by changing the gradient colors in CSS

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## 📧 Contact

For questions or suggestions, please reach out via GitHub issues.
