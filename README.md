# Handlebars Virtual Dom


### NONE OF THIS IS IMPLEMENTED YET!!

A Rust browser template rendering library

Requires Rust to be compiled to Webassembly or Javascript with Emscripten

### Benefits:
* No element declarations as macros or DSLs - templates in separate handlebars HTML file
* Type safety between templates and Rust code  
* Dynamic** template recompilation for development - preview changes instantly
* Multiple component declarations allowed in one file - convenient when having many small components
* Virtual dom diff computed in Rust - for faster rendering

__** Only changes to HTML (nothing inside "{{ }}") can be dynamically rerendered__