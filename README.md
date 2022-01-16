- Solution URL: (https://github.com/joud-s/Stats-preview-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

## -It was a challenge for me to fit the image one way was by adding on my img htm width:100% , but i replace it with css code background: url() to switch between the picturs

## -I still couldn't get the image to stay inside the div while resizing so I set a specific height and width

```html
<div class="main-img">
  <img
    width="100%"
    height="100%"
    src="./images/image-header-mobile.jpg"
    alt="main pictuer"
  />
</div>
```

```css
.wrapper .main-img {
  background: url(./images/image-header-mobile.jpg) no-repeat center/cover;
  height: 20rem;
}
.wrapper .main-img .overlay {
  background-color: hsla(277, 100%, 49%, 0.5);
  height: 100%;
}
```

## Author

- Frontend Mentor - [@yjoud-s](https://www.frontendmentor.io/profile/joud-s)
- Twitter - [@joudishaker](https://www.twitter.com/joudishaker)
