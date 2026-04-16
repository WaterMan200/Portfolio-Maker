# Portfolio Maker
This project serves to help students easily create online portfolios without a significant amout of coding experience. Students will be able to start with a base template of a portfolio that has already been made and can adjust it with some guided HTML and CSS changes. 

## Introduction to the Template
This Portfolio Maker Template has various features that students can utilize to make their portfolio stand out. For example, there is a navigation bar at the top which can be customized but already comes with some smooth quality of life features such as a hovering animation. 

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

## Getting Started with the Template
 There are many ways you can modify this template in order to suit your needs. We will be going in detail for some of the ways you can change the colors, images, etc. This guide is going to be for people who are new and experienced with HTML and CSS so everyone can utilize and customize this portfolio template to their wishes. 

### Downloading the Template & Hosting it on GitHub
In this section, we'll talk about how to clone this repository to your computer so that you can host it on GitHub pages and be able to use it like a real website. 

#### Things to do before downloading:
1. [Download Git](https://git-scm.com/install/)
2. Open VS Code (make sure it is the latest version). 
3. Make a [GitHub account](https://github.com/) if you do not have one already. 

#### Getting Started with Downloading the Repository 



 ### Images
 
 Changing images is going to be nearly the same for all of the pages. Here is how you can do it:
 1. Download the image that you want to use and locate it in your file explorer. Make sure there is a easily spelled name. 
 2. Move the file of the image under the images folder in order to be able to use it in the code. 
 3. Go the **HTML** file of which page you want to place the image in. We will be taking one of the image under the experience page as an example. 
 4. Locate this code segment `<img src="/images/experiencetemplateimage.jpg" alt="ExperienceTemplateImage">` within that file - there will be multiple instances and you will have to change each one individually. 
 5. This segment above is a image tag that you have to use in order to insert images onto an HTML page. 

<br>
 <details>
<summary>How Images Work in HTML</summary>

### Images in HTML

To insert an image in HTML, you will have to use the `<img>` tag. Technically speaking, images are not really inserted into the page, but rather linked to the web page. The `<img>` tag basically creates a space for that image. 

### `<img>` Tag
This tag is pretty simple to use. There are only 2 attributes that are required in order to get the image onto the page. 
* `src` - this the path (think of src as the location of the item on your computer) of the image
* `alt` - this is the alternate text for the image - useful if the image cannot load and then displays this text to the user. 

There are other fancy little tricks that you are able to do as well. To learn more about images in HTML, go to the [W3chools page on images in HTML](https://www.w3schools.com/html/html_images.asp). 

</details>