# miraga-prompt-kit

A small, curated kit of prompt templates and a JSON schema for AI image and video generation. Copy a template, fill in the blanks, and get more consistent results across models.

## What's inside

| Path | What it is |
|---|---|
| `prompts/image-basics.md` | Image prompt structure, shot types, lighting, aspect ratios, style tokens |
| `prompts/video-shorts.md` | Templates for 5–15 s short-form clips: camera moves, pacing, multi-shot beats |
| `schema/prompt-pack.schema.json` | JSON Schema (draft 2020-12) for sharing prompt packs |
| `examples/sample-pack.json` | A valid example pack |

## How to use

1. Pick a template from `prompts/`.
2. Replace the `{placeholders}`. Delete any you don't need, since shorter prompts often work better.
3. Add one or two style tokens. Don't stack ten.
4. Iterate: change **one** variable per run (lens, light, or style) so you can tell what helped.

### Quick example

Template:
```
{subject}, {action}, {shot_type}, {lighting}, {style_tokens}, {aspect_ratio}
```
Filled in:
```
an elderly fisherman mending a net, seated on a wooden dock, medium close-up,
soft overcast morning light, 35mm film, muted teal palette, 4:5
```

## Prompt packs (JSON)

To store or share prompts in a machine-readable form, use the schema:

```bash
npx ajv-cli validate --spec=draft2020 -s schema/prompt-pack.schema.json -d examples/sample-pack.json
```

## Works with Miraga

These templates are model-agnostic. We use them every day in [Miraga](https://vmiraga.com), so you can try them there if you want somewhere to start.

## Contributing

PRs with tested templates are welcome. Include the model you tested on and one sentence on why the template works.

## License

MIT. See [LICENSE](LICENSE).
