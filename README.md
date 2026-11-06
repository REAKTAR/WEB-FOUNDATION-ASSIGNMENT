Web Foundation Assignment
A collection of 45 hands-on assignments covering the foundations of front-end web development: HTML, CSS, Flexbox, CSS Grid and responsive design. Each assignment is a single, self-contained file you can open straight in a browser.
Author: Utkarsh Programme: BCA (Artificial Intelligence), Invertis University, 2025-28 Live pages: https://REAKTAR.github.io/web-foundation-assignment/

What's inside
#	Topic	What it covers	Files
1-5	Fundamentals	How a URL becomes a page, tool setup, terminal navigation, Git commits, GitHub link	01-url-to-page.md to 05-github-link.md
6-10	HTML basics	Headings, text-only and semantic resumes, debugging broken HTML, a personal introduction	06-basic-page.html to 10-personal-introduction.html
11-15	Links, images and structure	Navigation and anchors, accessible images, lists, semantic tags, blog and portfolio	11-portfolio-navigation.html to 15-personal-blog-portfolio.html
16-20	Forms, tables and metadata	Registration and job application forms, a size-chart table, a meta-tag audit, a multipage site	16-student-registration-form.html to 20-multipage-project.html
21-25	CSS fundamentals	Styling, selector types, fonts and colours, design tokens with CSS variables	21-lightly-styled-page.html to 25-styled-multipage-project.html
26-30	Box model and positioning	Annotated box model, card variants, fixing overflow, position and z-index, profile and product cards	26-box-model-annotated.html to 30-profile-product-card.html
31-35	Flexbox	Menu bar, centred login, wrapping product cards, navbar with hero, landing section	31-flex-menu-bar.html to 35-flexbox-landing-section.html
36-40	CSS Grid	Photo gallery, auto-fit products, dashboard with named areas, header and sidebar layout, portfolio	36-grid-photo-gallery.html to 40-grid-project-portfolio.html
41-45	Responsive design	Breakpoints, a responsive audit and fix, a Grid and Flexbox landing page, and the final responsive landing page	41-breakpoints-multi-screen.html to 45-landing-responsive-final.html
Repository structure
web-foundation-assignment/
├── README.md
├── 01-url-to-page.md ... 05-github-link.md      # written answers and proof
├── 06-basic-page.html ... 45-landing-responsive-final.html
└── screenshots/                                  # setup proof and other images

	• Assignments 1-5 are Markdown files with written answers and commands.
	• Assignments 6-45 are plain HTML files. The CSS lives inside a <style> block in each file, so there is nothing to install or build.
How to view the assignments
Option 1: open locally
	1. Clone the repository: 
git clone https://github.com/REAKTAR/web-foundation-assignment.gitcd web-foundation-assignment
	2. Double-click any .html file, or right-click it in VS Code and choose Open with Live Server.
Option 2: view online Open the live pages at the GitHub Pages link above and add the file name to the end, for example .../45-landing-responsive-final.html.
Skills practised
	• Semantic HTML5 and accessible markup (alt text, labels, landmarks)
	• Forms, tables and metadata (SEO and Open Graph tags)
	• CSS selectors, specificity, colour and typography
	• Design tokens with CSS custom properties
	• The box model, position, z-index and overflow handling
	• Flexbox and CSS Grid layouts
	• Mobile-first responsive design with media queries
	• Git and GitHub workflow with meaningful commit messages
Commit history
The repository was built in stages, one commit per group of assignments, using conventional prefixes (docs:, feat:, style:):
Commit	Message
1	docs: add README
2	docs: setup & git assignments (1-5)
3	feat: HTML basics (6-10)
4	feat: links, images, lists (11-15)
5	feat: forms, tables, metadata (16-20)
6	style: CSS fundamentals (21-25)
7	style: box model & positioning (26-30)
8	feat: flexbox layouts (31-35)
9	feat: grid layouts (36-40)
10	feat: responsive landing page (41-45)
Tools used
	• Visual Studio Code with the Live Server extension
	• Git and GitHub
	• Node.js (installed as part of the course setup)
Contact
Questions or feedback? Open an issue on this repository or reach out through my GitHub profile: @<REAKTAR>.
