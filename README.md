# 4pflo-static-website-myteam

[![Netlify Status](https://api.netlify.com/api/v1/badges/d8ca0b0f-648b-4be3-813f-d43a1acb6c13/deploy-status)](https://app.netlify.com/sites/soft-brioche-59c829/deploys)\
Production URL: https://soft-brioche-59c829.netlify.app/

<br />

## 🪶Aspiration

Credit is given to [Frontend Mentor](<[frontendmentor.io](https://www.frontendmentor.io/challenges/myteam-multipage-website-mxlEauvW)>) for the design.

<br />

## 💡 Takeaways

> > How to make footer stay at the bottom of the page?

```
  <body>
    <div class="container">
      <div class="header">...</div>
      <div class="main">...</div>
      <div class="footer">...</div>
    </div>
  </body>
```

- Set css to `div.container`:

  - `min-height: 100vh`
  - `display: flex`
  - `flex-direction: column`

- Set css to `div.main`
  - `flex-grow: 1`

<br />

> > How to bundle static site using Parcel?

- Create a `package.json` file, using `yarn init` or `npm init`
- Install Parcel dev-dependency, using `yarn add -D parcel`
- Update `package.json` file:
  - Define source file
    ```
    "source": "index.html"
    ```
  - Define scripts
    ```
    "scripts": {
      "start": "parcel",
      "build": "parcel build"
    }
    ```
    _`yarn start` => for development_\
    _`yarn build` => for production build_
- Bundled version of the site will be output to `/dist` directory at the root of project

<br />

## 👾 Technologies

- **HTML5** : used for structuring the site
- **CSS3** : used for styling the site

<br />

## 💎 Applied Conventions

- **BEM** (Block Element Modifier)
  - [BEM 101 CSS Tricks](https://css-tricks.com/bem-101/)

<br />

## 👽 3rd-Party Libraries

- **Parcel** [🔗](https://parceljs.org/) : used for bundling site's resources
- **Font Awesome Icons Kits** [🔗](https://fontawesome.com/docs/web/setup/use-kit)

<br />

## 🪚 Tools

- **befunky** [🔗](https://www.befunky.com/) : use its free plan to design artwork images for the site
- **Netlify** [🔗](https://www.netlify.com/) : used for deployment

<br />

## 📒 Further Readings

- [Building a web app with Parcel](https://parceljs.org/getting-started/webapp/)
- [A Step-by-Step Guide: Deploying A Static Site or Single-page App](https://www.netlify.com/blog/2016/10/27/a-step-by-step-guide-deploying-a-static-site-or-single-page-app/)
