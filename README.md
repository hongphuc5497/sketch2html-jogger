# sketch2html-jogger

## File structure

```structure
  app
  |--css/
  |
  |--images
  |    |--congo.png
  |
  |--styles
  |    |--reset.css
  |    |--setting.css
  |    `--main.css
  |
  |--webfonts
  |
  |--index.html
  |
  `--README.md
```

## HTML tree

```html
  div.product
    div.product__header
      div.product__menu
        i.product__menu-icon
        span.product__menu-text
      h1.product__heading
      ul.tool
        li.tool__item * 3
          i

    div.product__nav
      ul.category
        li.category__item
          a.category__link

      div.social
        span.social__text
        ul.social__share
          li.social__share-item * 2
            a.social__share-link
              i

    div.product__slider
      ul.slider
        li.slider_item
          h2.slider__title
          div.slider__image

      ul.slider__arrow
```
