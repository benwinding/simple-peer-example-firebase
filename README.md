## Simple Peer Demo (using Firebase)

This is a demonstration of P2P video calls using the package [simple-peer](https://github.com/feross/simple-peer) and firebase.

- [LIVE DEMO](https://benwinding.github.io/simple-peer-example-firebase/)

### System Architecture

- Web RTC
  - Available in all modern browsers
  - Used via the simple-peer package
  - All video/voice bandwidth is peer to peer
- Firebase Realtime database 
  - Registers and subscribes to active users
  - Sends and recieves the handshake data from simple-peer

