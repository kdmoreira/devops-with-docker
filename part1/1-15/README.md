`kdmoreira/youtube-dl` only downloads videos from Imgur.

## Usage:
Pull the image:
```console
docker pull kdmoreira/youtube-dl
```

In order to download videos to your current directory, run:
```console
docker run -d -v "$(pwd):/usr/src/app" kdmoreira/youtube-dl <imgur-url>
```

Running youtube-dl without passing a `<imgur-url>` will automatically download a cute "Hello!" video.
