# Sound &amp; Color

A web app that maps musical notes to color. Each note is assigned a hue from the color
wheel in **circle-of-fifths order**, so harmonically related notes sit next to each other
and chords blend into pleasing color combinations. Octave shifts both lightness and
saturation (with an optional per-octave hue tint) so the same note reads differently across
the keyboard.

## Features

- **Note → color mapping** driven by the circle of fifths, shown as a live color wheel.
- **Playable virtual piano** (mouse or computer keyboard `A W S E D F T G Y H U J K`) with
  real sound via the Web Audio API.
- **Polyphony + color blending** — hold multiple notes and see their colors combine.
  Blend modes: **Gradient** (horizontal, low pitch → high pitch), **Additive**, **Average**.
- **Labeled swatches** so simultaneous notes stay distinct even when their colors are close.
- **Octave tint** and **color-the-keys** toggles.
- **Chords tab** — a browsable gallery of every root across common chord types
  (major, minor, diminished, augmented, dominant 7, major 7, minor 7), each with its
  gradient. Click a chord to hear it.

## Live demo

https://m-tilleman.github.io/Sound-Color/

## Usage

Open `index.html` in any modern browser. No build step, no dependencies — it's a
single self-contained file.

## Roadmap

- **Listening mode** — analyze live audio (microphone or a file) and paint a color
  visualization from the pitches it hears.

## License

MIT
