# emoji-metadata
Metadata for each emoji.
## Sample Entry
```json
{
    "emoji": "😺",
    "description": "happy cat face",
    "category": "Smileys & Emotion",
    "aliases": [
        "smile",
        "grinning cat",
        "open",
        "cats",
        "a happy cat emoji",
        "happy cat emoji",
        "animal",
        "face",
        "mouth",
        "smiley cat",
        "happy",
        "grinning",
        "cat"
    ],
    "unicode": "6.0",
    "ios": "6.0",
    "sentiment": "positive",
    "related": [
        "🐈",
        "🐱",
        "😺"
    ],
    "rgb": [
        197,
        160,
        67
    ]
}
```
## Fields
- `emoji`: (unsure what this field is used for)
- `description`: Official Unicode name for the emoji
- `category`: Unicode block for the emoji. Possible values:
  -  Smileys & Emotion
  -  People & Body
  -  Animals & Nature
  -  Food & Drink
  -  Travel & Places
  -  Activities
  -  Objects
  -  Symbols
  -  Flags
- `aliases`: Possible terms and alternative names someone might use to search for the emoji
- `unicode`: The version of Unicode that introduced the emoji
- `ios`: The version of iOS that introduced the emoji
- `sentiment`: The vibe of the emoji. These are plucked from iOS and are used to suggest appropriate emoji for any given user input. Possible values:
  -  positive
  -  low_energy
  -  anger
  -  neutral
  -  sad
  -  anxiety
- `related`: Emoji similar to this one
- `rgb`: The average color of the emoji, split into an array of red, green, blue values (respectively).

Data sourced and cherry-picked from:
- [me4502/Emojify](https://github.com/me4502/Emojify/blob/master/src/emojiMap.json)
- [ospfranco/sol](https://github.com/ospfranco/sol/blob/main/src/lib/emojis.ts)
- [unicode-org/cldr-json](https://github.com/unicode-org/cldr-json/blob/main/cldr-json/cldr-annotations-full/annotations/en/annotations.json)
