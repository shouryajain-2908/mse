Shourya Jain | Portfolio

A modern, responsive personal portfolio website built with pure HTML and CSS. It features a dark theme, a gradient-accented hero section, animated background particles, and smooth-scrolling navigation.


Features
Dark, modern UI with a blue, purple and cyan gradient palette
Animated particle background in the hero section (pure CSS, no JavaScript)
Sticky navigation bar with smooth-scroll links to every section
Fully responsive layout for desktop, tablet and mobile
Hover effects on buttons and navigation links
Lightweight: a single HTML file with no frameworks or build step
Google Fonts: uses the Poppins typeface
Sections
Section	Description
Hero	Introduction, tagline and call-to-action buttons
About	A short bio
Skills	HTML, CSS, JavaScript, C++, Problem Solving
Experience	Learning and building new projects
Projects	Coming soon
Education	Coming soon
Contact	Get in touch
Tech Stack
HTML5 for structure
CSS3 for styling, gradients, keyframe animations and media queries
Google Fonts (Poppins) for typography
Project Structure
.
├── index.html      # Portfolio page (HTML + embedded CSS)
└── README.md

If your file is currently named mse.html, rename it to index.html so GitHub Pages serves it automatically.

Getting Started
Run locally
Clone the repository
bash
git clone https://github.com/<your-username>/<your-repo-name>.git
Open the project folder
bash
cd <your-repo-name>
Open index.html in your browser by double-clicking it, or serve it locally:
bash
# Python 3
python -m http.server 8000

Then visit http://localhost:8000.

Deploy with GitHub Pages
Push the project to a GitHub repository.
Go to Settings → Pages.
Under Source, select the main branch and the / (root) folder.
Click Save. Your site will be live at https://<your-username>.github.io/<your-repo-name>/ within a minute or two.
Customization
Colors: the accent colors (
#168cff, 
#963cff, 
#00c9d9) are used in the .gradient, .logo span and button styles. Search and replace them to change the theme.
Content: edit the text inside each <section> to update your bio, skills, experience, projects and education.
Particles: adjust background-size and the move keyframes in .particles to change density and speed.
Resume button: the nav "Resume" link currently points to #contact. Replace its href with a link to your resume PDF.
Roadmap
[ ] Add real projects with descriptions, tech tags and links
[ ] Add education and experience timelines
[ ] Link a downloadable resume
[ ] Add a contact form or social media links (GitHub, LinkedIn, email)
[ ] Add a skills section with icons or progress indicators
[ ] Add scroll animations and a mobile hamburger menu
