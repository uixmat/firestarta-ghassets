# Firestarta Assets
> Small repo of images for giuthub readme graphics

Below is a bunch of ways to manipulate images in your repositories using the [Firestarta](https://firestarta.dev) brand identity.


## Image width: `200px width`
Set the max image width using the `width` property on your `<img>` tag.

<table>
<tr>
<th align="left">
<img width="441" height="1">
<small>
Image
</small>
</th>
<th align="left">
<img width="441" height="1">
<small>
Code
</small>
</th>
</tr>
<tr>
<td>
<h3>
<picture>
<source media="(prefers-color-scheme: dark)" srcset="./assets/logo-dark.png">
<img alt="Firestarta.dev" src="./assets/logo-light.png" width="200">
</picture>
</h3>
</td>
<td>

```html
<img alt="alt" src="./image.png" width="200">
```
</td>
</tr>

</table>
