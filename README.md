# Static service pages

This is a repository of static pages used in digital services developed by the Environment Agency and its partners.

These pages are intended for use when a service is down due to maintenance or technical issues.

## Viewing the pages

In order to view the pages they do need to be served by a web service. If you are using a Mac or a version of Linux you should have everything you need already installed.

### Starting the web server

Open a terminal and navigate to the root of the project. Then run;

```bash
python -m SimpleHTTPServer
```

or if you are running [Python 3](https://www.python.org/download/releases/3.0/)

```bash
python3 -m http.server
```

Open your browser and go to http://0.0.0.0:8000. You'll see the index page listing all the pages in the project. Simply click the link for page you wish to see.

## GOV.UK content

Nearly all the assets covering images, stylesheets and javascript were sourced from GDS templates. The front office used the compiled [plain html](http://alphagov.github.io/govuk_template/) version. The back office comes from the GOV.UK [admin template](https://github.com/alphagov/govuk_admin_template). There is no static version of the admin template so the assets were stripped from an app which uses the template.

As all content is currently static this means these sources will need to be checked periodically for updates, and this repo updated accordingly.

## Contributing to this project

Please read the [contribution guidelines](/CONTRIBUTING.md) before submitting a pull request.

All contributions should be submitted via a pull request.

## License

THIS INFORMATION IS LICENSED UNDER THE CONDITIONS OF THE OPEN GOVERNMENT LICENCE found at:

http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3

The following attribution statement MUST be cited in your products and applications when using this information.

> Contains public sector information licensed under the Open Government license v3

### About the license

The Open Government Licence (OGL) was developed by the Controller of Her Majesty's Stationery Office (HMSO) to enable information providers in the public sector to license the use and re-use of their information under a common open licence.

It is designed to encourage use and re-use of information freely and flexibly, with only a few conditions.
