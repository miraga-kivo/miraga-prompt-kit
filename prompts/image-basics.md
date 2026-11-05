# Image prompt basics

## Core structure
```
{subject}, {details}, {environment}, {shot_type}, {lens}, {lighting}, {style_tokens}, {aspect_ratio}
```
Order matters for most models, so put the subject first.

## Shot types
| Token | Use for |
|---|---|
| extreme close-up | texture, eyes, product details |
| close-up | faces, emotion |
| medium shot | person from the waist up, dialogue framing |
| full shot | whole body, outfits |
| wide shot / establishing shot | location, scale |
| overhead / flat lay | food, desk setups, products |
| low angle | power, monumentality |
| dutch angle | tension, unease |

## Lenses
- `24mm wide-angle`: interiors, dramatic perspective
- `35mm`: natural, documentary feel
- `50mm`: neutral, close to the human eye
- `85mm portrait, shallow depth of field`: flattering faces, creamy bokeh
- `macro lens`: tiny subjects

## Lighting
`golden hour backlight` · `soft overcast light` · `hard noon sun` · `rim light` · `neon signage glow` · `single softbox, dark background` · `window light from the left`

## Aspect ratios
| Ratio | Where |
|---|---|
| 1:1 | profile pictures, grid posts |
| 4:5 | Instagram feed |
| 9:16 | Stories, Reels, Shorts, TikTok |
| 16:9 | YouTube thumbnails, desktop |
| 3:2 | photographic prints |
| 21:9 | cinematic banners |

## Style tokens (use 1–3)
- Photo: `35mm film grain`, `Kodak Portra palette`, `editorial fashion photo`
- Illustration: `flat vector illustration`, `ink and watercolor`, `children's book gouache`
- 3D: `clay render`, `isometric 3D, soft shadows`, `product render on seamless backdrop`
- Mood: `muted palette`, `high contrast`, `pastel`, `moody low key`

## Templates

**Product shot**
```
{product} on {surface}, {props}, overhead flat lay, soft diffused light, clean {color} background, commercial product photography, 1:1
```
**Portrait**
```
portrait of {person description}, {expression}, close-up, 85mm, shallow depth of field, {lighting}, {style_token}, 4:5
```
**Scene / environment**
```
{location} at {time_of_day}, {weather}, wide establishing shot, {mood} atmosphere, {style_token}, 16:9
```
**Thumbnail**
```
{subject} reacting to {thing}, bold expression, medium close-up, bright rim light, saturated colors, empty space on the right for text, 16:9
```

## Negative prompt starter (if supported)
```
blurry, extra fingers, distorted hands, watermark, text artifacts, low resolution
```
