# lyrics

Open time-synced lyrics (LRC) database.

## Lyrics Format

[Simple LRC format][1] with the following required ID tags:

```lrc
[ti:Title]
[ar:Artist]
[al:Album]
```

## Structure

LRC files are stored under [lyrics](https://github.com/lujjjh/lyrics/tree/main/lyrics).

The full path of an LRC is `/lyrics/${artist[0]}/${artist}/${title}.lrc`. `${artist[0]}` indicates the first character of the artist.

All the artists and titles are in lower cases.

For example, a song named **Lemon Tree** sung by **Fool's Garden** is put under `/lyrics/f/fool's garden/lemon tree.lrc`.

## Who are using this database?

- [lyrics-api.lujjjh.com](https://github.com/lujjjh/lyrics-api), which is used by [iTunes Desktop Lyrics for Windows](https://github.com/lujjjh/itunes-desktop-lyrics-windows)

[1]: https://en.wikipedia.org/wiki/LRC_(file_format)#Simple_format
