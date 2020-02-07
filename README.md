[Demo page](https://radogado.github.io/shadow-dom-demo/)

Safari 10, Chrome 53, Firefox 63 + iframe fallback

The #app element gets a Shadow DOM child, which can be accessed by app_container. Its style is unaffected by the page styles (except some * properties).

**shadow-style.css** applies only to the Shadow DOM element inside #app

**shadow-script.js** references the Shadow DOM by the app_container variable
