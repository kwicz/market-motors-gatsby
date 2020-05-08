# Market Motors


## Prerequisite
* Node
* Gatsby CLI (globally installed)

## Getting Started
Create your own project with Gatsby CLI:
```shell
gatsby new yourbusinessname https://github.com/v4iv/gatsby-starter-business.git 
```

## Available Scripts

### Develop
Start a hot-reloading development environment accessible at `localhost:8000`
```shell
yarn start
```

### Build
Get an optimized production build for your site generating static HTML and per-route JavaScript code bundles.
```shell
yarn build
```

### Serve
gatsby serve — Gatsby starts a local HTML server for testing your built site.
```shell
yarn serve
```

### Lint
Lint the code according to eslintrc file, for consistency.
```shell
yarn lint
```

### Clean
Remove the .cache and public for a scratch compile.
```shell
yarn clean
```

## Configuration
To personalize and configure this Starter open `config.js` file and replace the default values.

```javascript
module.exports = {
  siteTitle: 'Gatsby Starter Business', // Site title.
  siteTitleAlt: 'Business', // Alternative site title for SEO.
  siteLogo: '/icons/icon-512x512.png', // Logo used for SEO and manifest.
  siteUrl: 'https://gatsby-starter-business.netlify.com', // Domain of your website without pathPrefix.
  // Do not use trailing slash!
  pathPrefix: '/', // Prefixes all links. For cases when deployed to example.github.io/gatsby-starter-business/.
  siteDescription: 'Leverage Gatsby Business Starter for your Business.', // Website description used for RSS feeds/meta description tag.
  siteRss: '/rss.xml',
  siteFBAppID: '', // FB Application ID for using app insights
  googleTagManagerID: '', // GTM tracking ID.
  disqusShortname: 'gatsby-business-starter', // Disqus shortname.
  userName: 'Vaibhav Sharma',
  userTwitter: 'vaibhaved',
  userLocation: 'Delhi NCR, India',
  userDescription: '',
  copyright: 'Copyright © Gatsby Starter Business 2018. All Rights Reserved.', // Copyright string for the footer of the website and RSS feed.
  themeColor: '#00d1b2', // Used for setting manifest and progress theme colors.
  backgroundColor: '#ffffff', // Used for setting manifest background color.
}

```

## Deployment
Clicking the button will ask for authentication via Github, which will create a repo in your github account with this starter. Then, it will build and deploy the site to Netlify.

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/v4iv/gatsby-starter-business&amp;stack=cms"><img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify"></a>

You can read up on how to set up Identity(Authentication for CMS User) here [How To Set Up Netlify CMS](https://www.netlifycms.org/docs/add-to-your-site/)

### Technologies Used
* [React.js](https://reactjs.org/)
* [Material-UI](https://material-ui.com/)
* [Gatsby JS](https://www.gatsbyjs.org/)
* [Gatby Starter Proplogue](https://www.gatsbyjs.org/starters/anubhavsrivastava/gatsby-starter-business/) by Anubhav Srivatstava
* [JAMstack architecture](https://jamstack.org)
* [Netlify](https://www.netlify.com)

### Support and Contact Details
_Have a bug or an issue with this application? [Open a new issue](https://github.com/kwicz/market-motors/issues) here on GitHub._

### License

[![Open Source Love](https://badges.frapsoft.com/os/mit/mit.svg?v=102)](LICENSE)

Copyright (c) 2020 **_K. Wicz_**
