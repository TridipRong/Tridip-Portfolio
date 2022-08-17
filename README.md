
<h1 align="center"> ⚡️ TridipFolio ⚡️</h1>


## A Modern Portfolio Template for Developers!

<h2 align="center">
  <img src="assets/devfolio.gif" alt="Devfolio" width="1905px" />
</h2>

## Features

⚡️ Modern UI Design + Reveal Animations + Hover Effects\
⚡️ Well organized documentation\
⚡️ One Page Layout\
⚡️ Custom SCSS\
⚡️ Fully Responsive\
⚡️ Valid HTML5 & CSS3\
⚡ Fast and SEO Optimized

To view a demo example, **[Click Here](https://tridip-rong-portfolio.netlify.app/)**\
To view a live example, **[Click Here](https://github.com/TridipRong/myPortFolio)**\


## Getting Started 🚀

Here's a **Complete Guide** to walk you through the process of setting your own Portfolio Website with this minimal template on your local machine as well as hosting it on GitHub.



<h3 align="center">
OR
</h3>

Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> or <kbd>F1</kbd> to Show Command Palette, Search for **Watch Sass** and turn it on. Also search for **Open With Live Server** and turn it on. Doing this will watch all your Sass files for changes and will open the website in your browser to preview live.

<!-- Hero Section -->
<div id="hero">
  <section class="container">
    <h1 class="hero-title">
      Hi, my name is <span class="text-color-main name">Tridip Rong</span>
      <br />
      I'm a Back-End Developer.
    </h1>
    <p class="hero-cta">
      <a class="cta-btn cta-btn--hero" href="#about">Get in touch</a>
    </p>
  </section>
  <a href="#about" class="scroll-down-link" aria-label="scroll-down">
    <div class="scroll-down"></div>
  </a>
</div>
<!-- /END Hero Section -->
```

### About Section

- On `<img>` tag, fill the `src` attribute with your profile picture, your picture must be located inside [`assets/`](./assets) folder.
  - Recommended size for your profile image is (_450 x 450px_).
- On `<p>` tag with class-name `.about-wrapper__info-text`, include information about you, I recommend to use 2 paragraphs in order to work well and a maximum of 3 paragraphs.
- On last `<a>` tag, include your resume url on `href` attribute.

```html
<!-- About Section -->
<section id="about">
  <div class="container">
    <h2 class="section-title">About Me</h2>
    <div class="row about-wrapper">
      <div class="about-wrapper__image">
        <img class="img-fluid" src="./assets/profile.png" alt="Profile Image" />
      </div>
      <div class="about-wrapper__info">
        <p class="about-wrapper__info-text">
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </p>
        <p class="about-wrapper__info-text">
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </p>
        <span class="about-wrapper__cta">
          <a href="#" class="cta-btn cta-btn--resume">View Resume</a>
        </span>
      </div>
    </div>
  </div>
</section>
<!-- /END About Section -->
```

### Projects Section

- Each project lives inside `row` class.
- On `<h3>` tag with class-name `.project-wrapper__text-title`, include your project title.
- On `<p>` tag with `loremp ipsum...` text, include your project information.
- On first `<a>` tag, put your project url on `href` attribute.
- On second `<a>` tag, put your project repository url on `href` attribute.

---

- Inside `<div>` tag with class-name `.project-wrapper__image`, put your project image url on the `src` of the `<img>` and put again your project url on `href` attribute of `<a>` tag.
- Recommended size for project image (_1366 x 767px_), your project image must live in [`assets/`](./assets) folder. You can remove the default images and replace them with yours.

```html
<!--Projects Section-->
    <section id="projects">
      <div class="container">
        <div class="project-wrapper">
          <h2 class="section-title dark-blue-text">Projects</h2>

        <!-- Each .row is a project -->
          <div class="row">
            <div class="project-wrapper__text">
              <h3 class="project-wrapper__text-title">Fap-Bag Clone</h3>
              <p class="project-wrapper__text-info">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
              <div class="project-wrapper__text-btns">
                <a
                  href="#"
                  target="_blank"
                  class="cta-btn cta-btn--hero cta-btn--projects"
                  >See Live</a
                >
                <a href="#" target="_blank" class="cta-btn text-color-main"
                  >Source Code</a
                >
              </div>
            </div>

            <div class="project-wrapper__image">
              <a href="#" target="_blank">
                <div class="thumbnail rounded">
                  <img
                    src="./assets/WhatsApp Image 2022-08-17 at 11.26.03 AM.jpeg"
                    class="img-fluid"
                    alt="Project Image"
                  />
                </div>
              </a>
            </div>
          </div>
          ...
          </section>
<!-- /END Project -->
```

### Contact Section

- On `<p>` tag with class-name `.contact-wrapper__text`, include some custom call-to-action message.
- On `<a>` tag, put your email address on `href="mailto:` attribute.

```html
<!-- Contact Section -->
<section id="contact">
  <div class="container">
    <h2 class="section-title">Contact</h2>
    <div class="contact-wrapper">
      <p class="contact-wrapper__text">[Put your call to action here]</p>
      <a href="mailto:" class="cta-btn cta-btn--resume">Call to Action</a>
    </div>
  </div>
</section>
<!-- END Contact Section -->
```

### Footer Section

- Put your social media link on each `<a>` links.
- If you have more social-media accounts, see [Font Awesome Icons](https://fontawesome.com/v4.7.0/icons/) to put the corresponding additional social icon classNames.
- You can delete or add as many `<a>` links your want.

```html
<!-- Footer Section -->
<footer class="footer">
  ...
  <div class="social-links">
    <a href="https://twitter.com/rong_tridip" target="_blank">
      <i class="fa fa-twitter"></i>
    </a>
    <a href="https://www.instagram.com/tridiprong/?hl=en" target="_blank">
      <i class="fa fa-instagram"></i>
    </a>
    
    <a href="https://www.linkedin.com/in/tridip-rong-4b11481b2/" target="_blank">
      <i class="fa fa-linkedin"></i>
    </a>
    <a href="https://github.com/TridipRong" target="_blank">
      <i class="fa fa-github"></i>
    </a>
  </div>
  ...
</footer>
<!-- END Footer Section -->
```

### Step 2 - STYLES

Change the color theme of the website ( choose 2 colors to create a gradient ):

Go to [`style/base/_variables.scss`](./style/base/_variables.scss) and only change the values on these properties `$main-color` and `$secondary-color` to your prefered HEX color.

Save the `.scss` file so that the **Live Sass Compiler** extension compiles it to `.css`.

```scss
// Default values
$primary-color: #36d1dc;
$secondary-color: #5b86e5;
```

**NOTE**: I highly recommend to checkout gradients variations on [UI Gradient](https://uigradients.com/#Scooter)

---

- You can clear the README.md file and add you own readme to it.
- Also you don't need to push the [`style`](./style) folder, so you can add [`style`](./style) to [`.gitignore`](./.gitignore) file to ignore it while pushing it to the repo.
- Delete the file [`CNAME`](./CNAME) before you push it.

---

## Deployment 📦

- Head to your GitHub account and create a new repo. And set a new remote for our template repo.

  Note: remote URL will be different.

  ```bash
  # set a new remote
  $ git remote add origin https://github.com/user.repo.git
  ```

- Now commit all your changes with a commit message and push the code to your newly created repo.

  ```bash
  # commit changes
  $ git commit -m 'created my portfolio'
  # push the changes
  $ git push -u origin master
  ```

- Refresh your repo page and head to the settings tab. Now scroll down till you see GitHub Pages. In the Source section select the branch to be master and save it!
- Voilà your Portfolio should be live at `https://username.github.io/repoName/`

## Technologies used 🛠️

- [Sass](https://sass-lang.com/documentation) - CSS extension language
- [ScrollReveal.js](https://scrollrevealjs.org/) - JavaScript library
- [Tilt.js](https://gijsroge.github.io/tilt.js/) - JavaScript tiny parallax library

## Authors

- **Anil Seervi** - [https://github.com/AnilSeervi](https://github.com/AnilSeervi)

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🎁

I was motivated and inspired while learning [ZTM: Complete Web Developer](https://www.udemy.com/course/the-complete-web-developer-zero-to-mastery/) to create a simpler version of [simplefolio](https://github.com/cobidev/simplefolio) for those who didn't know node and packages.

---

<h2 align="center">Have Fun Creating Your Own Portfolio Website.</h2>
