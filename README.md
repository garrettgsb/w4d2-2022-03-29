### 01 - Vampires 1

* The DOM contains a node tree, much like the vampire tree from the weekend work
* A descendent of a node:
  * Is nested inside of its parent
    * ...which is, in turn, nested inside of its parent
      * ...which is nested inside of its parent, etc.
  * Has exactly one parent
  * May have descendents of its own
* The DOM allows us to manipulate nodes directly with Javascript

### 02 - Vampires 2

* This is how the DOM looks from the top-down: Enter at a particular node, and drill in layer-by-layer

### 03 - Vampire Builder

* Often, we have some data structure in Javascript (e.g. from a database query) that we want to represent on the page
* How can we turn a data structure into a web view?
* Let's start with an empty DOM, and a Javascript object representing our vampire tree, and build the page
* If there's time: Sloooow it down and _watch_ it build (`setTimeout` revisited!)

### 04 - Handling Clicks

* Use the provided `distanceFromRoot` function
* Run it for a particular vampire node when it's clicked
* Wait, something weird happens-- What is it?

--------

* **Side Quest:** This is getting to be alot of code stuffed into an HTML file
  * How do we move it into a Javascript file?
  * Something bad happens if we move the script file into the `<head>` element

### 05 - Vampire Editor

* Use the provided `findVampire` method to hard-code adding an offspring to one of the vampires
* It fails; why?
* Next, make _every_ vampire gain an offspring when clicked (with a hard-coded name)
* Next create a modal: Input, Create, Cancel
  * It opens when you click a vampire
  * It allows you to give the new vampire a name

### 06 - Vampire Clicks But It's jQuery

* Adding jQuery to a project
  * What's a CDN?
  * What's `min` (minification)?
* The `jQuery` function
  * The `$` alias
  * The three interfaces of the jQuery function:
    * `$('div')`
    * `$('<div>')`
    * `$(() => {})`

### 07 - Vampire Editor But It's jQuery

* jQuery sure is neat, eh?
* Let's do some more of it, if there's time
