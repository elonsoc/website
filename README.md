# Elon Society of Computing's Home on the Web

This repository contains ESC's website!

We're using Hugo as our [Static Site Generator](https://www.cloudflare.com/learning/performance/static-site-generator/).

To make updates to the site or add a new post, we leverage pull requests to integrate your changes. 

You can learn more about pull requests from this [github article](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).

### Getting Started
1. Make sure you have `hugo` installed. If you don't, follow this guide to [install hugo](https://gohugo.io/getting-started/installing#quick-install)

2. Clone this repository using Git into your folder of choice:
    ```
    git clone https://github.com/elonsoc/website.git
    ```
and now you're ready to make your changes!


### Start Developing

Navigate into your new site’s directory and start it up.

```shell
cd website/
hugo serve -D
```

Your site is now running at https://localhost:1313!

`hugo serve` starts a new webserver, builds the site, and begins the live reloading feature for faster iterative development.
When you make a change to the website, `hugo` will automatically detect the change, rebuild the site, and reload your webpage!
The `-D` option flag includes drafts, in case you were writing a new post.

### How to Contribute


### Building the Site for Github Pages
Building for Github Pages is pretty simple.
Simply commit your changes and push them!
If your pull request is accepted for integration, our repository will automatically build the hugo site through a [github action](https://github.com/features/actions). You can see the `yaml` file that set this automation up [here](https://github.com/elonsoc/website/blob/master/.github/workflows/gh-pages.yml).

After that, Github will propagate your changes to the world!

### Learn More About Hugo

<!-- - [Documentation](https://www.gatsbyjs.com/docs/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter)

- [Tutorials](https://www.gatsbyjs.com/tutorial/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter)

- [Guides](https://www.gatsbyjs.com/tutorial/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter)

- [API Reference](https://www.gatsbyjs.com/docs/api-reference/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter)

- [Plugin Library](https://www.gatsbyjs.com/plugins?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter)

- [Cheat Sheet](https://www.gatsbyjs.com/docs/cheat-sheet/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter) -->