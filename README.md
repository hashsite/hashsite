## [HashSite](https://hashsite.github.io/hashsite/)

### [Live Demo](https://hashsite.github.io/hashsite/#magnet:?xt=urn:btih:ac68392d0cb90b37583805eb4a638a41995a9ec2&dn=index.html&tr=udp%3A%2F%2Fexplodie.org%3A6969&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969&tr=udp%3A%2F%2Ftracker.empire-js.us%3A1337&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337&tr=wss%3A%2F%2Ftracker.btorrent.xyz&tr=wss%3A%2F%2Ftracker.fastcast.nz&tr=wss%3A%2F%2Ftracker.openwebtorrent.com)

### Open a serverless website hosted on the BitTorrent network using WebTorrent

1. Make an [HTML](https://www.w3schools.com/html/default.asp) file named ```index.html```
2. Create and host a torrent of it using [Instant.io](https://instant.io/), [WebTorrent Desktop](https://webtorrent.io/desktop/), or another WebTorrent compatible client.
3. Access it using its infohash or magnet link on https://hashsite.github.io/hashsite/ or with https://hashsite.github.io/hashsite/#infohash_or_magnet_link

#### To do:
- Enable a whole site to be hosted in one torrent.
- Check infohash is hexadecimal.
- Support Base32 infohash.
- Add some CSS.
- Enable dynamic websites using technologies such as blockchains, zeronet, namecoin, etc.
- When loading, change the <title> tag to the magnet link's dn parameter if it exists.
- Add an option to add trackers manually after the download has begun.
