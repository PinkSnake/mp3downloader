  mp3downloader
=================

### Table of contents

 * [Download all mp3 from Youtube Playlist](#Download-all-mp3-from-Youtube-Playlist)
 * [Download mp3 from string](#Download-mp3-from-string)
 * [Download mp3 from file (string)](#Download-mp3-from-file-(string))
 * [Download mp3 from file (youtube URL)](Download-mp3-from-file-(youtube-URL))
 * [Rename Tracks with AcoustID database](Rename-Tracks-with-AcoustID-database)

### Download all mp3 from Youtube Playlist

```sh
./mp3downloader.sh -s playlist -u "https://www.youtube.com/playlist?list=<ID>"
```

### Download mp3 from string

```sh
./mp3downloader.sh -s direct balgue de toto
```

### Download mp3 from file (string)

```sh
./mp3downloader.sh -s tracklist -p playlistTrack.txt
```

### Download mp3 from file (youtube URL)

```sh
./mp3downloader.sh -s youtube -p playlistYoutube.txt
```

### Rename Tracks with AcoustID database

```sh
./mp3downloader.sh -r ./playlistYoutube
```

### Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request and enjoy!

### Contributors

Check out all the awesome [contributors](https://github.com/PinkSnake/mp3downloader/graphs/contributors).
