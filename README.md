# xlime-polymer-elements

A library of [Web Components](http://webcomponents.org/) to present
and interact with [xLiMe](http://xlime.eu)
information.

See [documentation
page](http://xlime-eu.github.io/xlime-polymer-elements/components/xlime-polymer-elements/)
for a list of components along with their API and demos.

The web-components are implemented using [Polymer](http://polymer.io).

The API of the web-components rely on the availability of json
representations of the various xLiMe resources (e.g. tv programs,
social-media posts, news articles, knowledge base entities, text to
speech annotations, OCR annotations, subtitle annotations, etc.). Such
representations can be provided by the [xLiMe front-end
services](http://github.com/xlime-eu/xlime-frontend-services) project.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

Once this has all completed you can test the components on your local machine:

     polyserve -p 8081

This will generate a documentation page for all the components in this project,
start a server and publish the documentation and demos for all of the components.

