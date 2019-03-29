play a youtube video from vlc via [youtube-dl].

[youtube-dl]: https://ytdl-org.github.io/youtube-dl/

### installation

```bash
$ git clone https://github.com/gnawhleinad/youtube.git
$ cd youtube
$ brew bundle
$ ln -s "$(pwd)/youtube" /usr/local/bin/youtube
```

### examples

```bash
$ youtube https://youtu.be/U4n5OEwBlMw
```

```bash
$ youtube --audio --loop https://youtu.be/wbewYT57_nc
```
