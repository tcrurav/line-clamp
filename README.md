# CSS Ellipsis for more than one line is called line-clamp

For more than one line textoverflow: ellipsis doesn't work. You must use line-clamp. This is an examnple using this CSS feature.

![screenshots](https://github.com/tcrurav/line-clamp/blob/master/screenshots/screenshot-01.png)

## Getting Started

This link explains very well the use of line-clamp:
https://stackoverflow.com/questions/3922739/limit-text-length-to-n-lines-using-css


## Prerequisites

You need a working environment with:
* [Git](https://git-scm.com) - You can install it from https://git-scm.com/downloads.

## General Installation instructions

The best option to start with this project is cloning it in your PC:

```
git clone https://github.com/tcrurav/line-clamp.git
```

Now you can just open the file index.html in your favourite browser. 

The most important part of this example is in the file styles.css:

```
.right-side div {
  height: 7em;
  text-align: left;

  overflow: hidden;
  display: -webkit-box;
  -webkit-line-clamp: 6;
  /* number of lines to show */
  line-clamp: 6;
  -webkit-box-orient: vertical;
}
```

Enjoy!!!


## Built With

* [Visual Studio Code](https://code.visualstudio.com/) - The Editor used in this project

## Acknowledgments

* https://stackoverflow.com/questions/3922739/limit-text-length-to-n-lines-using-css. This stackoverflow post saved my life.
* https://gist.github.com/PurpleBooth/109311bb0361f32d87a2. A very complete template for README.md files.
* https://undraw.co/search. An excellent place to find images for your site. The image used in this example was downloaded from 'undraw'.