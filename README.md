# JS Parallax Effect

![1](https://github.com/abdul-1432/js-1_Parallax_Effect-1/assets/124916666/5dbdd39c-a741-4f4c-9bc5-29052415fcf1)

The JS Parallax Effect is a simple JavaScript library that allows you to create captivating parallax scrolling effects on your website. Parallax scrolling adds depth and visual interest to your web pages by moving elements at different speeds as the user scrolls, creating an illusion of depth.

## Features

- Lightweight and easy to use.
- Smooth and natural parallax scrolling.
- Customizable parallax layers and speeds.
- Works across modern web browsers.
- Mobile-friendly and responsive design.

## Getting Started

### Installation

You can include the JS Parallax library in your project by either downloading it manually and adding it to your project directory, or by using a package manager like npm:

```bash
npm install js-parallax-effect
```

### Usage

1. Add the `js-parallax.js` file to your HTML document:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Your other head content here -->
  <script src="path/to/js-parallax.js"></script>
</head>
<body>
  <!-- Your website content here -->
</body>
</html>
```

2. Define the parallax layers and their speed within your HTML markup using the `data-parallax` attribute:

```html
<div data-parallax="0.5"> <!-- Add the data-parallax attribute to the element with a value between -1 and 1 -->
  <!-- Content of the first parallax layer -->
</div>
<div data-parallax="0.8">
  <!-- Content of the second parallax layer -->
</div>
```

3. Initialize the parallax effect in your JavaScript:

```html
<script>
  document.addEventListener("DOMContentLoaded", function() {
    new JSParallax();
  });
</script>
```

That's it! You've now added the parallax effect to your website.

## Customization

You can further customize the parallax effect by passing an options object to the `JSParallax` constructor:

```javascript
document.addEventListener("DOMContentLoaded", function() {
  new JSParallax({
    speed: 0.5, // The default speed for all parallax layers (can be overridden individually).
    minSpeed: 0.1, // The minimum speed for any parallax layer.
    maxSpeed: 1, // The maximum speed for any parallax layer.
    debounce: 10, // The debounce time in milliseconds for handling scroll events.
    element: window, // The element to which the parallax effect will be applied (usually window).
  });
});
```

## Compatibility

The JS Parallax Effect library is compatible with modern web browsers, including but not limited to:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

## Contributing

Contributions to this project are welcome. Feel free to open issues for bug reports or new feature suggestions. If you want to contribute code, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Thanks to the open-source community for their contributions and inspiration.

---

Happy parallaxing! If you have any questions or need assistance, don't hesitate to reach out. Enjoy the captivating parallax effect on your website!
