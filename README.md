<h1 align="center">
 <a href="https://webrtc.rs"><img src="./doc/webrtc.rs.png" alt="WebRTC.rs"></a>
 <br>
</h1>
<p align="center">
 <a href="https://github.com/webrtc-rs/webrtc/actions"> 
  <img src="https://github.com/webrtc-rs/webrtc/workflows/webrtc/badge.svg?branch=master">
 </a> 
 <a href="https://codecov.io/gh/webrtc-rs/webrtc"> 
  <img src="https://codecov.io/gh/webrtc-rs/webrtc/branch/master/graph/badge.svg">
 </a>
 <a href="https://deps.rs/repo/github/webrtc-rs/webrtc"> 
  <img src="https://deps.rs/repo/github/webrtc-rs/webrtc/status.svg">
 </a>
 <a href="https://crates.io/crates/webrtc-rs"> 
  <img src="https://img.shields.io/crates/v/webrtc-rs.svg">
 </a> 
 <a href="https://docs.rs/webrtc-rs"> 
  <img src="https://docs.rs/webrtc-rs/badge.svg">
 </a>
 <a href="https://github.com/webrtc-rs/webrtc/blob/master/LICENSE">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
 </a>
 <a href="https://discord.gg/4Ju8UHdXMs">
  <img src="https://img.shields.io/discord/800204819540869120?logo=discord" alt="Discord">
 </a>
 <a href="https://twitter.com/WebRTCrs">
  <img src="https://img.shields.io/twitter/url/https/twitter.com/webrtcrs.svg?style=social&label=%40WebRTCrs" alt="Twitter">
 </a>  
</p>
<p align="center">
 A pure Rust implementation of WebRTC stack. Rewrite Pion WebRTC stack (<a href="http://Pion.ly">http://Pion.ly</a>) in Rust
</p>

<p align="center">
<strong>Sponsored with 💖 by</strong><br />
<a href="https://getstream.io/?utm_source=github.com/webrtc-rs/webrtc&utm_medium=github&utm_campaign=oss_sponsorship" target="_blank">
<img src="https://stream-blog-v2.imgix.net/blog/wp-content/uploads/f7401112f41742c4e173c30d4f318cb8/stream_logo_white.png?w=350" alt="Stream Chat" style="margin: 8px" />
</a>
<br />
Enterprise Grade APIs for <a href="https://getstream.io/activity-feeds/?utm_source=github.com/webrtc-rs/webrtc&utm_medium=github&utm_campaign=oss_sponsorship" target="_blank">Feeds</a> & <a href="https://getstream.io/chat/?utm_source=github.com/webrtc-rs/webrtc&utm_medium=github&utm_campaign=oss_sponsorship" target="_blank">Chat</a>. <a href="https://getstream.io/chat/get_started/?utm_source=github.com/webrtc-rs/webrtc&utm_medium=github&utm_campaign=oss_sponsorship" target="_blank">Try the interactive Chat tutorial</a> 💬
</p>

# Roadmap

<img src="./doc/webrtc_stack.png" alt="WebRTC.rs">

### Work in Progress Towards 1.0

[sdp-badge]: https://img.shields.io/crates/v/webrtc-rs-sdp.svg
[sdp-url]: https://crates.io/crates/webrtc-rs-sdp
[rtp-badge]: https://img.shields.io/crates/v/webrtc-rs-rtp.svg
[rtp-url]: https://crates.io/crates/webrtc-rs-rtp
[rtcp-badge]: https://img.shields.io/crates/v/webrtc-rs-rtcp.svg
[rtcp-url]: https://crates.io/crates/webrtc-rs-rtcp
[srtp-badge]: https://img.shields.io/crates/v/webrtc-rs-srtp.svg
[srtp-url]: https://crates.io/crates/webrtc-rs-srtp
[dtls-badge]: https://img.shields.io/crates/v/webrtc-rs-dtls.svg
[dtls-url]: https://crates.io/crates/webrtc-rs-dtls
[stun-badge]: https://img.shields.io/crates/v/webrtc-rs-stun.svg
[stun-url]: https://crates.io/crates/webrtc-rs-stun
[mdns-badge]: https://img.shields.io/crates/v/webrtc-rs-mdns.svg
[mdns-url]: https://crates.io/crates/webrtc-rs-mdns
[ice-badge]: https://img.shields.io/crates/v/webrtc-rs-ice.svg
[ice-url]: https://crates.io/crates/webrtc-rs-ice
[turn-badge]: https://img.shields.io/crates/v/webrtc-rs-turn.svg
[turn-url]: https://crates.io/crates/webrtc-rs-turn
[sctp-badge]: https://img.shields.io/crates/v/webrtc-rs-sctp.svg
[sctp-url]: https://crates.io/crates/webrtc-rs-sctp
[media-badge]: https://img.shields.io/crates/v/webrtc-rs-media.svg
[media-url]: https://crates.io/crates/webrtc-rs-media
[webrtc-badge]: https://img.shields.io/crates/v/webrtc-rs.svg
[webrtc-url]: https://crates.io/crates/webrtc-rs


- [x] SDP: [webrtc-rs/sdp](https://github.com/webrtc-rs/sdp) [![sdp][sdp-badge]][sdp-url]
  - sync up to [pion/sdp/v2.4.0](https://github.com/pion/sdp/tree/b29f0bbd42fc719eabdb027117217b0ddb27abf1)
- [x] RTP: [webrtc-rs/rtp](https://github.com/webrtc-rs/rtp) [![rtp][rtp-badge]][rtp-url]
  - sync up to [pion/rtp/v1.6.1](https://github.com/pion/rtp/tree/0d8026ebf7c048a65f30b053f3ce22e7d5e738ee)
- [x] RTCP: [webrtc-rs/rtcp](https://github.com/webrtc-rs/rtcp) [![rtcp][rtcp-badge]][rtcp-url]
  - sync up to [pion/rtcp/v1.2.4](https://github.com/pion/rtcp/tree/d136b4927f135b17cb15c9b287e22a9e053bd498)
- [x] SRTP: [webrtc-rs/srtp](https://github.com/webrtc-rs/srtp) [![srtp][srtp-badge]][srtp-url]
  - sync up to [pion/srtp/v1.5.2](https://github.com/pion/srtp/tree/071a6b95ab38e9eab9324dacd608dde1ec0c7cd3)
- [x] DTLS: [webrtc-rs/dtls](https://github.com/webrtc-rs/dtls) [![dtls][dtls-badge]][dtls-url]
  - sync up to [pion/dtls/v2.0.0](https://github.com/pion/dtls/tree/789798433596e4dd92451b66984dddb2f8a9f165)
- [x] STUN: [webrtc-rs/stun](https://github.com/webrtc-rs/stun) [![stun][stun-badge]][stun-url]
  - sync up to [pion/stun/v0.3.5](https://github.com/pion/stun/tree/7b20b792b7e18b3846032aaa80e8c0e2d412d0f8)
- [x] mDNS: [webrtc-rs/mdns](https://github.com/webrtc-rs/mdns) [![mdns][mdns-badge]][mdns-url]
  - sync up to [pion/mdns/v0.0.4](https://github.com/pion/mdns/tree/2e1665e5f21a89afc152bb4b3791b30eda9b28cf)
- [x] TURN: [webrtc-rs/turn](https://github.com/webrtc-rs/turn) [![turn][turn-badge]][turn-url]
  - sync up to [pion/turn/v2.0.2](https://github.com/pion/turn/tree/502d01577bf86a442ab9b9fa23f78987e7f1e1cd)
- [ ] ICE: [webrtc-rs/ice](https://github.com/webrtc-rs/ice) [![ice][ice-badge]][ice-url]
  - work in progress
  - catch up [pion/ice/v2.0.14](https://github.com/pion/ice/tree/c0a874421c45ef6bbc51166b9056aa46c201f075)
- [ ] PeerConnection [webrtc-rs/webrtc](https://github.com/webrtc-rs/webrtc) [![webrtc][webrtc-badge]][webrtc-url]

### Road Map Towards 2.0

- [ ] SCTP: [webrtc-rs/sctp](https://github.com/webrtc-rs/sctp) [![sctp][sctp-badge]][sctp-url]
- [ ] DataChannel [webrtc-rs/webrtc](https://github.com/webrtc-rs/webrtc) [![webrtc][webrtc-badge]][webrtc-url]
- [ ] Media: [webrtc-rs/media](https://github.com/webrtc-rs/media) [![media][media-badge]][media-url]

### Road Map Towards 3.0

- [ ] SIP
- [ ] QUIC
- [ ] ...

#

### Contributors or pull requests are welcome!
