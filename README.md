<!--
The drawing is a grid 180 dots wide. A dot is sharp only where it spans a whole number of device pixels.
On a phone the README column is the viewport less 82 px, which does not give one, so the phone rows pin a
width that does: 300 px or 240 px on a 3x screen and 270 px on a 2x screen. Each min-width is the narrowest
viewport whose column holds that width.

The contrast rows serve the colours of GitHub's high-contrast themes to a system that asks for more contrast.

The first row of each colour scheme must stay first. For a visitor with a fixed GitHub theme, GitHub
replaces the media query of every row of that scheme, so the first row is used at every size.
-->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark) and (prefers-contrast: no-preference) and (min-width: 544px)" srcset="assets/night-sky-dark.svg">
    <source media="(prefers-color-scheme: dark) and (prefers-contrast: more)" srcset="assets/night-sky-dark-contrast.svg">
    <source media="(prefers-color-scheme: dark) and (resolution: 3dppx) and (min-width: 382px)" srcset="assets/night-sky-dark.svg" width="300">
    <source media="(prefers-color-scheme: dark) and (resolution: 3dppx) and (min-width: 322px)" srcset="assets/night-sky-dark.svg" width="240">
    <source media="(prefers-color-scheme: dark) and (resolution: 2dppx) and (min-width: 352px)" srcset="assets/night-sky-dark.svg" width="270">
    <source media="(prefers-color-scheme: dark)" srcset="assets/night-sky-dark.svg">
    <source media="(prefers-color-scheme: light) and (prefers-contrast: no-preference) and (min-width: 544px)" srcset="assets/night-sky-light.svg">
    <source media="(prefers-color-scheme: light) and (prefers-contrast: more)" srcset="assets/night-sky-light-contrast.svg">
    <source media="(prefers-color-scheme: light) and (resolution: 3dppx) and (min-width: 382px)" srcset="assets/night-sky-light.svg" width="300">
    <source media="(prefers-color-scheme: light) and (resolution: 3dppx) and (min-width: 322px)" srcset="assets/night-sky-light.svg" width="240">
    <source media="(prefers-color-scheme: light) and (resolution: 2dppx) and (min-width: 352px)" srcset="assets/night-sky-light.svg" width="270">
    <source media="(prefers-color-scheme: light)" srcset="assets/night-sky-light.svg">
    <img src="assets/night-sky-light.svg" width="720" alt="Dot drawing of a cat asleep on the Moon, with a crescent, a comet and a ringed planet among stars">
  </picture>
</div>
