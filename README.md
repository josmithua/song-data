# song-data
Includes hymns from different hymn books in JSON format.

Hymn books currently include:
* Believers Hymn Book
* Sacred Songs for Singing Saints (also known as Songs of Thanksgiving & Praise)


## Format description
Each file is an array of song objects:

Song object properties:
* id (integer)
* title (string)
* author (string)
* meter (string)
* tuneName (string)
* verses (2D string array)
* chorus (string array)
* addedChorus (string array)

#### Example of a song object:

```
{
    "id": 1,
    "title": "Song title",
    "author": "Song author",
    "meter": "8.7.8.7.D.",
    "tuneName": "Deerhurst Lux Eoi Abbot's Leigh",
    "verses": [
      [
        "Verse 1, Line 1",
        "Verse 1, Line 2",
        "Verse 1, Line 3",
        "Verse 1, Line 4"
      ],
      [
        "Verse 2, Line 1",
        "Verse 2, Line 2",
        "Verse 2, Line 3",
        "Verse 2, Line 4"
      ]
    ],
    "chorus": [
      "Chorus, Line 1",
      "Chorus, Line 2"
    ],
    "addedChorus": [
      "Added chorus, Line 1",
      "Added chorus, Line 2"
    ]
  }
  ```


