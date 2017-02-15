In May 2011, Google released an open source project for browser-based real-time communication known as WebRTC.
WebRTC (Web Real-Time Communication) is a collection of communications protocols and application programming interfaces that enable real-time communication over peer-to-peer connections. This allows web browsers to not only request resources from backend servers, but also real-time information from browsers of other users.

This enables applications such as video conferencing, file transfer, chat, or desktop sharing without the need of either internal or external plugins.

WebRTC is being standardized by the World Wide Web Consortium (W3C) and the Internet Engineering Task Force (IETF). The reference implementation is released as free software under the terms of a BSD license.

# WebRTC uses Real-Time Protocol to transfer audio and video.

- getUserMedia, which allows a web browser to access the camera and microphone and to capture media
- RTCPeerConnection, which sets up audio/video calls
- RTCDataChannel, which allow browsers to share data via peer-to-peer
- getStats, which allows the web application to retrieve a set of statistics about WebRTC sessions.

# WebRTC is supported in the following browsers.
- Desktop PC
-- Google Chrome
-- Microsoft Edge 12
-- Mozilla Firefox 22
-- Opera 18
- Android
-- Google Chrome 28 (enabled by default since 29)
-- Mozilla Firefox 24
- Opera Mobile 12
- Chrome OS
- Firefox OS
- Blackberry 10 Browser

As of September 2015, Internet Explorer and Safari still lack the native support of WebRTC but ORTC was already added to the new Microsoft browser, Edge. Several plugins are available to add the support of WebRTC to these browsers. As of April 2016, WebKit, the back-end engine for Apple’s Safari has listed support for WebRTC as being in-development.

# Conclusion Why You Should Use WebRTC:
Because WebRTC requires no plugins, frameworks or applications, all you need is a WebRTC compatible browser. To an end user, WebRTC applications “just work” right out of the box. No Flash, no Silverlight, no JavaScript API, just pure video, audio, and data communication on any webpage.

WebRTC is entirely peer to peer, so you don’t have to pay for any of the bandwidth across the wire. Additionally, because WebRTC is entirely browser to browser, you get the highest performance and lowest latency possible. For example, say a user is trying to share a file. Without WebRTC, the user has to upload said file to a server, and the recipient user has to download that file. With WebRTC, these files are transferred directly through the WebRTC Data Channel, no servers or infrastructure required.


# Compare Websockets
- WebRTC is designed for high-performance, high quality communication of video, audio and arbitrary data.
- WebRTC apps need a service via which they can exchange network and media metadata, a process known as signaling. However, once signaling has taken place, video/audio/data is streamed directly between clients, avoiding the performance cost of streaming via an intermediary server.
- WebSocket on the other hand is designed for bi-directional communication between client and server. It is possible to stream audio and video over WebSocket, but the technology and APIs are not inherently designed for efficient, robust streaming in the way that WebRTC is.



# http://io13webrtc.appspot.com/#2
