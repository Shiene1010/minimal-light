# Shiene1010 Portfolio - Minimal Light

[![LICENSE](https://img.shields.io/github/license/shiene1010/minimal-light?style=flat-square&logo=creative-commons&color=EF9421)](https://github.com/shiene1010/minimal-light/blob/main/LICENSE)

\[[Live Demo](https://shiene1010.github.io/minimal-light/)\] | \[[한국어 버전](README_ko.md)\]

This is my personal portfolio website, forked and customized from the [Minimal Light](https://github.com/yaoyao-liu/minimal-light) theme. It is built using Jekyll and hosted via GitHub Pages.

## Features

- **Personalized for iOS Developer**: Focused on iOS/SwiftUI development projects.
- **Dynamic Feedback**: Integrated **Giscus** (GitHub Discussions) for visitor feedback and testimonials.
- **Clean History**: Git history has been reset to keep the repository lightweight.
- **Mobile Friendly**: Fully responsive design.
- **Dark Mode Support**: Seamless transition between light and dark themes.

## Project Structure

```
.
├── _data                    
│   ├── publications.yml      # Project data (Title, description, image link)
│   └── reviews.yml           # (Optional) Static review data
├── _includes                    
│   ├── giscus.html           # Giscus feedback widget configuration
│   └── publications.md       # Publications/Projects layout include
├── _sass                     # Styling files (SCSS)
├── assets                    # Images (Profile, Screenshots)
├── index.md                  # Main landing page content
└── _config.yml               # Site-wide configuration and metadata
```

## Setup & Customization

1.  **Profiles**: Edit `_config.yml` for your name, bio, and social links.
2.  **Content**: Modify `index.md` for your "About Me" and "News" sections.
3.  **Projects**: Add your projects to `_data/publications.yml`.
4.  **Feedback**: Install the [giscus app](https://github.com/apps/giscus) to enable the comments section.

## License

This project is licensed under the [Creative Commons Zero v1.0 Universal](LICENSE) License.
