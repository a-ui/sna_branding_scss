# Antwerp branding variant

This project contains everything you need to make a variant of Antwerp's core branding.

## Development

### Prerequisites

In order to run this project and see all available components, you'll need to have [NodeJS](https://nodejs.org) and [Gulp](https://gulpjs.com) installed.

### Installing

Go to the root of this project and run the following command in your command line:

```
npm ci
```

### Local development

Run the following command in your command line:

```
npm start
```

You'll see an overview of all the core branding components in its original form/style. The best starting point to create a variant is the file `src/styles/main.scss`. In this file you will find a complete overview of all CSS custom properties that you can override to create your own theme. Feel free to divide the file into several subfiles, e.g. if you want to create extra (versions of) components. But always take into account their compatibility with the already existing React components.

If you are making custom versions of existing components, we encourage you to build them up via the existing CSS custom properties of that component. This will almost guarantee full compatibility with aforementioned React components.

The overview of all the core branding components is mostly created from templates that reside in your `node_modules` folder. To make adjustments or to add your own components you can directly change the root file `src/index.njk` (we use [Nunjucks](https://mozilla.github.io/nunjucks/) as templating language) or use the ready-made file `src/templates/custom.njk`.

### Building

Run the following command in your command line:

```
npm run build
```

## Contributing

Contact us via [branding@stad.antwerpen.be](mailto:branding@stad.antwerpen.be).

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/a-ui/sna_branding_scss/tags).

## Authors

* **Jeroen Collier** - *Art director, lead design*
* **Jasper Van Proeyen** - *Initial work, lead developer*

See also the list of [contributors](https://github.com/a-ui/sna_branding_scss/contributors) who participated in this project.

## License

This project is licensed under a modified version of the MIT license. See the [LICENSE.md](LICENSE.md) file for details.
