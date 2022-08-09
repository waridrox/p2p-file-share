
# PeerShare

PeerShare is a file sharing app that allows users to transfer files between multiple devices. It uses torrent based web technologies and runs in the web browser. It supports instant file sharing with multiple devices at once.

PeerShare uses WebTorrent to transfer files between multiple devices, and WebSockets to create temporary rooms. Files shared via WebTorrent are peer-to-peer(as they use WebRTC internally) which means there is direct transfer between the sender and receiver without any intermediate server.


## Features

- No signup required.
- Supports one to many transfers.
- Works on almost all browsers that support WebRTC protocol.
- Cross platform and responsive.
- Easy to use, no app installation or dependency required.


## Comparision with 
![DATA TRANSFER PERFORMANCE OF BITTORRENT TRANSMISSION PROTOCOLS (NO OF PACKETS VS PROTOCOL)](https://user-images.githubusercontent.com/58583793/183577816-d37070df-3641-44e1-aac4-6fdd89e2cbe7.png)

![DATA TRANSFER PERFORMANCE OF BITTORRENT TRANSMISSION PROTOCOLS (BANDWIDTH VS PROTOCOL)](https://user-images.githubusercontent.com/58583793/183578053-fcaab0c4-3444-429a-91f7-14653c117dcd.png)

## Try it live!

- Head over to the website [here](https://p2p-file-share.herokuapp.com/).
- A random string will get appended to the above URL.
- Share the link of the page to the other peer over the same network.
- A connection will be established once the other peer opens the link.
- Start sharing files!


## Tech Stack

**Server:** Node, Express, SocketIO, WebTorrent

**Client:** HTML, CSS, JS, ejs


## References

- https://webtorrent.io/faq
- https://www.researchgate.net/figure/Total-number-of-packets-for-1MB-file-transfer_fig2_336175322
- https://stackoverflow.com/questions/44434604/how-does-utorrent-choose-between-tcp-and-utp
- https://news.ycombinator.com/item?id=8317441
- https://feross.org/libtorrent-webtorrent/

## License

[MIT](https://choosealicense.com/licenses/mit/)

