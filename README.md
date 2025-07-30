# emojicdn

## Basic usage

Append any emoji to the end of `emoji.hmt.ir` to get a PNG image:

```html
<img src="https://emoji.hmt.ir/🥳" />
```

## Emoji style

For more control, add the `style` query parameter to specify an emoji platform:

```html
<img src="https://emoji.hmt.ir/🥳?style=google" />
```

If no `style` is provided, the API defaults to `apple`.

Supported styles:

- `apple`
- `google`
- `facebook`
- `twitter`

## Implementation

- `emoji.json` from: https://github.com/iamcal/emoji-data/blob/master/emoji.json
