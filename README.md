# sass-boilerplate

Sass partials updated to latest version of Sass.

Due to the introduction of Sass Modules in **2019**, there are several rules and common used features that are becoming deprecated.


## Installation:

Use terminal to install the latest version of sass into your system. [https://sass-lang.com/install](https://sass-lang.com/install)

I used:
```
brew install sass/sass/sass
```

Note: I had to remove a previous version of sass from my system after installing it due to conflicting files
```
rm '/usr/local/bin/sass'
```

## Compilation options:

### Terminal: 
```
sass -w --style=compressed [scss file name]:[css file name]
```

### VSCode extension: 
[https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass)

## Resources

[https://css-tricks.com/introducing-sass-modules/](https://css-tricks.com/introducing-sass-modules/)
[https://sass-lang.com/documentation](https://sass-lang.com/documentation)
[https://sass-lang.com/documentation/cli/dart-sass](https://sass-lang.com/documentation/cli/dart-sass)
