<!-- markdownlint-configure-file {
  "MD013": {
    "code_blocks": false,
    "tables": false
  },
  "MD033": false,
  "MD041": false
} -->

<div align="center">

# Archiveify

`archiveify` is a bash script that allows archiving music from Spotify.

[Dependencies](#dependencies) •
[Usage](#usage) •
[Limitations](#limitations)

</div>

## Dependencies
The script requires the following dependencies:

* [curl](https://www.curl.se)
* [flac](https://xiph.org/flac/)
* [jq](https://stedolan.github.io/jq/)

## Usage

The script requires only one argument:
* The Spotify link to the playlist (in the format `spotify:playlist:<id>` or `https://open.spotify.com/playlist/<id>`)

To run the script, navigate to the directory where it is saved and enter the following command in your terminal:

```
$ ./archiveify <spotify_link>
```
The downloaded FLAC files will be saved in a directory named after the playlist in the user's home directory.

## Limitations
The script uses an external API to search for the tracks and download the FLAC files. As such, the availability and quality of the files may vary depending on the API used.

## Disclaimer
This script is provided for educational purposes only. The use of this script may be against Spotify's terms of service and/or copyright laws. The user is responsible for ensuring that they have the necessary rights to download and use the files. The author of this script is not responsible for any misuse or damages caused by the use of this script.
