# Codelab
Boilerplate code to quickly setup a Google codelab. Full documentation by Google can be found [here](https://googlecodelabs.github.io/codelab-components/components/codelab-components/#google-codelab).

## Installation
Make sure you have [bower.io](https://bower.io) installed.
  1. After pulling this repository do ```bower install```. Bower will now install Polymer and google codelab-components.
  2. Run the index.html with any HTTP(S) server.
  
## Usage
### google-codelab
```<google-codelab>``` is the root element of the file. Only one ```<google-codelab>``` should be used. ```<google-codelab>``` can have several attributes. These are described in the official Google documentation.
### google-codelab-step
```<google-codelab-step>``` is nested within ```<google-codelab>```. Every ```<google-codelab-step>``` will be seen as a step in the codelab.
```<google-codelab-step>``` must have at least the following attributes:
  * ```label``` The title of the step
  * ```step``` Number ordening of the steps
  * ```duration``` The duration of the step in minutes

Specify all HTML you want to see within the related ```<google-codelab-step>```
