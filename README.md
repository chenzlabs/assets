# Assets

Assets (e.g,, models, images, data files, sounds) used in various A-Frame
examples and boilerplates.

These assets are hosted at `https://cdn.aframe.io/` with CORS enabled.

## Referencing an Asset

Find an asset you want to use. And prepend it with the `https://cdn.aframe.io/`
domain. For example, if you wanted `360-video-boilerplate/video/city.mp4`, you
would use `https://cdn.aframe.io/360-video-boilerplate/video/city.mp4`.

```html
<a-scene>
 <a-assets>
  <video id="cityVideo" src="https://cdn.aframe.io/360-video-boilerplate/video/city.mp4">
 </a-assets>
 <a-videopshere src="#cityVideo"></a-videosphere>
</a-scene>
```
