# Northern x Fanshawe Shopify Course

## Prerequisites
- Bash CLI
- [Docker](https://docs.docker.com/install/)

## Creating a New Theme

To start a new theme, clone this repository and remove the `.git` folder by running the following:

```console
$ git clone https://github.com/northernco/fanshawe-shopify-course.git <theme_name>
$ cd <theme_name>
$ rm -rf .git
```

Create a new repository and add this folder.

## Creating a New Theme

In the project, run the following to create a new theme using Shopify's Theme Kit:

```console
$ chmod +x theme
$ ./theme new --password=[your-password] --store=[your-store.myshopify.com] --name=[theme name]
```

Full instructions can be found [[here]](https://shopify.github.io/themekit/#get-api-access).

## Using Theme Kit

Theme Kit can be run using the `theme` script in the project's root directory. A full list of commands can be found [[here]](https://shopify.github.io/themekit/commands/).
