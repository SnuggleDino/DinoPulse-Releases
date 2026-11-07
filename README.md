# DinoPulse

A music player for Windows with a built-in downloader. Your library lives on
your own machine, so it plays on a train, on a plane or in a basement flat, with
or without a connection. And it adapts to its listener, not the other way round.

## Download

**[Download the latest installer](https://github.com/SnuggleDino/DinoPulse-Releases/releases/latest/download/DinoPulse-amd64-installer.exe)**

It needs 64-bit Windows 10 or newer and administrator rights, and installs into
`Program Files\SnuggleDino\DinoPulse` with a shortcut in the start menu and on
the desktop. Every release below lists what changed.

- DinoPulse needs Microsoft's WebView2 runtime. Most Windows machines have it;
  where it is missing, the installer fetches it, which needs a connection.
- The programs the download screen works with are not part of the installer.
  The download screen names what is missing and fetches it on a click.

## Windows SmartScreen

The installer is not signed, so Windows may warn you the first time you start
it. To go ahead, choose "More info" and then "Run anyway".

## What it does

- **Plays your own library.** Point it at a folder and it reads tags and cover
  art from the files. The list is sortable, groupable by album or artist and
  searchable, with favourites and playlists.
- **Plays the way you expect.** Queue, shuffle, repeat, a mini player and media
  keys. It remembers where you stopped, and a tone control comes with presets.
- **Downloads into it.** A link, a search term or a playlist goes in, and a
  tagged file with cover art comes out, in the format and quality you choose.
  Downloading needs a connection, playing does not.
- **Matches, never copies.** Paste a Deezer playlist, album or track: DinoPulse
  searches online for each title and shows every hit next to the original
  before anything is fetched.
- **Handles your files.** Rename, copy, show in folder, or move to a trash that
  brings a track back with its favourite and its playlists.
- **Fits you.** A settings screen, a spectrum visualiser, seven colour schemes
  with a free accent colour, and every word in German and English.
- **Shows you around.** A short guide on first start, and "What is new" after
  every update.

## Licence

DinoPulse is free of charge. Its source code is not published, see `LICENSE`.

It carries GStreamer and other libraries under their own licences. Their texts
are in the `licenses` folder of the installation, and the GStreamer sources are
at https://gstreamer.freedesktop.org/src/.

https://snuggledino.dev
