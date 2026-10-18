# Truly music

Freely licensed recordings played by [Truly](https://github.com/hashtagRR/Truly), a free, open source wellbeing companion.

Every piece is a public domain work that was used in music therapy trials, as recorded in MCUD 1.0 (Du et al., 2026). Truly builds gentle paths through these pieces, starting close to how a person feels and moving a little at a time towards calmer or brighter.

The files are served with GitHub Pages from the same site as the app, so listening involves no streaming service.

## Contents

| Path | Contents |
|---|---|
| `audio/` | The recordings, 96 kbps MP3 |
| `tracks.json` | Title, composer, performer, licence, source, and the valence, arousal and tempo averaged from the MCUD entries each recording stands for |
| `CREDITS.md` | Attribution for every recording |

These files are produced by `music/prepare_audio.py` in the Truly repository from the list in `music/recordings.json`.

## Licences

Each recording keeps its own licence, listed in [CREDITS.md](CREDITS.md): public domain, CC0, CC BY or CC BY-SA. The recordings were converted to MP3 and their loudness was evened out; nothing else was changed. The valence, arousal and tempo values in `tracks.json` come from MCUD 1.0, licensed under CC BY 4.0, and `tracks.json` is shared under the same licence.

## Reference

Du, J., Song, J., Xu, Z., Fang, Y., Zhang, Y., Bi, C., Zheng, X., and Shen, B. (2026). MCUD 1.0: A clinical music usage data resource for personalized music therapy. *Scientific Data*. [doi:10.1038/s41597-026-07978-7](https://doi.org/10.1038/s41597-026-07978-7)
