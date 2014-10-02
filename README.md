# Alertify.js Nuget Package #
JavaScript Alert/Notification System http://fabien-d.github.com/alertify.js/

## Installing ##
https://www.nuget.org/packages/alertify

    PM> install-package alertify

## Build ##
Install the grunt cli tools

`npm install -g grunt-cli`

Install the required modules

`npm install`

build the package to the `dist` folder

`grunt`

## ASP.Net Bundling & Minification ##

Main script

    bundles.Add(new ScriptBundle("~/bundles/alertify").Include("~/Scripts/alertify/alertify*"));

Styles for basic and dropzone themes

    bundles.Add(new StyleBundle("~/Content/alertify/bundle")Include("~/Content/alertify/alertify.core.css", "~/Content/alertify/alertify.bootstrap.css"));

## License ##
http://opensource.org/licenses/MIT
