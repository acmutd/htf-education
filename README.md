## Preview

![Preview](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/preview.png)

**[View Live Preview](https://mustafa-sadriwala.github.io/acm-swe-workshop/)**

## Download and Installation

To begin using this template, choose one of the following options to get started:
* Clone the repo: `git clone https://github.com/Mustafa-Sadriwala/acm-swe-workshop.git`
* [Fork, Clone, or Download on GitHub](https://github.com/Mustafa-Sadriwala/acm-swe-workshop)

## Hosting

If you want to fork the repo:
1. Press the fork button in the top-right and choose the account you want to fork it to.
2. There will now be an identical repo in your account.
3. Open the repository and go to the **Settings** tab.
4. Rename the repository to your liking.
5. Scroll down to the GitHub Pages section in the **Settings** and you will find a link to your website!

If you want to clone the repo:
1. Clone the GitHub repo to your local machine.
2. Create a new GitHub repo on your account.
3. From the cloned local repo push to your new repo on GitHub using the following commands (replacing YOU/YOUR_NEW_REPO with the appropriate values, this URL can be found on the new repo):
```
$ git remote set-url origin http://github.com/YOU/YOUR_NEW_REPO
$ git push remote origin
```
3. Go to the repository on GitHub.
4. Go to the **Settings** Tab.
5. Scroll to the GitHub Pages sections and choose your source branch (most likely this will be the *master* branch)
6. The page will refresh and there will now be a link above the GitHub pages section to your website!

> Note: the website will not be instantly accesible and will likely show a 404 error for a few minutes


## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files included with the template in a code editor to make changes. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Walkthrough

Follow the steps to [Download and Install](#download-and-installation) this repository found above.
Open the repository on your local machine with your favorite text editor.

#### Changing Text

First we'll want to take a look at `index.html`.

On *lines 9-13* change the `meta` and `title` tags to correspond with your information.
![lines-9-13](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/9-13.png)

On *line 32* change **Temoc** to your own name. This will change the name in the navigation bar.
![lines-31-32](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/31-32.png)

On *lines 73-95* let's take a look at the masthead heading. This area is going to be right below the Temoc avatar.
Replace ***Temoc's Page*** with your full name or a heading you would prefer. Change the description in the `p` tag to match you graduation year and major.
![lines-73-95](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/73-95.png)

On *lines 116-125* we'll change the About Section. Here there are going to be two columns side by side. You may have to play around a little to make sure you have the right amount of text on both sides. We recommend writing something about your interests, career objectives, and maybe even hobbies.
![lines-116-125](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/116-125.png)

On *lines 359-397* you can find the information for the first portfolio modal. These are the modals that pop up when you click on one of the projects in the portfolio section. Change the title, **Log Cabin** to a relevant project name and change all the latin words in the `p` tag to a description of the project and what you worked on.
![portfolio-modal-1](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/portfolio-modal-1.png)

#### Adding files and images

Now let's talk about adding in some files and images that are more pertinent to you.

First you'll need to find a couple of images for your website. You'll want a picture of yourself, a professional headshot or just something you think you look good in for your avatar. And a generic picture to use for your first project in your portfolio.
<pre>
<b>./acm-swe-workshop</b>
├── LICENSE
├── README.md
├── Temocs\ Resume.pdf
├── css/
├── gulpfile.js
├──<b>img/</b>
    ├── avataaars.svg
    ├── github
    └── <b>portfolio</b>
        ├── cabin.png
        ├── cake.png
        ├── circus.png
        ├── game.png
        ├── safe.png
        └── submarine.png
├── index.html
├── js/
├── mail/
├── node_modules/
├── package-lock.json
├── package.json
├── scss/
├── temoc-primary.png
└── vendor/
</pre>
Put the picture of yourself in the `img` directory and put your project picture in the `img/portfolio/` directory.

Place a recent copy of your resume in the main directory (`acm-swe-workshop/`). Make sure you use a .pdf file for your resume.

>Note: you can delete the images in the `img/github/` directory

Let's start back from the top.

On *line 71* you'll find the `img` tag that controls the main avatar image at the top of the page. You'll want to replace the 
`src` attribute to the relative file path of your profile picture. The relative file path - if you followed the steps above - should be `img/<picture_file>`. You can also go ahead and put a short description of your image (maybe your name) for the `alt` attribute.
![lines-69-71](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/69-71.png)

On *lines 90-95* is the code for the resume button. Here you'll want to go to the `a` tag and edit the `href` attribute. The `href` attribute is actually mainly used for links but can also be satisfied with file paths. In the `href` attribute put the relative file path to your resume which should be just the name of the file (i.e. `resume.pdf`) if you placed it in the main directory.
![lines-90-95](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/90-95.png)


On *lines 161-171* you'll find portfolio item 1. Here you'll want to edit the `src` attribute of the `img` tag. You should put in the relative file path to your file, which should be `img/portfolio/<image_file>`.
![portfolio-item-1](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/portfolio-item-1.png)
Also make this change in the portfolio modal for item 1 of which we altered the text for above. You will need to update the `img` tag of portfolio modal 1 found on *lines 359-397*.

#### Adding Links

Now we are going to add links to your professional social medias.

On *lines 48-59* you'll find the code for the LinkedIn and GitHub icons on the navigation bar. Go ahead and put a link to your GitHub in the first `a` tag on *line 50* in the `href` attribute. Put a link to your LinkedIn in the second `a` tag on *line 56* also in the `href` attribute.  
![lines-48-59](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/48-59.png)

You can repeat the same process as above on *lines 127-137* to change the buttons in the about section.
![lines-127-137](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/127-137.png)

#### Getting Mail

Finally, let's update what email people should contact you at. 

Go to the `mail` directory and open the file named `contact-me.php`. In here you can see the back-end code for sending an email. This email can be redirected to your personal/school email simply replace the email address for the `$to` variable. You can also customize the message/sender/subject line that you will receive when someone uses your website.
![contact-me.php](https://github.com/Mustafa-Sadriwala/acm-swe-workshop/blob/master/img/github/contact-me.php.png)

>Note: Be aware that this constitutes putting your email on the internet. You probably already have it available on other social media platforms but if you are not comfortable with the idea of putting your personal/school email out there then we recommend deleting the contact section.

#### An Exercise

With what you've learned so far, scroll to *lines 300-337* to find the Footer section code. Now try to customize the Footer section with your own info or maybe even add something new to it altogether.

### Advanced Usage

After installation, run `npm install` and then run `npm start` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment. This will allow you to make change to the SCSS files and have them auto-update your the CSS files as well. SCSS offers the option of neater and more efficient styles.

#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp watch` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory

>You must have npm and Gulp installed globally in order to use these features. Installation guides can be found at:
> * https://www.npmjs.com/get-npm
> * https://gulpjs.com/docs/en/getting-started/quick-start

## Source Details

### [Start Bootstrap - Freelancer](https://startbootstrap.com/template-overviews/freelancer/)

[Freelancer](http://startbootstrap.com/template-overviews/freelancer/) is a one page freelancer portfolio theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). This theme features several content sections, a responsive portfolio grid, window modals for each portfolio item, and a working PHP contact form.

# Copyright and License

Copyright 2013-2019 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-freelancer/blob/gh-pages/LICENSE) license.
