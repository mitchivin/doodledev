# DoodleDev

A visual design tool for the web. Draw on the canvas, add Interactions with keyframes or states, and export production HTML / CSS / JS with no runtime dependencies.

Live at [doodledev.app](https://doodledev.app).

<p align="center">
  <img src="https://github.com/user-attachments/assets/a4520428-8ac5-4b25-8c95-1ab7945afaa0" alt="DoodleDev Editor" />
</p>

## Features

- Vector canvas: shapes, pen / bezier paths, text, images, groups, and a boolean shape builder
- Styling: fills, strokes, gradients, shadows, glow, lighting, blur, and noise
- Interactions: keyframes with easing and playback, plus hover and click states
- Welcome presets (MI Boy Color, MiPod Classic) plus local `.doodle` File Open / Save
- Export as a Web Component or a full HTML page (optional ZIP when the design includes image assets)
- Exported output is standalone. No React, Vue, or animation library required

<p align="center">
  <img src="https://github.com/user-attachments/assets/562180c7-6007-4233-81a8-3c5fa46ccd26" alt="DoodleDev Code Preview" />
</p>

## Export

Drop the export into any site and use the custom element (default tag / file name):

```html
<script type="module" src="./doodledev-export.js"></script>

<doodledev-export></doodledev-export>
```

The widget id (and therefore the tag and filename) can be customized at export time.

## Stack

- Vanilla HTML / CSS / JavaScript
- Paper.js for boolean shape operations
- Custom export pipeline that ships only the interaction code your design uses

## Related

Handheld shells and UI pieces from DoodleDev show up in:

- [MI Boy Color](https://builds.doodledev.app/#/miboy) - Game Boy Color emulator in the browser
- [MiPod Classic](https://builds.doodledev.app/#/mipod) - click-wheel music player
- [MitchIvin XP](https://mitchivin.com/) - Windows XP portfolio desktop

## Credits

Built by **[Mitch Ivin](https://mitchivin.com/)**.

## License

Source stays private. The live product is at [doodledev.app](https://doodledev.app).
