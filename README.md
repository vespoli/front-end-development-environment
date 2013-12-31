front-end-development-environment
=================================

## Front End Development Environment Setup

This document serves as a list of the stuff you will need to set up a front end development environment to support most front end projects I develop. I plan to extend this to include a skeleton starter project. 

This setup is specific to mac users.

### Homebrew
This is a "package-manager" like utility for easily installing things on a mac

    ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"

http://brew.sh/

### git

    brew update
    brew install git
    git config --global user.name "Your Name"
    git config --global user.email "your@email.com"

### Xcode + command line tools
Command line tools are needed for various command line utilities as well as a dependancy for some of the other tools

https://developer.apple.com/xcode/



### Editor
Pick an editor that will allow you to easily see the level of indention. This will be very important for developing JADE templates. Sublime Text text is a great choice:

http://www.sublimetext.com/

### CodeKit
CodeKit is used for building the front end portion of the project as well as provides other useful services such as syntax checking and image optimization.
The CodeKit config file is part of project repository and located at the project root. The folder can be dragged into codekit to create a new project. 

*Note: You will need to use the actual compass executable, not CodeKit's. (CodeKit > Preferences > Other Tools > Compass > Advanced Compiler Settings > Use the Compass executable at this path:. Set it to your compass directory which is probably /usr/bin/compass)*

http://incident57.com/codekit/

### SASS

    gem install sass


### Compass
Sass mixin library

    gem update --system
    gem install compass


[http://compass-style.org/install/]: http://compass-style.org/install/

### Breakpoint
Media query mixin

    gem install breakpoint

http://breakpoint-sass.com/

### MAMP
Easy host configuration. The free version should be fine but not as nice as pro which allows you to configure multiple hosts.

http://www.mamp.info/en/index.html

