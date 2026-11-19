# VCS Design

"Student volunteers coding for our community"

St Andrews Volunteer Code Society (VCS) design language document.

| Section             | Last Updated |
| ------------------- | ------------ |
| [Ethos](#ethos)     | 2026-11-19   |
| [Colours](#colours) | 2026-08-27   |
| [Fonts](#fonts)     | 2026-08-27   |
| [Shapes](#shapes)   | 2026-08-27   |
| [Logo](#logo)       | 2026-08-27   |

## Ethos

The VCS is an open student society committed to creating positive change. As volunteers, we seek education, experience and growth, for ourselves and our community. Our design language must always reflect these core principles.

- **Openness.** Everyone must be able to access and understand our content.
- **Honesty.** The information we communicate must not be disguised in any way.
- **Positivity.** Our online presence and communications must not spread hatred.
- **Approachability.** We must demonstrate that we will work together and learn.

Accessibility is a core responsibility following from these principles. VCS design content must always meet modern [WCAG](https://www.w3.org/TR/WCAG21/) and [EAA](https://commission.europa.eu/strategy-and-policy/policies/justice-and-fundamental-rights/disability/european-accessibility-act-eaa_en) criteria.

### Design Concepts

The VCS uses certain design concepts to communicate our principles. VCS content should be consistent with these concepts and techniques. 

- **Visual content.** Design with clarity and accessibility in mind. Use *variance* and *imperfection* to convey our collaborative ideals. Ensure that icons and graphics conveying information meet 3:1 contrast on their background. Prefer soft, hand-drawn looking forms over sharp edges and precise geometry.

- **Text content.** Aim for a background contrast of at least 4.5:1 for all text. Write clearly and concisely, avoiding convoluted or long sentences. Ensure use of English is correct and understandable.
  - **Dates.** Follow an English format like "*Wednesday the 9th of September, 2026*." The name of the day of the week may be omitted.
  - **Times.** Follow a 12 hour format like "*2pm to 5pm*." For compatibility with screen readers, avoid using characters like dashes or hyphens to imply time ranges. 
    - An example of a badly formatted date and time is "*10-11am every day during the 2nd-21st of June*".
    - A better format would be "*Every day from the 2nd to the 21st of June, from 10am to 11am*."
  - **Slang.** Avoid using slang words that some readers may not understand. When in doubt, choose the more common word.

- **Audio content.** Avoid excessive noise in audio and ensure speech is clear and understandable. Keep speech to between 50 and 65 decibels (dB) and music under 60 dB. Never auto-play audio, except on platforms that implement their own setting to disable auto-play (e.g. Instagram).
  - **Music.** Do not use music with extreme volume, tempo or language. Prefer instrumental music over songs with lyrics. Ensure that copyright law is respected, but prefer good music over non-copyright music. Music content should be enjoyable to listen to.

- **Video content.** Ensure that visual standards for text and information contrast are met within videos. To mitigate risk of seizures, video content must not flash or strobe more than three times in 1 second. Motion graphics and animated text must ensure a consistent framerate, and it is recommended that this frame rate be at least 24 fps. Never auto-play video content.

## Colours

Colour is not a vehicle for meaning and should never be relied on as the only attribute conveying information. 

Traffic light colours cannot replace success/warning/error icons.

| Colour                                                                                                              | Token         | Hex      | HSL                |
| ------------------------------------------------------------------------------------------------------------------- | ------------- | -------- | ------------------ |
| <a href='#'><img valign='middle' alt='#fbf5e9' src='https://readme-swatches.vercel.app/fbf5e9?style=circle'/></a> | `paper`       | #fbf5e9 | hsl(40, 69%, 95%)  |
| <a href='#'><img valign='middle' alt='#26241f' src='https://readme-swatches.vercel.app/26241f?style=circle'/></a> | `ink`         | #26241f | hsl(43, 10%, 14%)  |
| <a href='#'><img valign='middle' alt='#5a252b' src='https://readme-swatches.vercel.app/5a252b?style=circle'/></a> | `maroon`      | #5a252b | hsl(353, 42%, 25%) |
| <a href='#'><img valign='middle' alt='#2d3d56' src='https://readme-swatches.vercel.app/2d3d56?style=circle'/></a> | `navy`        | #2d3d56 | hsl(217, 31%, 26%) |
| <a href='#'><img valign='middle' alt='#4a5230' src='https://readme-swatches.vercel.app/4a5230?style=circle'/></a> | `olive`       | #4a5230 | hsl(74, 26%, 25%)  |
| <a href='#'><img valign='middle' alt='#a84e58' src='https://readme-swatches.vercel.app/a84e58?style=circle'/></a> | `maroon-lift` | #a84e58 | hsl(353, 37%, 48%) |
| <a href='#'><img valign='middle' alt='#5f7ba0' src='https://readme-swatches.vercel.app/5f7ba0?style=circle'/></a> | `navy-lift`   | #5f7ba0 | hsl(214, 25%, 50%) |
| <a href='#'><img valign='middle' alt='#8a9857' src='https://readme-swatches.vercel.app/8a9857?style=circle'/></a> | `olive-lift`  | #8a9857 | hsl(73, 27%, 47%)  |
| <a href='#'><img valign='middle' alt='#c1503b' src='https://readme-swatches.vercel.app/c1503b?style=circle'/></a> | `brick`       | #c1503b | hsl(9, 53%, 49%)   |
| <a href='#'><img valign='middle' alt='#f2c044' src='https://readme-swatches.vercel.app/f2c044?style=circle'/></a> | `butter`      | #f2c044 | hsl(43, 87%, 61%)  |
| <a href='#'><img valign='middle' alt='#7a9a6b' src='https://readme-swatches.vercel.app/7a9a6b?style=circle'/></a> | `sage`        | #7a9a6b | hsl(101, 19%, 51%) |
| <a href='#'><img valign='middle' alt='#2f8c80' src='https://readme-swatches.vercel.app/2f8c80?style=circle'/></a> | `verdigris`   | #2f8c80 | hsl(172, 50%, 37%) |
| <a href='#'><img valign='middle' alt='#96602f' src='https://readme-swatches.vercel.app/96602f?style=circle'/></a> | `ochre`       | #96602f | hsl(29, 52%, 39%)  |
| <a href='#'><img valign='middle' alt='#efb3a8' src='https://readme-swatches.vercel.app/efb3a8?style=circle'/></a> | `blush`       | #efb3a8 | hsl(9, 69%, 80%)   |
| <a href='#'><img valign='middle' alt='#c6d5d0' src='https://readme-swatches.vercel.app/c6d5d0?style=circle'/></a> | `mist`        | #c6d5d0 | hsl(160, 15%, 81%) |
| <a href='#'><img valign='middle' alt='#c7b29f' src='https://readme-swatches.vercel.app/c7b29f?style=circle'/></a> | `sand`        | #c7b29f | hsl(28, 26%, 70%)  |
| <a href='#'><img valign='middle' alt='#748a98' src='https://readme-swatches.vercel.app/748a98?style=circle'/></a> | `slate`       | #748a98 | hsl(203, 15%, 53%) |

## Fonts

The VCS uses the [DejaVu Fonts](https://dejavu-fonts.github.io/) family.

| Font         | Used for                   |
| ------------ | -------------------------- |
| DejaVu Sans  | Any text                   |
| DejaVu Serif | Exceptional headings only  |
| DejaVu Mono  | Code, data and subheadings |

## Shapes

The VCS maintains a family of thematic shape imagery. These assets can be found within the `shapes/` directory of this repository.

Combination of these shapes should use SVG multiply blending to achieve an "overprint" effect. The overprint effect is a recognisable characteristic of the VCS design language and represents the intersection of diverse perspectives and ideas. The VCS [colours](#colours) are designed to create aesthetic tertiary colours when overprinted on each other.

| Name       | Meaning                         | File path(s)                              |
| ---------- | ------------------------------- | ----------------------------------------- |
| Arch       | Problem-solving, robustness     | `shapes/arch.svg`                         |
| Bird       | Freedom, ambition, nature       | `shapes/bird.svg`                         |
| Bow        | Organisation, bureaucracy       | `shapes/bow.svg`, `shapes/bow-simple.svg` |
| Cloud      | Imagination, kindness           | `shapes/cloud.svg`                        |
| Ellipse    | Commitment, critical thinking   | `shapes/ellipse.svg`                      |
| Grass      | Connection                      | `shapes/grass.svg`                        |
| Leaves     | Success, beauty                 | `shapes/leaves.svg`                       |
| Loop       | Dedication, fun                 | `shapes/loop.svg`                         |
| Page       | Education, stability            | `shapes/page.svg`                         |
| Rattle     | Childishness, silliness         | `shapes/rattle.svg`                       |
| Ring       | Openness, cohesion              | `shapes/ring.svg`                         |
| Rod        | Subtlety, strength              | `shapes/rod.svg`                          |
| Seed       | Creativity, youth, future       | `shapes/seed.svg`                         |
| Semicircle | Bravery, separation             | `shapes/semicircle.svg`                   |
| Spot       | Dependability, quietness        | `shapes/spot.svg`                         |
| Star       | Brilliance, innovation, respect | `shapes/star.svg`                         |
| Tilde      | Exploration, uncertainty        | `shapes/tilde.svg`                        |
| Zigzag     | Potential, faith                | `shapes/zigzag.svg`                       |

Don't take these meanings too seriously. The shapes can go wherever they look good.

## Logo

The VCS logo is a combination of the Star shape in `brick` overprinted on the Spot shape in `butter`. It represents the positive outcome of patient and collective work.

### Mark

The logo mark asset can be found at `logo/vcs-mark.svg` in this repository. A pre-generated 512x512 PNG is at `logo/vcs-mark.png`. PNGs at additional resolutions can be generated from the SVG at any time.

A pre-rendered logo with balanced padding on a `paper` background is at `logo/vcs-pfp.png`. This image should be used as the VCS's profile picture on social platforms such as Google, Instagram, etc.

A banner version is also provided at `logo/vcs-banner.png`. It shows the VCS logo with the text "VCS" in `ink` on the right.

### Lockup

The logo lockup asset can be found at `logo/vcs-lockup.svg` in this repository. It features the VCS logo with the text "VCS" to the right of it in `ink`.

Additional assets with the VCS's full name are at `logo/vcs-lockup-long-{black,white}.svg`. Instead of "VCS," they have "VOLUNTEER CODE SOCIETY" across two lines in `ink` or `paper`, with "VOLUNTEER" slightly larger on the first line, and "CODE SOCIETY" slightly smaller on the second line.

