This is the repository for the BIOL409 Website.

The repository was originally forked from [**Beautiful Jekyll**](https://github.com/BIOL409/BIOL409.github.io/blob/master/BeautifulJekyll_info.md). See the intructions there if you want to learn more about it.

Most of the original template and workflow used for the version of the course in 2016 is ready to use and modify in future versions. So you don't have to worry (a lot) about the details in specific folders and scripts.

People with access to the repository would be able to directly create md files to add new content and posts to the website. Alternatively, you can also follow the [instructions](https://resources.github.com/whitepapers/github-and-rstudio/) to clone the remote repository and create a local copy in your computer to modify the content using R Studio. You would need to install Git, RStudio if you don't have them and you will need a GitHub account. 

- If you want to modify pre-existing links such as "TheCourse" or "schedule", open the specific `.md` file of interest and edit them.

- If you want to create new links on the website, you will have to first create a new .md file with the content and save it. The you will have to modify the `_config.yml` to allow this new file to appear as a navigation bar. You do this by including the name and exact file name in the `navbar-links` section of the file.

- `_config.yml_` is the place to modify all the settings that will appear in the website, there are lots of comments from the original author, so this step should be a bit straightforward.

- Information that you want to be displayed as a post, should be inside the [`_posts`](./posts) directory

- All the pictures used on the website are in [`_img`](https://github.com/BIOL409/BIOL409.github.io/tree/master/img). You can add more to link them to specific posts, etc.

In general, If there is something you are not sure about, I would recommend going back to the original instructions [here](https://github.com/BIOL409/BIOL409.github.io/blob/master/BeautifulJekyll_info.md).
