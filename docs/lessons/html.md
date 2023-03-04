# HTML

---

**Course Objective:**

The objective of this lesson is to provide you with the basic structure of html, how to add tags and get more documentation to create a page.

## What is HTML?

HTML stands for Hyper Text Markup Language. HTML is the standard markup language for creating Web pages. HTML describes the structure of a Web page. HTML consists of a series of elements. HTML elements tell the browser how to display the content.

Use [MDN DOCS](https://developer.mozilla.org/en-US/docs/Web/HTML) to see what tags are available when creating html.

## Structure

![HTML](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20220401160946/HTML-Basic-Format.png ":size=50%")

## Tags

![HTML Tags](https://assets.digitalocean.com/django_gunicorn_nginx_2004/articles/new_learners/html-element-diagram.png)

## Linking To A Stylesheet

                <head>
                    <link rel="stylesheet" href="./main.css">
                </head>

## Adding Image

                <body>
                    <img src="https://www.oxfordwebstudio.com/user/pages/06.da-li-znate/sta-je-html/sta-je-html.jpg">
                </body>

## Practice | Solo

1. Open up your text editor!
2. Create a new folder with a file inside called index.html
3. Use the structure image above and type everything out on your file index.html
4. Add a image to your project.Use [MDN DOCS](https://developer.mozilla.org/en-US/docs/Web/HTML) if you need addition resources.
5. Add your name as the title of your project.
6. Use the command line to push your project to github.

## Practice | Group

### Pt1

> Split up into a group of 3 or 4. You will be tasked to create a project which you will all share. This project will some starter code and use your knowledge of tags to edit and create your own section to the page.

- One person will start the project, they will create a folder (name it team-portfolio) with a blank html file inside that folder.
- Add this to your html file. [Code](https://gist.github.com/3salaz/a28482420f3fc3f3b8b596c5bd6bf40d)
- That same person will `git add index.html` and `git commit -m "initial commit"` then wait until your teammate create a repository on github.
- One person from the group will create the repository on github and add your team as collaborators.
- Share the code from using the section displayed below with the first student that created the index.html file. Use the commands below to push the folder to github.
  ![Pushing From Command](../../assets/images/push-existing-command-line.png)

- At this point you should have a hmtl file on github that your teammates can clone down.

### Pt2

- All remaining members of the group, will clone down the repository to their computers using the `git clone` command
  ![Clone Repo](../../assets/images/clone-repo.png)
  ex. `git clone https://github.com/3salaz/gh-portfolio.git`
- Everyone should now have a html file to start with
- Create your own branch for all of your changes. `git checkout -b your-branch-name`
> ex. `git checkout -b Erik`
- You will now be in your own branch so you don't effect any changes to your teammates.

- Go to the section with a id of Erik, change out my content for yours. Add images or links to your social profiles. When you complete your section push changes to github and help your partners. (Make sure you are using `git push origin your-branch-name` this will ensure that you are sending your code to your branch and not the main one)
- When everyone is pushed to github. We will merge all the changes and pull down all the new content to make sure you all have each others section
- Publish the page with github.
