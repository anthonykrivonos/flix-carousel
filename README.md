# Flix Carousel

*Flix Carousel* is a **pure-CSS** animated carousel modeled after Netflix's browse screen! It's less than 100 lines of source code and can be imported by CDN or by downloading this repository.

See *Flix Carousel* in action.

![Flix Carousel Example](https://media.giphy.com/media/8Bl3HslMi1d8DQvLLb/giphy.gif)

```
<div class="carousel">
    <div class="carousel-row">
          <div class="carousel-tile" style="background: #46B1C9;"></div>
          <div class="carousel-tile" style="background: #84C0C6;"></div>
          <div class="carousel-tile" style="background: #9FB7B9;"></div>
          <div class="carousel-tile" style="background: #BCC1BA;"></div>
          <div class="carousel-tile" style="background: #F2E2D2;"></div>
    </div>
</div>
```

## Getting Started

### Installing

To install via CDN, add this to the bottom of your `<header>` tag.
```
TBA
```

To install manually, download this repository, add the contents to the root of your project, and link the source CSS at the bottom of your `<header>` tag.
```
<link href="src/carousel.css" rel="stylesheet">
```

End with an example of getting some data out of the system or using it for a little demo

## Overwriting Default Styling

Add the following to another CSS file linked to your project, or in a `<style>` tag within your HTML file.

### Changing Tile Height/Width
```
:root {
    --carousel-tile-spacing: ---px !important;
    --carousel-tile-width:   ---px !important;
}
```

### Changing Growth Factor
`<1:` Shrink
`1 :` Normal
`>1:` Grow
```
:root {
    --carousel-growth-factor: --- !important;
}
```
### Changing Fade Opacity
The fade opacity is the opacity of tiles that are not currently hovered, while another tile is currently hovered (value out of 1).
```
:root {
    --carousel-fade-opacity: --- !important;
}
```

### Changing Transition Speed
`X:`
`1` for 1s transition
`2` for 0.5s transition
`3` for 0.3s transition
```
.carousel-tile {
      transition: var(--carousel-transition-X) !important;
}
.carousel-row {
      transition: var(--carousel-transition-X) !important;
}
```

## Inspired By

* [Pure-CSS Netflix Show Carousel](https://codepen.io/joshhunt/pen/LVQZRa) - By Josh Hunt

## Authors

* **Anthony Krivonos** - *Initial work* - [Portfolio](https://anthonykrivonos.com)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Josh Hunt
* Vicki Shao for all the support and flames! 🔥