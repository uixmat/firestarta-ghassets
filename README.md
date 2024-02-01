# Firestarta Assets
> Small repo of images for giuthub readme graphics

Below is a bunch of ways to manipulate images in your repositories using the [Firestarta](https://firestarta.dev) brand identity.


### Image width
Set the max image width using the `width` property on your `<img>` tag.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/logo-dark.png">
  <img alt="Firestarta.dev" src="./assets/logo-light.png" width="200" align="ce">
</picture>

> `200px width`

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/logo-dark.png">
  <img alt="Firestarta.dev" src="./assets/logo-light.png" width="200" align="ce">
</picture>
```
