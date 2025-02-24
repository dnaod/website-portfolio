# Personal Website Portfolio

A professional portfolio website built with Hugo using a modified version of the `hugo-resume` theme. The site showcases professional experience, projects, and skills in a clean, responsive format.

## Dependencies

- [Hugo](https://gohugo.io/) (Extended version) v0.92.0 or later
- [Git](https://git-scm.com/) for version control and theme management

## Quick Start

1. Clone this repository:
```bash
git clone https://github.com/yourusername/website-portfolio.git
cd website-portfolio
```

2. Initialize and update the theme submodule:
```bash
git submodule init
git submodule update
```

3. Start the Hugo development server:
```bash
hugo server -D
```

4. View the site at http://localhost:1313

## Customization

### Content
- Edit files in the `content/` directory to modify page content
- Update `config.toml` for site configuration
- Add images to `static/img/`

### Theme
The site uses an updated (for use with Hugo 0.92.0) and customized version of the hugo-resume theme with a cobalt blue color scheme. Theme customizations are in:
- `themes/hugo-resume/static/css/resume.css`
- `themes/hugo-resume/static/css/tweaks.css`

## Deployment

Build the site with:
```bash
hugo --minify
```

The built site will be in the `public/` directory, ready for deployment to your hosting service.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Based on the [hugo-resume](https://github.com/eddiewebb/hugo-resume) theme
- Modifications and customizations by [Dan Feeny]