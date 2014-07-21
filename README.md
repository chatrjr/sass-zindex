# Zindex: A tiny Sass library for taming z-index. 

Zindex uses [the stepping method][CRJ Post], and my budding understanding of how the stack context works, to serve as a relatively painless tool for managing z-index. I'm not entirely sure it counts as a library, because it's so damn tiny.

The idea itself came from reading:

+ [Sassy Z-Index Management for Complex Layouts][JBSM]
+ [What No One Told You About Z-Index][PW]
+ [Handling z-index][CC]

## Getting Zindex Going

Before anything else, clone the repo into your project's Sass directory.

```bash
git clone https://github.com/chatrjr/sass-zindex.git
```

Or grab the tarball/zipball.

+ [Tarball][TB] 
+ [Zip][Z]

Next import Zindex into your project.

```scss
@import 'sass-zindex/zindex';
```

And you're good to go.

## Using Zindex

To get started using Zindex, [check out the example file][EX] in the repo. If live demos are you thing, [check out the pen with my test cases][CP].


[JBSM]: http://www.smashingmagazine.com/2014/06/12/sassy-z-index-management-for-complex-layouts/ "Sassy Z-Index Management for Complex Layouts"
[PW]: http://philipwalton.com/articles/what-no-one-told-you-about-z-index/ "What No One Told You About Z-Index"
[CC]: http://css-tricks.com/handling-z-index/ "Handling z-index"
[TB]: https://github.com/chatrjr/sass-zindex/tarball/master "Zindex Tarball"
[Z]: https://github.com/chatrjr/sass-zindex/zipball/master "Zindex Zip"
[EX]: https://github.com/chatrjr/sass-zindex/blob/master/zindex-example.scss "Zindex Usage Examples"
[CP]: http://codepen.io/chatrjr/pen/JrLIt "Zindex Test Cases"
