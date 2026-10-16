# MayankFitness

A responsive, single-page website for a fictional fitness center. The page introduces the gym, presents membership plans and training programs, and helps prospective members explore trainers, testimonials, FAQs, and contact information.

## Features

- Responsive navigation with links to sections throughout the page
- Hero section with membership offer countdown
- Basic, Premium, and Elite membership plan cards
- Gym benefits, trainer profiles, and fitness programs
- Member transformations and testimonials
- FAQ accordion and contact section
- Newsletter and contact form interfaces

## Built With

- HTML5
- CSS3
- JavaScript
- [Bootstrap 5.3](https://getbootstrap.com/) for layout and interactive components
- [Font Awesome](https://fontawesome.com/) for icons
- Google Fonts for typography

Bootstrap, Font Awesome, and Google Fonts are loaded from external CDNs, so an internet connection is required for those resources.

## Getting Started

This is a static website and does not require a package manager, build step, or backend.

1. Clone the repository:

   ```bash
   git clone https://github.com/chhavicreations/Gym-website-.git
   ```

2. Open the project folder:

   ```bash
   cd Gym-website-
   ```

3. Start a local web server. For example, with Python:

   ```bash
   python -m http.server 8000
   ```

   On Windows, you can use `py -m http.server 8000` if `python` is not available as a command.

4. Visit [http://localhost:8000](http://localhost:8000) in your browser.

You can also open the folder in Visual Studio Code and use the Live Server extension.

## Project Structure

```text
.
├── index.html             # Main landing page
├── timer.js               # Membership offer countdown
├── CSS/
│   ├── style.css          # Main site styles
│   ├── utils.css          # Utility styles
│   └── responsive.css     # Responsive layout styles
└── IMAGES/                # Logo, gym, trainer, and program images
```

## Customization

- Edit the page content and section structure in `index.html`.
- Update colors, component styles, and responsive behavior in the CSS files under `CSS/`.
- Update the offer countdown date in `timer.js`.
- Replace or add images in `IMAGES/` and update their references in `index.html`.

## Notes

- The contact and newsletter forms are front-end interfaces only; they are not connected to a submission service or backend.
- Gym address, contact details, membership prices, testimonials, and member statistics are sample website content. Update them before using the site for a real business.
