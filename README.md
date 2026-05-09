<h1>Introduction</h1>
<p>This repository stores the student project archive for the Game Programming department at SUNY Morrisville. The repository is broken into two branches:</p>
<ol>
  <li>The Main Branch</li>
  <li>The Development Branch</li>
</ol>

<h1>The Main Branch</h1>
<p>
  <strong>DO NOT PUSH ANY CHANGES TO THE MAIN BRANCH UNTIL IT'S READY TO BE SEEN!!!</strong>

  The main branch is the branch that is visible to the public. All URLs on the web page are directly connected to this web page (URLs use absolute pathing). Changes you make to the repository will not be publicly visible until they are pulled onto the main branch.
</p>

<h1>The Development Branch</h1>
<p>
  The development branch is where you can workd on making changes to the website. If you fork this repository, you can craete a pull request to the development branch. This is to ensure that you can double-check for merge conflicts before sending your changes to main.
</p>
<strong>*Note:</strong> Always merge the main branch onto the development branch before creating the pull request. This'll alleviate any merge conflicts before being sent to the main.

<h1>Website Structure</h1>
<p>
  The website is currently broken into two sections: the home (landing) page, and the prokect page. The home page is what users will first see when clicking onto the website. Currenlty, it showcases some of the best work student have done in Morrisville's game program.

  The project page is the archive itself. It lists all the student projects (that could be added) that have been completed in each course. Projects are sectioned based on the course it was completed in, and then by their project type (i.e., final project, midterm, etc). I recommend collapsing all elements in the file when viewing. There are comments to help navigate the file.

  The deliverables for each project is broken into a semester folder hierarchy. For example, the projects created in CITA 113 for the Fall 2024 semester are under the "Projects/F24-113/" folder. You can find each deliverable for each project from there.

  The deliverables for each project vary. Some have playable games, GitHub repos, and reports. Others have videos, presentations, and blender files. You can find the full list of deliverables for each project in the deliverables section. Each deliverable is stored in an anchor element. Be sure to update the deliverable's href link to where it is, either in this project or on the web.
</p>

<h1>The Styling</h1>
<p>
  You can find the styles for the project archive in the CSS folder. There is one file (styles.css) that acts as a monolithic CSS file. Every style on the project archive can be found there.
</p>

<h1>Known Issues</h1>
<p>
  Right now, there are some problems with elements scaling with the page. Most notably, the header will scale incorrectly with the height of the page. This is most notable when shrinking the size of the window to something really small. This shouldn't be noticeable for common page usage, but it can be encountered

  There is also a problem with the border-radius property on many div containters. You can see this most obviously with the buttons on the project page. The corners are not rounding off neatly when it curves downward/upward. It is kind of cut off. For comparison, the project highlights on the home page are applying the border-radius property correctly.
</p>
