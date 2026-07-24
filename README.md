# DoodleDev

A visual design and animation tool for the web. Draw on the canvas, animate on a timeline, and export production HTML / CSS / JS with no runtime dependencies.

Live at [doodledev.app](https://doodledev.app).

<p align="center">
  <img width="1920" height="1080" alt="doodleDev1" src="https://github.com/user-attachments/assets/4d7ea5dc-9cbf-4e20-9c40-3d2cc4385634" />
</p>

## Features

- Vector canvas: shapes, pen / bezier paths, text, groups, and a boolean shape builder
- Styling: fills, strokes, gradients, shadows, glow, lighting, blur, and noise
- Timeline keyframe animation with easing and playback
- Interactive states for hover and click without hand-writing the glue
- Export as a Web Component or a full HTML page
- Exported output is standalone. No React, Vue, or animation library required

<p align="center">
  <img width="1920" height="1080" alt="doodleDev2" src="https://github.com/user-attachments/assets/e5707f7c-366a-4c74-98a9-a436518d16c5" />
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

- [Mitch Boy Color](https://github.com/mitchivin/gameboy) - Game Boy Color emulator in the browser
- [MiPod](https://github.com/mitchivin/ipod) - click-wheel music player
- [MitchIvin XP](https://mitchivin.com/) - Windows XP portfolio desktop

## Credits

Built by **[Mitch Ivin](https://mitchivin.com/)**.

## License

Source stays private. The live product is at [doodledev.app](https://doodledev.app).
