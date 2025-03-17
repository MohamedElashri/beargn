# Hugo BearGN

A green variant of the Hugo Bear Blog theme, customized for a nature-inspired look.

## About

BearGN is a fork of the Hugo Bear Blog theme with a green color scheme that emphasizes readability and a connection with nature. The theme maintains the original's minimalist approach while introducing a fresh, green aesthetic.

## Features

- Green color scheme for both light and dark modes
- Maintains the original Bear Blog's simplicity and speed
- Responsive design
- Dark mode support
- Clean typography

## Color Scheme

### Light Mode
- Background: Light mint (#d5ffd8)
- Text: Dark green (#084106)
- Links: Green (#080)
- Headings: Dark green (#007a00)
- Accent: Soft green (#98f29f)

### Dark Mode
- Background: Deep forest (#1b4624)
- Text: Light gray (#ddd)
- Links: Mint (#bce8c2)
- Headings: Light green (#72d17a)
- Accent: Forest green (#335e36)

## Demo

For a current & working demo of this theme, please check out https://blog.melashri.net/ 🎯.

## Installation

If you already have a Hugo site on your machine, you can simply add this theme via

```
git submodule add https://github.com/MohamedElashri/beargn.git themes/beargn
```

## Content & structure

### Starting fresh

If you are starting fresh, simply initialize a new Hugo site and add this theme via

```
hugo new site mysite
```

Then, add this theme via

```
hugo new theme beargn
```

and then copy the contents of the the cloned to the `themes/beargn` directory. You might need to replace the `themes/beargn` directory. 


### Adding / editing content

#### Index-Page

The contents of the `index`-page may be changed by editing your `content/_index.md`-file.

#### Page

You can add **a new page** via running

```
hugo new my-new-page.md
```

#### Blog-Post

You can add **a new blog-post** via running

```
hugo new blog/my-new-post.md
```

#### Link

You can add **a new link** via running

```
hugo new links/my-new-link.md
```


#### Micro-Post

You can add **a new micro-post** via running

```
hugo new micro/my-new-micro.md
```

## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License) 

