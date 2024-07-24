<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
> [!IMPORTANT]
> If you are migrating from v3 (`git submodule` based) theme to v4 (`hugo modules` based) theme, please read this [migration guide](https://toha-guides.netlify.app/posts/update-v3-to-v4/).

=======
>>>>>>> 46969da (updated to stable release)
=======
=======
> [!IMPORTANT]
> If you are migrating from v3 (`git submodule` based) theme to v4 (`hugo modules` based) theme, please read this [migration guide](https://toha-guides.netlify.app/posts/update-v3-to-v4/).

>>>>>>> upstream/main
>>>>>>> 2e395f0 (initial for rebase)
=======
=======
> [!IMPORTANT]
> If you are migrating from v3 (`git submodule` based) theme to v4 (`hugo modules` based) theme, please read this [migration guide](https://toha-guides.netlify.app/posts/update-v3-to-v4/).

>>>>>>> upstream/main
>>>>>>> 2e395f05247e00814659ae78ebf9d7a5403b59c0
# Toha

[![Netlify Status](https://api.netlify.com/api/v1/badges/b1b93b02-f278-440b-ae1b-304e9f4c4ab5/deploy-status)](https://app.netlify.com/sites/toha/deploys)
[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Fhugo-toha%2Ftoha%2Fbadge%3Fref%3Dmain&style=flat)](https://actions-badge.atrox.dev/hugo-toha/toha/goto?ref=main)
![Repository Size](https://img.shields.io/github/repo-size/hugo-toha/toha)
![Lines of Codes](https://img.shields.io/tokei/lines/github.com/hugo-toha/toha)
![Contributor](https://img.shields.io/github/contributors/hugo-toha/toha)
![Latest Release](https://img.shields.io/github/v/release/hugo-toha/toha?include_prereleases)
![Last Commit](https://img.shields.io/github/last-commit/hugo-toha/toha)
![Open Issues](https://img.shields.io/github/issues/hugo-toha/toha?color=important)
![Open Pull Requests](https://img.shields.io/github/issues-pr/hugo-toha/toha?color=yellowgreen)
![License](https://img.shields.io/github/license/hugo-toha/toha)
![Security Headers](https://img.shields.io/security-headers?url=https%3A%2F%2Fhugo-toha.github.io%2F)
[![This project is using Percy.io for visual regression testing.](https://percy.io/static/images/percy-badge.svg)](https://percy.io/b7cb60ab/hugo-toha.github.io)

A [Hugo](https://gohugo.io/) theme for a personal portfolio with minimalist design and responsiveness.

![Thumbnail](https://raw.githubusercontent.com/hugo-toha/toha/main/images/screenshot.png)

- **Example Site:** [hugo-toha.github.io](https://hugo-toha.github.io)
- **Documentation:** [toha-guides.netlify.app](https://toha-guides.netlify.app/posts)

## Features

- Minimalist Design
- Fully Responsive
- Multiple Language Support
- Carefully Designed Cards
- Experience Timeline
- Achievement Gallery
- Sidebar to Categorize the Posts
- Short Codes
- Analytics Support
  - GoatCounter
  - counter.dev
  - Google Analytics
  - Matomo/Piwik
  - [Umami](https://umami.is/)
- Comment Support
  - [Disqus](https://disqus.com/)
  - [Valine](https://valine.js.org/)
  - [Uttarances](https://utteranc.es/)
  - [Giscus](https://giscus.app/)

For more details about the features please visit [here](https://toha-guides.netlify.app/posts/features/).

## Available Translations

- English
- বাংলা
- Français
- Indonesian
- Deutsch
- Español
- 简体中文
- हिन्दी
- Italiano
- 日本語
- 한국어
- русский
- suomi
- Tiếng Việt
- Turkish
- Arabic (العربية)
<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
=======
- Português
=======
>>>>>>> 2e395f05247e00814659ae78ebf9d7a5403b59c0
- Português Europeu
- Català
- Português Brasileiro
- Nederlands
- Hebrew
<<<<<<< HEAD
=======
- Português
>>>>>>> 46969da (updated to stable release)
=======
- Português
=======
- Português Europeu
- Català
- Português Brasileiro
- Nederlands
- Hebrew
>>>>>>> upstream/main
>>>>>>> 2e395f0 (initial for rebase)
=======
>>>>>>> upstream/main
>>>>>>> 2e395f05247e00814659ae78ebf9d7a5403b59c0

To know more about how to translate your site, please visit [here](https://toha-guides.netlify.app/posts/translation/). Follow, the data and post format from this [example site](https://hugo-toha.github.io).

## Screenshots

Here are few screenshots from the [example site](https://hugo-toha.github.io).

##### Home Page Sections

![Home Page Sections](https://raw.githubusercontent.com/hugo-toha/toha/main/images/about.png)

##### List Page

![List Page](https://raw.githubusercontent.com/hugo-toha/toha/main/images/list.png)

##### Reading Page

![Reading Page](https://raw.githubusercontent.com/hugo-toha/toha/main/images/single.png)

## Requirements

<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
- Hugo Version 0.118.0 (extended) or higher
- Go language 1.18 or higher (require for hugo modules)
- Node version v18.x or later and npm 8.x or later.
=======
- Hugo Version 0.87.0 or higher
>>>>>>> 46969da (updated to stable release)
=======
- Hugo Version 0.87.0 or higher
=======
- Hugo Version 0.118.0 (extended) or higher
- Go language 1.18 or higher (require for hugo modules)
- Node version v18.x or later and npm 8.x or later.
>>>>>>> upstream/main
>>>>>>> 2e395f0 (initial for rebase)
=======
- Hugo Version 0.87.0 or higher
=======
- Hugo Version 0.118.0 (extended) or higher
- Go language 1.18 or higher (require for hugo modules)
- Node version v18.x or later and npm 8.x or later.
>>>>>>> upstream/main
>>>>>>> 2e395f05247e00814659ae78ebf9d7a5403b59c0

## Usage

In order to use this theme, follow the following steps:

#### Add theme as git submodule

At first, add [Toha](https://github.com/hugo-toha/toha) theme as git submodule to your hugo-site.

```console
$ git submodule add https://github.com/hugo-toha/toha.git themes/toha
```

> Don't use SSH URL of the theme during adding as git sub-module. Also, don't clone the theme in your `themes` directory using `git clone`. They don't work well with Github Action or Netlify.

<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
Now, in your `hugo.yaml` file, add a `module` section.
=======
=======
>>>>>>> 2e395f0 (initial for rebase)
=======
>>>>>>> 2e395f05247e00814659ae78ebf9d7a5403b59c0
If you don't already have a hugo site, create one by following the step-by-step guide from [here](https://toha-guides.netlify.app/posts/getting-started/prepare-site/).

#### Configuring Site

Now, configure your site to use `toha` theme by adding the following configuration in `config.yaml` file of your site.
<<<<<<< HEAD
<<<<<<< HEAD
>>>>>>> 46969da (updated to stable release)
=======
=======
Now, in your `hugo.yaml` file, add a `module` section.
>>>>>>> upstream/main
>>>>>>> 2e395f0 (initial for rebase)
=======
=======
Now, in your `hugo.yaml` file, add a `module` section.
>>>>>>> upstream/main
>>>>>>> 2e395f05247e00814659ae78ebf9d7a5403b59c0

```yaml
baseURL: https://hugo-toha.github.io

languageCode: en-us
title: "John's Blog"
theme: "toha"

# Manage languages
# For any more details, you can check the official documentation: https://gohugo.io/content-management/multilingual/
languages:
  en:
    languageName: English
    weight: 1

# Control TOC depth
markup:
  tableOfContents:
    startLevel: 2
    endLevel: 6
    ordered: false

# At least HTML and JSON are required for the main HTML content and
# client-side JavaScript search
outputs:
  home:
  - HTML
  - RSS
  - JSON

# Enable global emoji support
enableEmoji: true

# Site parameters
params:
  # GitHub repo URL and branch of your site
  gitRepo: https://github.com/hugo-toha/hugo-toha.github.io
  gitBranch: main

  # specify whether you want to write some blog posts or not
  enableBlogPost: true

  # specify whether you want to show Table of Contents in reading page
  enableTOC: true

  # specify whether you want the language flags to be displayed. 
  showFlags: true

  # Provide newsletter configuration. 
  # This feature has been implemented for Mailchimp only for now.
  # You can also hide it from the footer.
  newsletter:
    # specify whether you want to display the newsletter form 
    enable: true
    # specify which newsletter provider you want to use
    provider: mailchimp
    # specify the target URL for the subscription form
    mailchimpURL: https://github.us1.list-manage.com/subscribe/post?u=19de52a4603135aae97163fd8&amp;id=094a24c76e
```

<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
=======
Don't forget to update `title`, `baseURL`, and `gitRepo` fields with your own information. To know about more available configuration options, please visit [here](https://toha-guides.netlify.app/posts/configuration/site-parameters/).
=======
>>>>>>> 2e395f05247e00814659ae78ebf9d7a5403b59c0
Check this sample [hugo.yaml](https://github.com/hugo-toha/hugo-toha.github.io/blob/main/hugo.yaml) for further reference.

##### 3. Update your module

Now, run this command to load this theme as your module.

```bash
hugo mod tidy
```
<<<<<<< HEAD
=======
Don't forget to update `title`, `baseURL`, and `gitRepo` fields with your own information. To know about more available configuration options, please visit [here](https://toha-guides.netlify.app/posts/configuration/site-parameters/).
>>>>>>> 46969da (updated to stable release)
=======
Don't forget to update `title`, `baseURL`, and `gitRepo` fields with your own information. To know about more available configuration options, please visit [here](https://toha-guides.netlify.app/posts/configuration/site-parameters/).
=======
Check this sample [hugo.yaml](https://github.com/hugo-toha/hugo-toha.github.io/blob/main/hugo.yaml) for further reference.

##### 3. Update your module

Now, run this command to load this theme as your module.

```bash
hugo mod tidy
```
>>>>>>> upstream/main
>>>>>>> 2e395f0 (initial for rebase)
=======
>>>>>>> upstream/main
>>>>>>> 2e395f05247e00814659ae78ebf9d7a5403b59c0

#### Running Locally

Now, you can run your hugo site with `toha` theme locally with the following command:

```console
$ hugo server --theme toha --watch
```

When you run your site for first time, it will start with the default parameters. It should look similar to the [example site](https://hugo-toha.github.io). However, it will not have any sections in the homepage as we haven't configured them yet. You can configure your site by following the guides from [here](https://toha-guides.netlify.app/posts/configuration/).

## Shortcodes

Here, are some handy shortcodes you can use with this theme.

- [Alert](https://toha-guides.netlify.app/posts/shortcodes/#alert)
- [Image](https://toha-guides.netlify.app/posts/shortcodes/#image)
- [Split](https://toha-guides.netlify.app/posts/shortcodes/#split)
- [Vertical Space](https://toha-guides.netlify.app/posts/shortcodes/#vertical-space)
- [Video](https://toha-guides.netlify.app/posts/shortcodes/#video)
- [Mermaid](https://hugo-toha.github.io/posts/shortcodes/#mermaid)

## Project Roadmap

Here, are the current plan and progress of various components of this theme. The components will be prioritized based on users requests.

### 1. Portfolio Mode

Here is the check list for portfolio mode,

- [x] **Home**

  - [x] Configurable Background
  - [x] Author Image
  - [x] Greeting
  - [x] Typing Carousel

- [x] **About**

  - [x] Name and Designation
  - [x] Summary
    - [x] Markdown Support
  - [x] Social Links
    - [x] Font Awesome Support
  - [x] Resume Link
  - [x] Soft Skills Indicator

- [x] **Skills**

  - [x] Skill Cards
  - [x] Markdown Support

- [x] **Experiences**

  - [x] Designation
  - [x] Timeline
  - [x] Company Overview
  - [x] Responsibilities

- [x] **Projects**

  - [x] Category Filter
  - [x] Project Card
    - [x] Overview
      - [x] Markdown Support
    - [x] Github Stars
    - [x] External URL Support
    - [x] Technology Tags

- [x] **Recent Posts**

- [x] **Academic Career**

  - [x] Degree
  - [x] Institution
  - [x] Timeline
  - [x] Taken Courses
  - [x] CGPA
  - [x] Extracurricular Activities

- [ ] **Publications**

  - [x] Category Filter
  - [x] Card
  - [x] Tags
  - [x] Links
  - [ ] Dedicated Page
    - [ ] Abstract
    - [ ] Authors
    - [ ] Gallery

- [x] **Accomplishment / Courses**

  - [x] Overview
  - [x] Certificate

- [x] **Achievements Gallery**
  - [x] Image
  - [x] Summary

### 2. Blog Mode

Here is the checklist for blog mode,

- [ ] **Dedicated Home page**

- [x] **List Page**

  - [x] Post Cards
  - [x] Sidebar
  - [x] Pagination

- [x] **Reading Page**

  - [x] Hero Image
  - [x] Author Information
  - [x] Sidebar
  - [x] Table of Contents
  - [x] Next & Previous Page Navigation
  - [x] `Improve This Page` Button
  - [x] Disqus Comment

### 3. Documentation Mode

Here is the check list for documentation mode,

- [ ] **Dedicated Home Page**
- [ ] **Doc Page**
  - [ ] Redesign sidebar
  - [ ] Redesign TOC menu
  - [ ] Search Capability

### 4. Note Mode

- [ ] **Dedicated Home Page**
- [ ] **Note Page**
  - [x] Add note view
  - [ ] Redesign sidebar
  - [ ] Add search capability

### 5. Tracking and Comments

- [x] Google Analytics
- [x] Disqus Comment

### 6. Shortcodes

- [x] Image
- [x] Split Page into Multiple Column
- [x] Vertical space between two sections
- [x] Alert
- [ ] Figure & sub-figure
- [ ] Tabs
- [x] Notes

## Contributing

You can contribute to this theme in various ways. You can report a [bug](https://github.com/hugo-toha/toha/issues/new?template=bug.md), file an [feature request](https://github.com/hugo-toha/toha/issues/new?template=feature_request.md), send a PR, [share your thoughts](https://github.com/hugo-toha/toha/issues/new?template=question.md) etc.

Pull requests are most welcome and I will be happy to review. Just follow the following principles:

- Keep it simple.
- Keep it consistent with the design.
- Use as few dependencies as possible.
- Have patience.

> I am not a web developer. I have created this theme for my personal needs. So, it is reasonable to have some flaws in the codes. Feel free to open issues and PRs acknowledging the problems.

## Local Development

For local development, you can make changes in the theme submodule and test the changes against your own site or this [example site](https://github.com/hugo-toha/hugo-toha.github.io) locally.

### Fork

At first, fork [this repo](https://github.com/hugo-toha/toha). Then, follow the following steps to use the forked theme for local developments,

#### Running the forked theme against the example site

If your want to run your local development against this [example site](https://github.com/hugo-toha/hugo-toha.github.io), follow the following steps:

```bash
# go to exampleSite directory
$ cd exampleSite
# install hugo modules
$ hugo mod tidy
# install dependencies
$ hugo mod npm pack
$ npm install
# run the example site locally
$ hugo server -w
```

Now, you can make change in the theme and they will be reflected immediately on the running site. If you need to change any configuration, you can do that in the `hugo.yaml` file inside `exampleSite` folder. If you need to add any content or data, you can create the respective folder inside `exampleSite` directory and add your desired content or data there.

#### Running the forked theme against your own site

If you want to run your local development against your own site, follow the following steps:

**Replace the theme module:**

Open your site's `go.mod` file and replace the `github.com/hugo-toha/toha/v4` with your forked repo's path. For example, if your forked repo is `github.com/<your-github-user>/toha`, then replace the `github.com/hugo-toha/toha/v4` with `github.com/<your-github-user>/toha/v4`.

```go
module github.com/hugo-toha/hugo-toha.github.io

go 1.19

require github.com/hugo-toha/toha/v4 v4.0.1-0.20231229170427-d3968ca711ef // indirect

replace(
    github.com/hugo-toha/toha/v4 => github.com/<your-github-user>/toha/v4 <git branch>
)
```

For interactive development, you can replace the theme with your locally cloned fork. For example, if you have cloned your fork in `/home/my-projects/toha`, then replace the `github.com/hugo-toha/toha/v4` with `/home/my-projects/toha`.

```go
module github.com/hugo-toha/hugo-toha.github.io

go 1.19

require github.com/hugo-toha/toha/v4 v4.0.1-0.20231229170427-d3968ca711ef // indirect

replace(
    github.com/hugo-toha/toha/v4 => /home/my-projects/toha
)
```

**Update dependencies:**

```bash
# update hugo modules
$ hugo mod tidy
# install dependencies
$ hugo mod npm pack
$ npm install
```

**Run your site locally:**

```bash
$ hugo server -w
```

From there you can make changes to the source code of the theme while testing with your running Hugo site or the example site.

### Open a PR

When the changes look good, commit and push them to your fork.

```bash
# stage all the changes
$ git add .
# commit the changes with a meaning full commit message
$ git commit -m "A meaningful commit message"
# push the commit to your fork
$ git push my-fork my-feature-branch
```

Then, open a PR against `main` branch of [hugo-toha/toha](https://github.com/hugo-toha/toha) from the `my-feature-branch` branch of your own fork.

## Attribution

- Thanks [Anup Deb](https://dribbble.com/anupdeb) for his design guidance.
- Many of the illustrations have been taken from [iconscout](http://iconscout.com/).
