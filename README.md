# DoodleDev

A visual design and animation tool for the web. Draw on the canvas, animate on a timeline, and export production HTML / CSS / JS with no runtime dependencies.

Live at [doodledev.app](https://doodledev.app).

<p align="center">
  <img src="https://github.com/user-attachments/assets/9fe6b17d-1382-4a07-b511-ae52c8221e2e" alt="DoodleDev Editor" />
</p>

## Features

- Vector canvas: shapes, pen / bezier paths, text, groups, and a boolean shape builder
- Styling: fills, strokes, gradients, shadows, glow, lighting, blur, and noise
- Timeline keyframe animation with easing and playback
- Interactive states for hover and click without hand-writing the glue
- Export as a Web Component or a full HTML page
- Exported output is standalone. No React, Vue, or animation library required

<p align="center">
  <img src="https://github.com/user-attachments/assets/90e044c0-4eb2-46a0-bfa4-38510f40a328" alt="DoodleDev Code Preview" />
</p>

## Export

Drop the export into any site and use the custom element:

```html
<script type="module" src="./doodle-export.js"></script>

<doodle-component></doodle-component>
```

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
