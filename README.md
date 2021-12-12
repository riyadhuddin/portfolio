<div align="center">
  
# portfolio 
 
[![Twitter](https://img.shields.io/twitter/url?label=Tweet&style=social&url=https%3A%2F%2Fgithub.com%2FRiyadhUddin%2Fportfolio)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2FRiyadhUddin%2Fportfolio) [![GitHub forks](https://img.shields.io/github/forks/RiyadhUddin/portfolio?style=plastic)](https://github.com/RiyadhUddin/portfolio/network) [![GitHub stars](https://img.shields.io/github/stars/RiyadhUddin/portfolio?style=plastic)](https://github.com/RiyadhUddin/portfolio/stargazers)

[![Netlify Status](https://api.netlify.com/api/v1/badges/5c1dcb34-cada-4c80-82b7-cfdbdbd7c774/deploy-status)](https://app.netlify.com/sites/portfolio/deploys)
![Repository Size](https://img.shields.io/github/repo-size/RiyadhUddin/portfolio)
![Latest Release](https://img.shields.io/github/v/release/RiyadhUddin/portfolio?include_prereleases)
![Last Commit](https://img.shields.io/github/last-commit/RiyadhUddin/portfolio)
![Open Issues](https://img.shields.io/github/issues/RiyadhUddin/portfolio?color=important)
![Open Pull Requests](https://img.shields.io/github/issues-pr/RiyadhUddin/portfolio?color=yellowgreen)
![License](https://img.shields.io/github/license/RiyadhUddin/portfolio)

</div>

A high performance and mobile first hugo template for personal portfolio and blog

### Credit

I spent an amount of effort building this template. It's always disheartening whenever I find that someone use this template without giving me credit. Please, give me proper credit in footer.

### Demo

- [Live demo V1](https://portfolio-1.netlify.app)
- [Live demo V2](https://portfolio-2.netlify.app)
- [Live demo V3 (latest)](https://portfolio.netlify.app)
- [Github pages demo](https://RiyadhUddin.github.io/)

## Requirements

- Hugo Version 0.68.0 or higher

## How to use this template

- [portfolio](#portfolio)
    - [Credit](#credit)
    - [Demo](#demo)
  - [Requirements](#requirements)
  - [How to use this template](#how-to-use-this-template)
    - [Hugo theme format](#hugo-theme-format)
    - [Local Development](#local-development)
    - [Direct deployment using netlify](#direct-deployment-using-netlify)
    - [Direct deployment using Github Pages and action](#direct-deployment-using-github-pages-and-action)
  - [Deployment](#deployment)
  - [Issues](#issues)
  - [Contributing](#contributing)
  - [License](#license)
  - [🤝 Support](#-support)

### Hugo theme format

- Install Hugo and create a site using `hugo new site my-site -f=yaml`
- Clone this repo inside your themes folder and create config.yaml (_I am not much aware about toml. So, I am using yaml format._) inside root folder and use one of these [v1config](https://github.com/RiyadhUddin/portfolio/blob/master/website/v1.yaml), [v2config](https://github.com/RiyadhUddin/portfolio/blob/master/website/v2.yaml), [v3config](https://github.com/RiyadhUddin/portfolio/blob/master/website/v3.yaml) as base template.

```
cd themes
git clone https://github.com/riyadhUddin/portfolio.git
```

- You should have the mentioned (_inside the config file_) images in static folder to use them.

### Local Development

- Install hugo and just clone this repo

```
git clone https://github.com/RiyadhUddin/portfolio.git
cd portfolio
```

- Now create config.yaml file in your root folder and use one of these [v1config](https://github.com/RiyadhUddin/portfolio/blob/master/website/v1.yaml), [v2config](https://github.com/RiyadhUddin/portfolio/blob/master/website/v2.yaml), [v3config](https://github.com/RiyadhUddin/portfolio/blob/master/website/v3.yaml) as base template.
- Run your site using `hugo serve` commend

### Direct deployment using netlify

- Fork this repo or create new repo using `use this template` button and connect repo to netlify.
- You can customize the config file, content and everything inside website folder. Netlify will automatically deploy your changes every time you modify the repo.

**[What is netlify?](https://www.netlify.com/about/)** An intuitive Git-based workflow and powerful serverless platform to build, deploy, and collaborate on web apps

### Direct deployment using Github Pages and action

- Fork this repo or create new repo using `use this template` button. Github action will generate all files and push to demo branch. Now, you have to connect your github pages to that `demo` branch. _No need to create demo branch. Github action will take care of it_
- You can customize the config file, content and everything inside website folder. Github action will automatically deploy your changes to demo branch every time you modify the repo.

## Deployment

Run `hugo`. It will generate a folder called public. You can use the files inside public folder for deployment. You should delete the public folder for each time when you are using `hugo` commend.

## Issues

If you have a question, please [open an issue](https://github.com/RiyadhUddin/portfolio/issues) for help and to help those who come after you. The more information you can provide, the better!

## Contributing

Contributions, issues, and feature requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

Licensed under [MIT](LICENSE)

## 🤝 Support

Give a ⭐️ if you like this project!

<a href="https://www.buymeacoffee.com/RiyadhUddin" target="_blank" rel="noopener"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="40" width="145" alt="Buy Me A Coffee"></a>
