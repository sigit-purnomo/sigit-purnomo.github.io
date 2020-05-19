---
title:  "Tutorial: How to Create GitHub Pages for Academia"
excerpt: "As academia, having a website to publish portfolios is really important. GitHub Pages will be a perfect solution because it doesn't cost anything. There is no need to buy a domain and web hosting service. Everything is all in Github. This tutorial will guide you to build your GitHub Pages. Please enjoy it! "
date: 2020-05-19
permalink: /posts/2020/05/tutorial-how-to-create-github-pages-for-academia/
categories: [tutorial]
tags: [academia-github-pages]
---

The main objective of this tutorial is to give step-by-step guides for academia that wants to publish his/her academic portfolios using GitHub Pages.

### Step #1: Sign Up to GitHub 

1. Go to [GitHub](https://github.com) website using your browser and klik the Sign Up button.

   ![GitHub Homepage](/assets/images/github-homepage.png "GitHub Homepage")

2. Fill the form to create new account. <br />
   **Note:** Please wisely choosing your username account. It will become the address of your GitHub Pages. As academia, known by your real name is very important, so if it is still available, I suggest setting the username like this: **firstnamelastname** or **firstname-lastname**.

   ![GitHub Create New Account](/assets/images/github-join.png "GitHub Create New Account")

3. Sign In using your new account

   ![GitHub Sign In](/assets/images/github-sign-in.png "GitHub Sign In")


### Step #2 Fork the GitHub Pages Repository

1. Go to [my GitHub Pages Repository](https://github.com/sigit-purnomo/sigit-purnomo.github.io) using your browser.

   ![Girhub Personal Site Repository](/assets/images/repository-github.png "Girhub Personal Site Repository")

2. Click the fork Icon.

   ![Girhub Personal Site Repository Fork](/assets/images/repository-github-fork.png "Girhub Personal Site Repository Fork")

3. Go to your new repository then click the Settings Icon

   ![Github New Repository Settings](/assets/images/repository-settings.png "Github New Repository Settings")

4. Rename your new repository to your-username.github.io.

   ![Github New Repository Rename](/assets/images/repository-rename.png "Github New Repository Rename")


### Step #3 Configure Your GitHub Pages

1. Click the **_config.yml** file in your repository then click the Pencil Icon. 

   ![Configure GitHub Pages](/assets/images/configuration-edit.png "Configure GitHub Pages")

   a. Configure Your Github Pages Description <br />
      This part is to configure your site description, like title, description, etc. Please edit as your wish.

      ![Configure GitHub Pages Description](/assets/images/configuration-settings-description.png "Configure GitHub Pages Description")

   b. Configure Your Github Pages Profile <br />
      This part is to configure your profile, like name, avatar, bio, location, and link to some of your important things, like email and social media account. As academia, my suggestion is you should add links to your Google Scholar, ResearchGate, Orcid ID, and SINTA Profile (Indonesian Only).

      ![Configure GitHub Pages Profile](/assets/images/configuration-settings-profile.png "Configure GitHub Pages Profile")

   c. Configure Your Github Pages Footer <br />
      This part is to configure your site footer, like link to your social media account. Please edit as your wish.

      ![Configure GitHub Pages Footer](/assets/images/configuration-settings-footer.png "Configure GitHub Pages Footer")   

   d. Commit Your Configuration <br />
      After finish the configuration, don't forget to commit your change by fill the form and click te **Commit changes** button.

      ![Configure GitHub Pages Footer](/assets/images/configuration-commit.png "Configure GitHub Pages Footer")   

2. Click the **_data** folder in your repository then edit the **navigation.yml** file.  <br />
   This file contains the menu configuration for your GitHub Pages. Please edit it to fit your requirements. Don't forget to commit the changes by clicking the Commit changes Button.

   ![Configure GitHub Pages Menu](/assets/images/navigation-edit.png "Configure GitHub Pages Menu")

### Step 4: Edit Your GitHub Pages Contents

GitHub Pages content mostly consists of pages (saved in _pages folder) and posts (saved in _posts folder). You can use pages type content to create content like about me, publication portfolio, and research portfolio. Whereas post type of content, you can use it to create content to publish your opinion, thought, or tutorial like this content. You can follow this step both to edit the pages or posts. 

1. Click the **_pages** folder in your repository to see the list of the pages contents.<br />

  ![GitHub Pages Contents](/assets/images/pages-lists.png "GitHub Pages Contents]")

2. Edit all of the pages with information about you and your portfolios.<br />
   Both of the pages and posts content using the Markdown format. You can learn about the Markdown format **[here]**(https://guides.github.com/features/mastering-markdown/). <br />
   **Note:** If you want to add image in your content, don't forget to upload the image in **/assets/images/** folder.
   
   ![GitHub About Pages Edit](/assets/images/pages-content.png "GitHub About Pages Edit")

   ![GitHub About Pages Contents](/assets/images/pages-content-edit.png "GitHub About Pages Contents")

3. Commit the Changes.<br />
   After finish edit the content, don't forget to commit your change by fill the form and click te **Commit changes** button.

   ![GitHub Pages Commit Changes](/assets/images/pages-content-commit.png "GitHub Pages Commit Changes")   


### Final Note
If you want to learn about how to customize your GitHub Pages, you can go to the Jekyll Documentation here:
1. [Pages](https://jekyllrb.com/docs/pages/)
2. [Posts](https://jekyllrb.com/docs/posts/)
3. [Front Matter](https://jekyllrb.com/docs/front-matter/)
4. [Collections](https://jekyllrb.com/docs/collections/)
5. [Layouts](https://jekyllrb.com/docs/layouts/)

Aside, there is also a complete documentation about Minimal Mistakes Template that used in this repository. You can access it here in [Quick-Start Guide](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).
