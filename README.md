# Dev Landing Page With Jekyll

> Inspired at [dev-landing-page of Flexdinesh](https://github.com/flexdinesh/dev-landing-page)

> **Live Demo:** Here's my **Dev Landing Page With Jekyll [Rolly Sanchez](https://rollys.github.io)** :peru:

Minimal landing page for developers.

Developers don't talk much. Their code does all the talking. So here's a minimal landing page for developers.

---

<p align="center">
    <b><a href="README.md#what-is-inside">What is inside</a></b>
    |
    <b><a href="README.md#themes">Themes</a></b>
    |
    <b><a href="README.md#making-your-github-pages">Making your GitHub Pages</a></b>
    |
    <b><a href="README.md#customizing-theme">Customizing Theme</a></b>
    |
    <b><a href="README.md#custom-domain">Custom Domain</a></b>
    |
    <b><a href="README.md#running-in-local">Running in local</a></b>
    |
    <b><a href="README.md#using-docker">Using Docker</a></b>
    |
    <b><a href="README.md#using-docker-compose">Using Docker Compose</a></b>
    |
    <b><a href="README.md#todo">Todo</a></b>
    |
    <b><a href="README.md#credits">Credits</a></b>
    |
    <b><a href="README.md#the-beerware-license">The Beerware License</a></b>
</p>

## What is inside

- [Jekyll](https://jekyllrb.com/), [Sass](https://sass-lang.com/) and [Font-Awesome](https://fontawesome.com/);
- Google Speed for Desktop: [99/100](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Frollys.github.io%2F&tab=desktop);
- Google Speed for Mobile: [92/100](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Frollys.github.io%2F&tab=mobile);
- No JS. :sunglasses:
- Docker and Docker Compose. :smirk:

## Themes

Dev Landing Page With Jekyll comes in 12 **material themes**.

![9 Material Themes](https://image.ibb.co/jJVKCn/dev_landing_page_themes.jpg)
![1 Material Themes White Grey Pacifico](https://user-images.githubusercontent.com/5701014/107158770-4aedbe80-695a-11eb-9682-751fc233b06e.png)
![1 Material Themes Indigo White Pacifico](https://user-images.githubusercontent.com/5701014/107245634-5cd46d80-69fd-11eb-950a-27897bd584d6.png)
![1 Material Themes Yellow Black Pacifico](https://user-images.githubusercontent.com/5701014/107245635-5e059a80-69fd-11eb-9fd5-80b3ba99f768.png)

Also have one option for include any **background image**.

![Background Image Themes](https://user-images.githubusercontent.com/5701014/107158813-87211f00-695a-11eb-8259-887fadfa6965.png)

If none of these themes fit within your taste, it's quite easy to customize and create your own too.

## Making your GitHub Pages

GitHub makes it easy to create personal websites. Follow this link - [GitHub Pages](https://pages.github.com/) to know how or follow the steps below.

If you already have a GitHub profile (obviously)

- Fork this [repo](https://github.com/rollys/jekyll-dev-landing-page).
- In your repo fork, click in `settings` option. ![Setting repo](https://user-images.githubusercontent.com/5701014/107165085-c6159b80-697f-11eb-8ef9-8a1d11ac95e1.png)
- Now, you can rename you repo fork with the name `{username}.github.io` 
![Rename repo](https://user-images.githubusercontent.com/5701014/107165107-d6c61180-697f-11eb-9075-ee917ebad0ba.png)
- Also, you will should watch in the section `Github Pages` in the same `Settings` repo page, enabled your site. ![Rename repo](https://user-images.githubusercontent.com/5701014/107165466-00cc0380-6981-11eb-9381-0fbb38a239f3.png)
- Git clone your new repo fork.
- Then, Customize your name, links and everything else for your landing page.
- Finally `git push`

Voila! Your site should be live at `https://{username}.github.io`

> Note: Is very important that your clone your repo fork and modified anything, then you push your changes to show all world your github pages.

## Customizing Theme

You can customize theme with this options.

- Edit `_config.yml` file with your data in the attributes.
  - `theme_custom`: is the theme name find in the path `/_sass/variables/themes.scss`. You have 12 theme options: `green-white, grey-white, indigo-white, red-white, white-blue, white-grey, white-indigo, white-red, yellow-black, indigo-white-pacifico, white-grey-pacifico` and `yellow-black-pacifico`. For default: `indigo-white`.
  - `theme_name_background`: if you will desire background image in your landing page, your put just the image file name , else keep value in `false`. You can upload custom background image in the path `/assets/image/`. For default: `false`.
  - `theme_extension_background`: is just the extension of your background image file. For default: `png`.
  - `author`: is your name, this used to seo and "Hello, I,m _author_" at home page. For default: `Rolly`.
  - `title_intro`: is any text that will overwrite "Hello, I,m _author_" at home page, keep empty value for don't overwrite "Hello, I,m _author_". For default: _empty value_.
  - `skill_separator`: is the symbol that separate your skills at home page. For default: `|`.
  - `title_plataforms`: is the title for plataforms icon at home page, keep empty value for don't show this title. For default: `Connect with me on`.
  - `forkme`: show (`true` value) or hide (`false` value) _fork me_ button at home page. For default: `false`.
  - `forkme_link`: is the link of your repository of project,for default: `https://github.com/rollys/jekyll-dev-landing-page`.
- Edit `plataforms.yml` file: in this file your find a plataform list as `linkedin, twitter, stackoverflow, etc.` You add (or remove) plataform that you use, follow the format.
- Edit `skills.yml` file: here you put your skills, follow the format.
- Change the `favicon`: you can change or overwrite the favicon in the path `/assets/image/favicon.ico`. You can generate own favicon in _https://favicon.io/favicon-generator/_

### Custom Domain

If you want to make your new landing page available under a domain like `{username}.com` you can get started here - [Setting up a custom domain](https://help.github.com/articles/quick-start-setting-up-a-custom-domain/).

## Running in Local

For deploy in localhost.

- :star: to the project. :metal:
- Install ruby.
- Execute command in console `gem install bundler jekyll`
- Git clone or download this [project](https://github.com/rollys/jekyll-dev-landing-page) or your repo fork.
- Execute command in console `bundle install`
- Then run `bundle exec jekyll s`
- Look in the browser `http://127.0.0.1:4000/`

## Using Docker

Running the container from the root of your project ( obviously you have installed [docker](https://docs.docker.com/engine/install/) ):

```
docker run -d -p 4000:4000 -it --volume="$PWD:/srv/jekyll" --name "my_dev_landing_page" jekyll/jekyll:latest jekyll serve --watch --incremental --livereload --verbose
```

## Using Docker Compose

Run docker-compose from the root of your project ( obviously you have installed docker and [docker-compose](https://docs.docker.com/compose/install/) ):

`docker-compose up`

To off and remove the container and image:

`docker-compose down`

## TODO

What remains to be done.

- [ ] Minify Html.
- [ ] Optimize Css and Style inline.
- [ ] Add Style Core inline  in the layouts.
- [ ] Optimize calls of Css file external.
- [ ] Optimize calls of Fonts external (just font necesaries).
- [ ] Add project pages.
- [ ] Add post pages.
- [ ] Convert this template in jekyll-theme ruby gems.


## Credits

- [@flexdinesh](https://github.com/flexdinesh/)
- [@calina-c](https://calina-c.github.io/)
- [@tallesecb](https://tallesecb.github.io/)

## THE BEERWARE LICENSE

**Rolly Sanchez** was inspired in the code of _Dinesh Pandiyan_. As long as you retain this notice you can do whatever you want with this stuff. If we meet someday, and you think this stuff is worth it, you can buy me a beer in return.
