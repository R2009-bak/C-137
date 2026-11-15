# The Ones Who Went First

Interactive web comics about three NASA spacecraft — **Surveyor 3** (the Moon), **Pioneer 10** (Jupiter and beyond) and the **Kepler** space telescope (orbiting the Sun). Made for the NASA Space Apps Challenge 2026.

Open `index.html`, pick a world, meet the spacecraft, and read its comic (press SPACE to reveal panels).

## Use of SI (Super Intelligence) tools

- **Images:** all comic panels, covers and the three spacecraft cut-outs (`img/`, `kimg/`, `pimg/`, `craft-*.png`) were generated with an SI image-generation tool from prompts written for each panel. Every image carries a visible "SI-generated" watermark. NASA logos and flags that appeared in some generated images were removed.
- **Code:** the HTML, CSS and JavaScript, including the WebGL shaders that render the Moon, Jupiter and the Sun, were written with the help of Claude (Anthropic), a large language model, based on our team's scenarios and design decisions.
- **Text:** English captions and card texts were drafted with the help of Claude and checked against the NASA sources below.
- **Not SI-generated:** the story scenarios and the choice of missions (our team); the mission facts (NASA sources).

## Sources

- NASA Science — Surveyor 3: https://science.nasa.gov/mission/surveyor-3/
- NASA Science — Pioneer 10: https://science.nasa.gov/mission/pioneer-10/
- NASA Science — Kepler / K2: https://science.nasa.gov/mission/kepler/
- NASA — Kepler-186f press release: https://www.nasa.gov/news-release/nasas-kepler-telescope-discovers-first-earth-size-planet-in-habitable-zone
- NASA Science — Kepler reaction wheels: https://science.nasa.gov/?p=199178
- The Planetary Society — The Pioneer Plaque: https://www.planetary.org/articles/0120-the-pioneer-plaque-science-as-a-universal-language

Schematic diagrams (Pioneer 10 radiation graph, magnetic field) are illustrations, not measured data. The Kepler-186f image is an artist's concept and the alien epilogue is fiction; both are labeled on the pages.

Fonts: Bangers, Comic Neue, Unbounded, Manrope (Google Fonts, SIL Open Font License).
