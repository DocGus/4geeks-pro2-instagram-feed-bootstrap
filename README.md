Instagram Photo Feed with Bootstrap

This project consists of creating an Instagram Photo Feed using HTML5, Bootstrap, and JavaScript, based on the HTML Hello template provided by 4Geeks Academy.

The goal was to reproduce the main structure and functionality of an Instagram feed using Bootstrap components.

📦 Template Used

The project started from the HTML Hello template provided by 4Geeks Academy.

This template provides a basic structure for starting a web project from scratch and allows working with HTML, CSS files, and a local server using Flask.

Using this foundation, we developed our own project by adding the visual structure and functionality needed to create the Instagram Photo Feed.

🛠️ Technologies Used
HTML5 — page structure and content.
Bootstrap 5.3.8 — layout, grid, components, and utility classes.
Bootstrap Icons — icons used throughout the interface.
JavaScript — interaction for switching between feed views.
Flask — local server used to run the project.
Git — version control.
GitHub — repository storage and synchronization.
📱 Implemented Components
Navbar

A navigation bar was created using Bootstrap components and classes.

It includes:

Instagram icon.
Project name.
Create a new post button.
Settings dropdown menu.
Photo Grid

A grid view was created using the Bootstrap Grid system.

The photos are organized using:

3 images per row.
Columns using .col-4.
Spacing using .g-2.
Square images using .ratio.ratio-1x1.
Responsive images using .img-fluid.
Image cropping using .object-fit-cover.
Individual Post View

A second view was created where each post appears individually as a card.

Each post contains:

Title.
Date.
Image.
Number of likes.
Description.

The following Bootstrap classes were used to organize this view:

.card
.row
.col-12
.col-md-8
.col-lg-6

This allows the content to have different widths depending on the screen size.

View Switching

Two buttons were implemented to switch between:

Grid View
Individual Post View

JavaScript controls the visibility of each section using the Bootstrap class:

d-none

When a view is selected, JavaScript adds or removes this class to show or hide the corresponding content.

Create New Post Modal

A Bootstrap Modal was implemented to simulate creating a new post.

It includes:

Caption text field.
Camera icon.
Location icon.
Close button.
Publish button.

The Publish button is only part of the visual interface because this exercise does not require storing information in a database or implementing a backend for posts.

Dropdown

A dropdown menu was implemented using the Bootstrap Dropdown component.

It includes:

Profile
Accessibility
Privacy and Data
Log out

A divider was also used to separate the menu options.

🎨 Bootstrap Icons

Bootstrap Icons were used to add icons to the interface.

These include:

Instagram
Settings
Camera
Location

Icons are incorporated using classes such as:

<i class="bi bi-instagram"></i>
📚 What We Learned

During this project, we mainly worked with the following concepts:

HTML
Basic structure of an HTML5 document.
Semantic elements.
Use of attributes.
External resource links.
Content organization using HTML elements.
Bootstrap

We learned how to use:

Grid system.
Rows and columns.
Responsive Design.
Containers.
Cards.
Navbar.
Dropdown.
Modal.
Utility classes.
Spacing.
Display.
Ratios for maintaining proportions.
Reusable components.

We also learned that Bootstrap allows us to build interfaces using predefined classes without having to create all the CSS from scratch.

JavaScript

We learned basic DOM interaction concepts:

getElementById()
addEventListener()
classList.add()
classList.remove()

These methods allow us to select HTML elements, detect events, and modify element classes to dynamically change the interface.

Local Development Environment

We worked on the project locally using:

Ubuntu.
Visual Studio Code.
Python.
Flask.
Python virtual environment venv.

Flask was used to run a local server and view the project in the browser.

Git and GitHub

We worked with the basic version control workflow:

Modify files
      ↓
Save changes
      ↓
git status
      ↓
git add
      ↓
git commit
      ↓
git push
      ↓
GitHub

We also worked with:

Local repository.
Remote repository.
origin.
Commits.
Git and GitHub synchronization.
.gitignore.

The venv/ directory is excluded through .gitignore because it belongs to the local Python environment and should not be part of the repository.

▶️ Run the Project Locally

Activate the virtual environment:

source venv/bin/activate

Install Flask if necessary:

pip install flask

Run the server:

python3 server.py

Then open:

http://127.0.0.1:3000
📁 Main Project Structure
4geeks-pro2-instagram-feed-bootstrap/
├── index.html
├── server.py
├── .gitignore
├── README.es.md
├── README.md
├── README.cn.md
├── learn.json
└── .vscode/

The venv/ directory exists in the local environment but is excluded from the repository through .gitignore.

🎯 Final Result

The project reproduces the main visual features of the Instagram Photo Feed with Bootstrap exercise:

Navbar.
Dropdown menu.
Grid View.
Individual Post View.
View switching.
Create New Post Modal.
Icons.
Responsive Design.
Rock climbing-related photographs.

The project was developed from the initial template and then built and documented step by step to understand not only the final result, but also the tools and concepts used throughout the process.

🔗 Repository

GitHub:

https://github.com/DocGus/4geeks-pro2-instagram-feed-bootstrap

🙏 Project Based on 4Geeks Academy

This exercise is part of the web development learning process at 4Geeks Academy and uses their initial HTML Hello template as its starting point.