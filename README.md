# Firestarta Assets
> Small repo of images for giuthub readme graphics

Below is a bunch of ways to manipulate images in your repositories using the [Firestarta](https://firestarta.dev) brand identity.


## Image width: `200px width`
Set the max image width using the `width` property on your `<img>` tag.

<table>
<tr>
<th align="left">
<img width="441" height="1">
<p> 
<small>
Image
</small>
</p>
</th>
<th align="left">
<img width="441" height="1">
<p> 
<small>
Code
</small>
</p>
</th>
</tr>
<tr>
<td>
<picture>
<source media="(prefers-color-scheme: dark)" srcset="./assets/logo-dark.png">
<img alt="Firestarta.dev" src="./assets/logo-light.png" width="200">
</picture>
</td>
<td>

```
<img alt="alt" src="./image.png" width="200">
```
</td>
</tr>
</table>
