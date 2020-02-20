## [HashSite](https://hashsite.github.io/hashsite/)

### Open a serverless website hosted on the BitTorrent network using WebTorrent

1. Make an [HTML](https://www.w3schools.com/html/default.asp) file named ```index.html```
2. Create and host a torrent of it using [Instant.io](https://instant.io/), [WebTorrent Desktop](https://webtorrent.io/desktop/), or another WebTorrent compatible client.
3. Access it using its infohash or magnet link on https://hashsite.github.io/hashsite/ or with https://hashsite.github.io/hashsite/#infohash_or_magnet_link

#### To do:
- Enable a whole site to be hosted in one torrent.
- Enable dynamic websites using technologies such as blockchains, zeronet, namecoin, etc.
- When loading, change the <title> tag to the magnet link's dn parameter if it exists.
- Add an option to add trackers manually after the initial download has begun.
- Check infohash is hexadecimal.
- Support Base32 infohash.
- Add some CSS.
- Live demo.
