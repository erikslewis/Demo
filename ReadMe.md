In May 2011, Google released an open source project for browser-based real-time communication known as WebRTC.
WebRTC (Web Real-Time Communication) is a collection of communications protocols and application programming interfaces that enable real-time communication over peer-to-peer connections. This allows web browsers to not only request resources from backend servers, but also real-time information from browsers of other users.

This enables applications such as video conferencing, file transfer, chat, or desktop sharing without the need of either internal or external plugins.

WebRTC is being standardized by the World Wide Web Consortium (W3C) and the Internet Engineering Task Force (IETF). The reference implementation is released as free software under the terms of a BSD license. OpenWebRTC provides another free implementation based on the multimedia framework GStreamer.

WebRTC uses Real-Time Protocol to transfer audio and video.

getUserMedia, which allows a web browser to access the camera and microphone and to capture media
RTCPeerConnection, which sets up audio/video calls
RTCDataChannel, which allow browsers to share data via peer-to-peer
The WebRTC API also includes a statistics function:

getStats, which allows the web application to retrieve a set of statistics about WebRTC sessions.
WebRTC is supported in the following browsers.

Desktop PC
Google Chrome
Microsoft Edge 12
Google Chrome 23
Mozilla Firefox 22
Opera 18
Android
Google Chrome 28 (enabled by default since 29)
Mozilla Firefox 24
Opera Mobile 12
Chrome OS
Firefox OS
Blackberry 10
Browser
As of September 2015, Internet Explorer and Safari still lack the native support of WebRTC but ORTC was already added to the new Microsoft browser, Edge. Several plugins are available to add the support of WebRTC to these browsers. As of April 2016, WebKit, the back-end engine for Apple’s Safari has listed support for WebRTC as being in-development.

Conclusion Why You Should Use WebRTC:
Because WebRTC requires no plugins, frameworks or applications, all you need is a WebRTC compatible browser. To an end user, WebRTC applications “just work” right out of the box. No Flash, no Silverlight, no JavaScript API, just pure video, audio, and data communication on any webpage.

WebRTC is entirely peer to peer, so you don’t have to pay for any of the bandwidth across the wire. Additionally, because WebRTC is entirely browser to browser, you get the highest performance and lowest latency possible. For example, say a user is trying to share a file. Without WebRTC, the user has to upload said file to a server, and the recipient user has to download that file. With WebRTC, these files are transferred directly through the WebRTC Data Channel, no servers or infrastructure required.
