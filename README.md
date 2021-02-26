# Project 2 Pitches!!!
You must turn in a pitch that outlines what you'll build for your project 2. 

## You should already...
- Know who your pod leader is for P2
- Have "soft pitched" your idea to your pod leader for feedback
- Have gotten approval on one of your soft pitched ideas

## Your pitch must include:
* **A Project Repo**
  - Make a brand new repo in your personal github. Clone it to your machine.
  - Make a `README.md` (see below for what it should contain)
* **A `readme.md`**
  - The file extension `.md` stands for markdown. Markdown is a set of syntaxes that let you do very basic styling on your file (less sophisticated than html + css). You can find a guide to how to use markdown syntax here: https://guides.github.com/features/mastering-markdown/
  - In VScode, you can preview how your markdown will look, which is very handy: https://code.visualstudio.com/docs/languages/markdown
  - Your pitch readme should have the following:
    - a Description of the app
    - mvp goals
    - stretch goals
    - user stories 
    - explanation of the APIs you plan to use 
    - daily sprints
    - wireframes
    - database ERDs
    - a RESTful routing chart for your app
* **Daily Sprints** 
  * Plan out your daily goals in advance so you can keep on track with MVP!

    *Exapmle of Daily Sprints*
    - Monday:
      * test API
      * wireframe app
      * plan database ERD
      * plan routes
    - Tuesday:
      * create db models -- test db
      * stub routes -- test routes
      * build routes
    - Wednesday:
      * finish routes
      * create views
    - Thursday:
      * finish views
      * mvp
    - Friday:
      * debug refactor
      * style views
    - Saturday:
      * style views
      * stretch goals
    - Sunday:
      * stretch goals
* **Wireframes**
  - Use a tool like https://awwapp.com/, https://www.mockflow.com/, or good ol zoom whiteboard to create wireframes for your project. Whatever you use, get a screen cap.
  - Your wireframes should walk the reader through the screen states, and should include short descriptions of each screen. It's a good idea to give your wireframes labels (like 1, 2, 3 etc), and to indicate which screens transitions to which other screens.
  - Move your image files into the project folder and link them in your README. (You might want to put all your wireframe images into a single folder called images or assets. In that case you'll have to specify the filepath to those images including the containing folder.) Pro tip: use VScode's markdown previewer!
* **ERDs**
  - you can use [dbdesigner.net](https://app.dbdesigner.net/) or a similar tool plan your database schema. Screengrabs are the quickest way to get your ERDs into your readme!
* **RESTful routing chart** 
  * Can be a table in your readme.md or another spreadsheet. Plan out your routes that go along with the views you wireframed. 
  * _include all the routes your app will need!_

*Example for a simple books app:*

| Method | URL | Functionality | view |
|--------|-----|---------------|------|
| GET  | /books | list all books | show books/index.ejs
| POST | /books | add a book | redirect to /books/:id
| GET  | /books/:id | show one book |  show books/detail.ejs
| PUT  | /books/:id | update one book | redirect to /books/:id
| DELETE | /books/:id | delete one book | redirect to /books




## Turning in your pitch
Commit your `README.md` with these components completed, and push to your project repo. Link your project repo in the google classroom assignment for the P2 Pitch.