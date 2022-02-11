
# PeerShare

PeerShare is a file sharing app that allows users to transfer files between multiple devices. It uses torrent based web technologies and runs in the web browser. It supports instant file sharing with multiple devices at once.

PeerShare uses WebTorrent to transfer files between multiple devices, and WebSockets to create temporary rooms. Files shared via WebTorrent are peer-to-peer(as they use WebRTC internally) which means there is direct transfer between the sender and receiver without any intermediate server.


## Features

- No signup required.
- Supports one to many transfers.
- Works on almost all browsers that support WebRTC protocol.
- Cross platform and responsive.
- Easy to use, no app installation or dependency required.


## Try it live!

- Head over to the website [here.](https://p2p-file-share.herokuapp.com/)
- A random string will get appended to the above URL.
- Share the link of the page to the other peer over the same network.
- A connection will be established once the other peer opens the link.
- Start sharing files!


## Tech Stack

**Server:** Node, Express, SocketIO, WebTorrent

**Client:** HTML, CSS, JS, ejs


## License

[MIT](https://choosealicense.com/licenses/mit/)

