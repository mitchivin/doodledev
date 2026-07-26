# DoodleDev

A visual design and animation tool for the web. Draw on the canvas, animate on a timeline, and export production HTML / CSS / JS with no runtime dependencies.

Live at [doodledev.app](https://doodledev.app).

<p align="center">
  <img src="https://github.com/user-attachments/assets/a4520428-8ac5-4b25-8c95-1ab7945afaa0" alt="DoodleDev Editor" />
</p>

## Features

- Vector canvas: shapes, pen / bezier paths, text, groups, and a boolean shape builder
- Styling: fills, strokes, gradients, shadows, glow, lighting, blur, and noise
- Timeline keyframe animation with easing and playback
- Interactive states for hover and click without hand-writing the glue
- Export as a Web Component or a full HTML page
- Exported output is standalone. No React, Vue, or animation library required

<p align="center">
  <img src="https://github.com/user-attachments/assets/562180c7-6007-4233-81a8-3c5fa46ccd26" alt="DoodleDev Code Preview" />
</p>

## Export

Drop the export into any site and use the custom element:

```html
<script type="module" src="./doodle-export.js"></script>

<doodle-component></doodle-component>
```

<p align="center">
  <img src="https://github.com/user-attachments/assets/fa01f135-d093-4692-9b0c-5504a549fde5" alt="MiPod Live Demo" />
</p>


## Stack

- Vanilla HTML / CSS / JavaScript
- Vite
- Custom export pipeline that ships only the animation code your design uses

## Related

Handheld shells and UI pieces from DoodleDev show up in:

- [MI Boy Color](https://github.com/mitchivin/miboy) - handheld shell
- [MiPod](https://github.com/mitchivin/mipod) - click-wheel shell
- [MitchIvin XP](https://mitchivin.com/) - Windows XP portfolio desktop

## Credits

Built by **[Mitch Ivin](https://mitchivin.com/)**.

## License

Source stays private. The live product is at [doodledev.app](https://doodledev.app).
