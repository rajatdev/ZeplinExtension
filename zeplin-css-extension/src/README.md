# zeplin-extension-style-kit

This package aims to provide an API to generate CSS-like style code snippets from the data exposed to Zeplin extensions. Even though target language or dialect can be different from CSS, preprocessors or CSS-in-JS solutions use the same property set and value format with CSS.

CSS properties and value formats are modeled in `zeplin-extension-style-kit` to form an intermediate representation. This representation is mostly language agnostic and can be used to develop an extension that generates similar style code snippets, e.g. Sass, React Native, styled-components.

## Models

- [Elements](./docs/elements.md)
  - [Layer](./docs/elements.md#layer)
  - [TextStyle](./docs/elements.md#textStyle)
- [Declarations](./docs/declarations.md)
  - [StyleDeclaration](./docs/declarations.md#styledeclaration)
  - [BackdropFilter](./docs/declarations.md#backdropfilter)
  - [BackgroundBlendMode](./docs/declarations.md#backgroundblendmode)
  - [BackgroundClip](./docs/declarations.md#backgroundclip)
  - [BackgroundColor](./docs/declarations.md#backgroundcolor)
  - [BackgroundImage](./docs/declarations.md#backgroundimage)
  - [BackgroundOrigin](./docs/declarations.md#backgroundorigin)
  - [Border](./docs/declarations.md#border)
  - [BorderImageSlice](./docs/declarations.md#borderimageslice)
  - [BorderImageSource](./docs/declarations.md#borderimagesource)
  - [BorderRadius](./docs/declarations.md#borderradius)
  - [BorderStyle](./docs/declarations.md#borderstyle)
  - [BorderWidth](./docs/declarations.md#borderwidth)
  - [Color](./docs/declarations.md#color)
  - [Filter](./docs/declarations.md#filter)
  - [FontSize](./docs/declarations.md#fontsize)
  - [FontStretch](./docs/declarations.md#fontstretch)
  - [FontStyle](./docs/declarations.md#fontstyle)
  - [FontWeight](./docs/declarations.md#fontweight)
  - [Height](./docs/declarations.md#height)
  - [LetterSpacing](./docs/declarations.md#letterspacing)
  - [LineHeight](./docs/declarations.md#lineheight)
  - [MixBlendMode](./docs/declarations.md#mixblendmode)
  - [Mixin](./docs/declarations.md#mixin)
  - [ObjectFit](./docs/declarations.md#objectfit)
  - [Opacity](./docs/declarations.md#opacity)
  - [Shadow](./docs/declarations.md#shadow)
  - [TextAlign](./docs/declarations.md#textalign)
  - [TextFillColor](./docs/declarations.md#textfillcolor)
  - [TextStroke](./docs/declarations.md#textstroke)
  - [Transform](./docs/declarations.md#transform)
  - [Width](./docs/declarations.md#width)
- [Values](./docs/values.md)
  - [StyleValue](./docs/values.md#styleValue)
  - [Angle](./docs/values.md#angle)
  - [Color](./docs/values.md#color)
  - [Gradient](./docs/values.md#gradient)
  - [Length](./docs/values.md#length)
  - [Percent](./docs/values.md#percent)
  - [Scalar](./docs/values.md#scalar)
- [RuleSet](./docs/ruleSet.md)