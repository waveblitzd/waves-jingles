# wave's jingles

A personal repo of jingles for usage in [Cocoon](https://github.com/inssekt/CocoonFE).

## Game List

- Bomb Rush Cyberfunk
- ChuChu Rocket!
- Crazy Taxi
- Crazy Taxi 2
- Hatsune Miku: Project DIVA Mega Mix+
- Jet Set Radio
- Mario Strikers Charged
- Sonic Adventure
- Sonic Adventure 2
- Sonic and the Black Knight
- Sonic and the Secret Rings
- Sonic Colors
- Sonic Rush
- Sonic Unleashed
- Sonic x Shadow Generations
- Super Paper Mario
- Super Smash Bros. Brawl
- Super Smash Bros. Ultimate
- UNBEATABLE
  
## Quick Start

1. Use this repository template
2. Add your audio files (`.mp3`, `.ogg`, `.wav`) to the repo.
3. Update `index.json` to reference each file.
4. In Cocoon, go to **Settings → Library & Data → Jingle Repositories**
   and add your repo as `your-username/your-repo-name`.

## index.json Format

The `index.json` file at the root of the repository tells Cocoon what
jingles are available and where to find them.

```json
{
  "name": "My Jingle Pack",
  "entries": [
    {
      "game": "Super Fartio Throws",
      "file": "jingles/superfartiothrows.mp3"
    },
    {
      "game": "The Legend of Velma",
      "file": "jingles/The Legend of Velma.ogg"
    }
  ]
}
```

When creating a jingle pack, make sure you have the right to distribute
the audio files. Consider using:

- Original compositions
- Clips you created yourself
- Content with appropriate Creative Commons licenses
- Short, transformative fair-use clips (consult local laws)

Do **not** redistribute copyrighted music without permission.
