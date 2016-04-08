# mindsmash-angular-livetemplates
Angular related live templates for IntelliJ IDEA 

## Install

Check out where to [find your templates directory](https://www.jetbrains.com/idea/help/live-templates.html). Once you found it, `cd` into it and run `git clone https://github.com/mindsmash/mindsmash-angular-livetemplates .` You could also clone the directory to any other directory and add a symbolic link to `mindsmash.xml` in your templates folder.

After cloning the repository, IntelliJ IDEA needs to be restarted.

## List of Templates

### Angular
* **$directive** - Template for an angular directive with a separate controller.
* **$service** - Template for an angular service (actually its a factory, since we don't use services at all).

### Jasmine
* **$it** - Template for "it" blocks.
* **$define** - Template for "define" blocks with one nested "it" block.
* **$testC** - Template for tests of controllers.
* **$testD** - Template for tests of directives which contain a nested controller.
* **$testLink** - Template for tests of directives with a link function under test.
* **$testService** - Template for tests for angular services.
* **$testProvider** - Template for tests for angular provider (including a service part).
 
### ngDoc
* **$docD** - Creates an ngDoc comment block for directives.
* **$docS** - Creates an ngDoc comment block for services / providers.
* **$docF** - Creates an ngDoc comment block for methods/functions.
* **$docM** - Creates an ngDoc comment block for modules (overview).

