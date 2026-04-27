# Portfolio Maker
This project serves to help students easily create online portfolios without a significant amout of coding experience. Students will be able to start with a base template of a portfolio that has already been made and can adjust it with some guided HTML and CSS changes. 

## Introduction to the Template
This Portfolio Maker Template has various features that students can utilize to make their portfolio stand out. For example, there is a navigation bar at the top which can be customized but already comes with some smooth quality of life features such as a hovering animation. 

<details>
<summary>
More Details about the Template
</summary>

### The Home Page
The home page comes with an about me section that users can use to provide a brief introduction about themselves. There is also a highlighted projects section which can display some of the user's best projects with a button that takes them to a more detailed page of their project. At the end of the home page, there is a set of buttons that the user can click in order to travel to other pages similar to the navigation bar. 
 
 ### The Skills Page
 The skills page contains a list of skills that the user can use in order to showcase the different capabilities they have. There is also an image next to each skill in order to give a mental image of what the skill is and to add to the aesthetic of the website. Each skill also reverses which gives the page a bit of a unique spin in order to make it look interesting. 

 ### The Experience Page
 The experience page is very similar to the skills page. There is a list of experiences that the user can upload in order to showcase the different places they have experience at. Similar to the skills page, there is also an image that the user can upload. However, there is not a reversing of the experiences though; the user can choose to reverse the images via modifying some of the code. 

 ### The Projects Page
 The projects page is similar to the skills page as well. There is a list of all the projects that users can edit in order to showcase the projects they have worked on or are working on. They can also upload images. This page also reverses after each project which the user can choose to remove if they wish by modifying the code. 

 ### The Contact Page
 The contact page is the last page of the portfolio. This is the page where the user can upload their personal information in order to be contacted by people reading the website. There is an email which if you click can be automatically copied (there is no popup saying that you have copied it currently), and there are buttons which are going to link to other places where they can reach out to the user. 
</details>

## Getting Started with the Template
 There are many ways you can modify this template in order to suit your needs. We will be going in detail for some of the ways you can change the colors, images, etc. This guide is going to be for people who are new and experienced with HTML and CSS so everyone can utilize and customize this portfolio template to their wishes. 

### Downloading the Template & Hosting it on GitHub
In this section, we'll talk about how to clone this repository to your computer so that you can host it on GitHub pages and be able to use it like a real website. 

#### Things to do before downloading:
1. [Download Git](https://git-scm.com/install/)
2. Open VS Code (make sure it is the latest version). 
3. Make a [GitHub account](https://github.com/) if you do not have one already. 
4. Link your VS Code to your GitHub account
    - Select the GitHub icon in the activity bar. 
    - Click **Sign In** and follow the prompt to authenticate with GitHub in the browser. 
    - If done correctly, you should be directed back to VS code. 
        - If you have any troubles, visit [VS Code's detailed guide here.](https://code.visualstudio.com/docs/sourcecontrol/github)

### Important Notice
There are 2 ways of "downloading"/modifying the actual repository. The first method is to fork the repository which will create a personal branch of the repository which you can modify but will be visible under the Forks tab in this GitHub Repository Fork's page. The other method is to download the repository and create a personal repository which will not be linked to this repository in anyway. We will show you how to do both. The Forking method is much easier but allows your code to be public on this main template repository whereas the second method allows you to keep your code to yourself without linking it to this project. 

#### Forking the Repository - The Easier Method
1. Go to the top of this repository's page and click the **Fork** button in the top right corner. 
2. Name the repository something of your choice - preferably something that allows you to identify the project easily. Give it a description if you wish to.
3. Copy the link of the newly created repository from the search bar.
4. Open VS Code, then click on the version control / GitHub logo on the activity bar and select **Clone Repository**. 
5. Paste the URL that you just copied and select a place for the local version of the repository to be stored on your computer. 


#### Getting Started with Downloading the Repository - The Private Method
1. Click the arrow next to the **green Code button**.
2. Click **download ZIP.**
3. Locate the ZIP folder and right click and extract all. 
4. Open VS Code, locate the folder, click it and then open the folder named `Portfolio-Maker-main` inside of the extracted folder in VS Code. 
5. Click on the GitHub icon in the activity bar and then click **Initiatlize Repository**.
6. You should then be brought to a screen with a list of changes that you have made that are avaliable to push. Type a message above the button that says **Commit** that says something along the lines of "intializing repository". 
7. Click on the arrow pointing downwards next to the **Commit** button and click **Commit & Push**. 
    - If there is a pop-up saying something along the lines of "There are no staged changes. Would you like to stage your changes and commit", click yes. 
8. Wait for the changes to be pushed. After that, there should be a button that says **Publish branch** which you should click in order for your repository to be created and displayed on your GitHub account.

### Creating Your Website
In order to host your portfolio online via GitHub, you have to do the following:
1. Go to the repository that you made for your portfolio (not this one), and go to settings. 
2. Click the settings tab at the top of the repository and click on the **Pages** option under the Code and Automation Section. 
3. Under the **Build and Deployment** section, click the option that says **Deploy from a branch**.
4. For the branch, choose the branch named **main** and click save. 
5. After you do this, it should be checking your repository and should generate a link at the top of the page with the portfolio. This might take a minute, so keep refreshing until you see the link. 

This portfolio webpage will be updated everytime you push changes to the repository, specifically the main branch. 

For a video tutorial on how to do this, [click here](https://youtu.be/DB_PGpJFU1A?t=220) (video links to the time when the tutorial starts showing how to host it without a custom domain, you can watch the full tutorial if you want to learn how to host it on a personal custom domain).

 ### Modifying Images
 
 Changing images is going to be nearly the same for all of the pages. Here is how you can do it:
 1. Download the image that you want to use and locate it in your file explorer. Make sure there is a easily spelled name. 
 2. Move the file of the image under the images folder in order to be able to use it in the code. 
 3. Go the **HTML** file of which page you want to place the image in. We will be taking one of the image under the experience page as an example. 
 4. Locate this code segment `<img src="/images/experiencetemplateimage.jpg" alt="ExperienceTemplateImage">` within that file - there will be multiple instances and you will have to change each one individually. 
 5. This segment above is a image tag that you have to use in order to insert images onto an HTML page.
    - Essentially, you will have to replace the name of the file (in this case it's `experiencetemplateimage.jpg`) with the name of the new file that you have uploaded to the folder.
    - The phrase `alt="ExperienceTemplateImage"` is what the image will be called if it not able to load, this text is what the user will see instead of the image.

<br>
<details>
<summary>How Images Work in HTML</summary>

### Images in HTML

To insert an image in HTML, you will have to use the `<img>` tag. Technically speaking, images are not really inserted into the page, but rather linked to the web page. The `<img>` tag basically creates a space for that image. 

### `<img>` Tag
This tag is pretty simple to use. There are only 2 attributes that are required in order to get the image onto the page. 
* `src` - this the path (think of src as the location of the item on your computer) of the image
* `alt` - this is the alternate text for the image - useful if the image cannot load and then displays this text to the user. 

There are other fancy little tricks that you are able to with images in HTML with other optional attributes. To learn more about images in HTML, go to the [W3chools page on images in HTML](https://www.w3schools.com/html/html_images.asp). 

</details>

### Modifying the Color Scheme
Modifying the color scheme is a rather simple task to do. You generally just have to change CSS files in order to change it as this template relies completely on CSS files for its styling. Anytime you see a tag named `color`, `background`, `background-color`, or `border-bottom`, you can be assured that these tags are being used in order to set the color of something in the webpage. 

Just change the hex color code associated with each thing and see how it changes the website. Keep playing around with different combinations, colors, etc. to find something that you really like in order to make this portfolio yours. 