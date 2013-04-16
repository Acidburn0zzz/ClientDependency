
![ClientDependency Framework](http://shazwazza.com/Content/Downloads/ClientDependencyLogo.png)

## What is *ClientDependency Framework (CDF)* ?

CDF is a framework for managing dependencies for JavaScript and CSS files in your web application (client files). It allows for each individual component in your web application to declare what CSS and JavaScript files they require instead of relying on a single master page to include all dependencies for all modules. 

## Out of the box you get

* MVC support - Any view engine
* Webforms support
* Runtime dependency resolution
* Pre-defined bundling
* Combining, compressing & minifying output
* Support for external/CDN files
* OutputCaching of the combined files
* Persisting the combined composite files for increased performance when applications restart or when the Cache expires
* Versioning the files ... great for ensuring your clients' browser cache is cleared!
* Prioritizing dependencies
* Pre-defined file paths - great for theming!
* Detecting script and styles that are not explicitly registered with CDF and have the output compressed
* Provider Model so you can choose how you would like your JS and CSS files rendered, combined, compressed & minified

## Nuget

	PM> Install-Package ClientDependency

	PM> Install-Package ClientDependency-Mvc

## [Documentation](https://github.com/Shandem/ClientDependency/wiki)

Click the link to see the documentation on how to get started and more advanced techniques


