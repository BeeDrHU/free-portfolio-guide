# Build a Free Website with Github Pages

If you want the official documentation from github [click here](https://docs.github.com/en/pages/getting-started-with-github-pages)

##Table of Contents
[1. Project Guidelines](## Project Guidelines)
[2. Get Started](## Start a New Repository)
[3. Deploy Your Site](## Creating your Site)
[4. Add Content to Your Site](## Adding Content to the Site)
[5. Guide to Using Markdown](## Guide to using Markdown)
[6. Adding a Theme to Your Site](### Add a Jekyll Theme to Your Site)

## Project Guidelines

The purpose of this project is to gather all of your hard work and expertise from the last year, and turn it into a online portfolio/resume.

You can put as much effort into this website as you would like. If you have projects from other class you want to include in your resume, please do. It would be awesome to see all of the things you guys have acomplished over your time at Heritage.

**The minimum requirements**
1. Website hosted on github and publicly accessible.
2. Website must have a style or theme. **Can't be generic html/text**.
3. Website must have the following sections: 
  *introduction section
  *about me
  *experience/work/school/certifications
  *projects
  *contact me
4. Your website must contain **at least** 3 Python projects. They can be projects you've done privately or projects from in class.

**This project is worth 25% of your grade** please take it seriously. As always, if you have any questions feel free to contain me via email or our discord server.

**When ready to submit** simply send me the link to your portfolio so I can review it. Additionally, our final day of class will be a presentation day for portfolios.

## Start a New Repository
I would recommend starting a new repository for your website because if you are using the free pages that github provides your website domain will be attached to your username and then you can link any files found on your account to your website.

**Create a repository just for the website**

1. Navigate to your github home page.

2. In the top right corner of your screen, you'll see a + symbol that will give you a drop-down menu. Open the menu and click new repository.

3. Once you're on the new repository page, you are going to specify a name for the repository. If you are using the free website option github has the repository name needs to be in this format: username.github.io

4. Choose the repository visibility. For our portfolio websites it will need to be set to public.

5. Scroll down and you'll see a section about initializing with documents. **Select "Initialize with a README**.

6. Click **Create Repository**

## Creating your Site
Now that you have the repository for your site, we need to activate github pages.

1. Navigate to the repository you just created. 

2. Open the settings in the repository.

3. Scroll down until you find the **Pages** section on your left hand side and click on it.

4. On the screen, you'll see a section that says **Source**. Click on the box under source and select **Deploy from a branch**.

5. Next, in the branching section you will see two drop-down menus. One should show your branch options and one should show your folder options. Select the branch location and the folder you want to access. IF you made a new repository for this website you should select **main** branch and **root** folder.

6. Save the new settings and wait for the website to render. Refresh the page periodically and when it's finished rendering, you'll find a link at the top of the page that says **Your site is live at** https://username.github.io/.

## Adding Content to the site
That's all it takes to acitvate your site. You now have a completely customizable website for you to build your portfolio on. 

To add content to your website, you can either use html/css/js or jekyll markdown files. Each has positives and negatives and it is 100% a matter of personal preference. 

In either case, when you are ready to upload your content to your new website all you have to do is:

1. Go to your website repository.

2. Select **Add File** and then select either create file or upload file.

3. Commit the changes to the file you are adding.

4. Wait for the site to render and refresh your website to check the accuracy of the changes you made.

**This technique will work for any files you upload.**

You can upload sections of code, excel files, pdf, html, css, js, md, pictures, etc. Anything you need can be saved to this repository, or another repository on your account and then you can link between the files through github. 

**Markdown example for including content**
For example, let's say I have uploaded an image into my github pages repository and I know want to include that on my page. All I need to do is this:

*syntax*

![alt text for accessibility](link to file)

*real example*

![photo of author](./file_name.png)

**Now, if the file is in a different repository:**

[Link Text](https://github.com/myusername/myrepo/blob/main/example.md)

## Guide to using Markdown

Github pages uses a static website generator called Jekyll Markdown, which comes from the Ruby programming language. 

Markdown files are very common in programming, other languages like R also support them, and other platforms like Jupyter notebooks are based entirely on the concept of markdown files.

If you choose to write your website in markdown here's a [cheat sheet](https://itopaloglu83.github.io/Jekyll-Markdown-Cheat-Sheet/).

Also, know that you can mix and match your html/css/js and markdown. If you take a look at my [README](https://github.com/BeeDrHU/beedrhu.github.io/blob/4c28f183a7d92d6707729705cab36f13ef50197a/README.md) you can see that I have html and css at the bottom of my page to include a contact form.

### Add a Jekyll Theme to Your Site

If you decide to use markdown, Github has free themes that you can use to style your site. Check them out [here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll).

Adding a theme is simple. Follow these steps:

1. Add a new file to your website repository called _config.yml

2. In this file you are going to specify these fields:
```
title: Dr_Bee's Portfolio
markdown: kramdown
remote_theme: pages-themes/theme-name
plugins:
- jekyll-remote-theme 
```
3. Commit the changes to the repository.

4. Wait for the website to render and deploy. Check that the theme has updated.
