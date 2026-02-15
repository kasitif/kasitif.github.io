# kasitif.github.io

My professional CV and portfolio site, built with Jekyll and hosted on GitHub Pages.

## About This Site

This is a personal CV website for Felix Kasiti Isundwa, showcasing my research, publications, professional experience, consultancy work, and projects in remote sensing and hydrology.

**Live Site:** [kasitif.github.io](https://kasitif.github.io)

## Site Structure

```
kasitif.github.io/
├── _config.yml              # Jekyll configuration
├── index.md                 # Bio page (home)
├── cv.md                    # Full CV
├── publications.md          # Research publications
├── consultancy.md           # Consultancy projects
├── projects.md              # Research & development projects
├── _layouts/                # Custom layouts
│   └── default.html         # Default page layout
├── assets/                  # Static files
│   ├── css/
│   │   └── style.css
│   ├── pdf/
│   │   └── cv.pdf           # Downloadable CV
│   └── images/
│       ├── profile.jpg      # Your photo
│       ├── consultancy/     # Consultancy images
│       └── projects/        # Project images
├── Gemfile                  # Ruby dependencies
├── .gitignore              # Git exclusions
├── README.md               # This file
├── SETUP_INSTRUCTIONS.md   # Deployment guide
└── IMAGE_GUIDE.md          # Image upload guide
```

## Pages Overview

- **Bio** (/) - Professional introduction and academic journey
- **CV** (/cv/) - Full curriculum vitae with experience and skills
- **Publications** (/publications/) - Research papers and conference proceedings
- **Consultancy** (/consultancy/) - Advisory work and consulting projects
- **Projects** (/projects/) - Research projects and operational systems

## Building Locally

To preview the site locally:

1. Install Jekyll and Bundler:
   ```bash
   gem install jekyll bundler
   ```

2. Clone the repository:
   ```bash
   git clone https://github.com/kasitif/kasitif.github.io.git
   cd kasitif.github.io
   ```

3. Install dependencies:
   ```bash
   bundle install
   ```

4. Serve the site:
   ```bash
   bundle exec jekyll serve
   ```

5. View at `http://localhost:4000`

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

## Technologies

- **Jekyll** - Static site generator
- **GitHub Pages** - Hosting
- **Markdown** - Content formatting
- **Liquid** - Templating

## License

© 2025 Felix Kasiti Isundwa. All rights reserved.

## Contact

- Email: [kasitif@gmail.com](mailto:kasitif@gmail.com)
- LinkedIn: [linkedin.com/in/kasitif](https://www.linkedin.com/in/kasitif)
- Academic Email: [f.k.isundwa@stir.ac.uk](mailto:f.k.isundwa@stir.ac.uk)
