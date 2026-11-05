# Video shorts templates (5–15 s)

## Core structure
```
{shot_type} of {subject} {action}, {camera_movement}, {environment}, {lighting}, {style}, {duration}, {aspect_ratio}
```
Describe **one clear action** per shot. Video models struggle with several events in one clip.

## Camera movements
| Token | Effect |
|---|---|
| static locked-off shot | calm, product focus |
| slow push-in | builds attention |
| pull-back reveal | shows the context at the end |
| orbit / 360 around subject | product hero shots |
| tracking shot following {subject} | energy, movement |
| handheld, slight shake | documentary, UGC feel |
| crane up | ending, scale |
| whip pan | transitions |

## Pacing guide
- **5 s**: one shot, one action
- **10 s**: 2 beats (setup → payoff)
- **15 s**: 3 beats (hook → body → ending)

## Templates

**Product hero (5 s, 9:16)**
```
slow orbit around {product} on a {surface}, soft studio light, subtle reflections, dark gradient background, commercial look, 5 seconds, 9:16
```
**Hook → payoff (10 s, 9:16)**
```
Shot 1 (0–4s): close-up of {person}'s hands {action}, static camera.
Shot 2 (4–10s): pull-back reveal of {result} in {environment}, warm light.
Style: {style}. Aspect 9:16.
```
**Atmospheric loop (5 s)**
```
static wide shot of {location}, {ambient motion: drifting fog / falling snow / city lights flickering}, seamless loop, {style}, 16:9
```
**Character moment (8 s)**
```
medium shot of {character} {emotion} as they {action}, slow push-in, {lighting}, shallow depth of field, cinematic, 8 seconds, 9:16
```
**Image-to-video**
```
animate this image: {what moves}, {camera_movement}, keep {what must stay the same} unchanged, subtle natural motion
```

## Tips
- Name what stays still: "background stays static".
- Avoid on-screen text in prompts, and add captions in editing instead.
- Generate at the target ratio. Cropping 16:9 to 9:16 loses the subject.
