# gatsby-starter-identity

Gatsby.js V2 starter template based on Identity by HTML5 UP

For an overview of the project structure please refer to the [Gatsby documentation - Building with Components](https://www.gatsbyjs.org/docs/building-with-components/).

![Screenshot](./src/assets/img/identity.jpg)

Check online preview [here](https://anubhavsrivastava.github.io/gatsby-starter-identity/)

## Screenshot

![Screenshot](./src/assets/img/demo.png)

## Install

Make sure that you have the Gatsby CLI program installed:

```sh
npm install --global gatsby-cli
```

And run from your CLI:

```sh
gatsby new <site-name> https://github.com/anubhavsrivastava/gatsby-starter-identity
```

Then you can run it by:

```sh
cd gatsby-example-site
npm install
gatsby develop
```

### Personalization

Edit `config.js` to put up your details

```javascript
module.exports = {
  siteTitle: 'Gatsby Starter Identity', // <title>
  ...
  authorName: 'Anubhav Srivastava',
  heading: 'Web Developer',
  // social
  socialLinks: [
    {
      icon: 'fa-github',
      name: 'Github',
      url: 'https://github.com/anubhavsrivastava',
    }
    ...
  ],
};

```