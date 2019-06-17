## Studio Kalavati

This is the documentation page for the projects in the Studio Kalvati stable.

## Projects

### Sargam-spec

This is a Clojure specification to document Hindustani classical compositions in Bhatkhande notation format. It will also support serialization to (and from) JSON.

Compositions can have parts (e.g Sthyai, Antara and multiple Taans) as well as the Taal the composition is set in, or it can be saved with a single part.

For more info, head over to the Sargam-spec [readme](https://github.com/Studio-kalavati/sargam-spec).

### Bhatkhande notation 

This project is a re-frame utility that reads a composition stored in a the app-db and displays the composition in an HTML5 canvas. It contains utility methods to 

* setup an HTML canvas
* display separate parts of the composition
* configuration 

More info in the [project page](https://github.com/Studio-kalavati/bhatkhande-notation)


### Chaturpandit

This is a re-frame project that displays a form to validate sargam-spec-compliant inputs and then display them in a Bhatkhande notation canvas.

More info in the [project page](https://github.com/Studio-kalavati/chaturpandit)
