## [HashSite](https://hashsite.github.io/hashsite/)

### Open a serverless website hosted on the BitTorrent network using WebTorrent

1. Make an [HTML](https://www.w3schools.com/html/default.asp) file named ```index.html```.
2. Create and host a torrent of it using [Instant.io](https://instant.io/), [WebTorrent Desktop](https://webtorrent.io/desktop/), or another WebTorrent compatible client.
3. Access it using its infohash or magnet link on https://hashsite.github.io/hashsite/ or with https://hashsite.github.io/hashsite/#infohash_or_magnet_link

#### To do:
- Look for index.html in the root directory only.
- If index.html doesn't exist, look for index.htm or index
- Enable a whole site to be hosted in one torrent.  Likely through blobs.
- Support the trackers specified in magnet links. This includes web hosts.
- Check infohash is hexadecimal.
- Support Base32 infohash.
- Create and host a live demo.
- Add some CSS.
- Enable dynamic websites using technologies such as blockchains, zeronet, namecoin, etc.
- When loading, change the <title> tag to the magnet link's dn parameter if it exists.
