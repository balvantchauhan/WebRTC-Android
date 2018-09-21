# AndroidRTC

## WebRTC Live Streaming

An Android client for [WebRTC-Android](https://github.com/balwant108/WebRTC-Android).

It is designed to demonstrate WebRTC video calls between androids and/or desktop browsers, but WebRtcClient could be used in other scenarios. 

- WebRTC-Android
- [iOS client](https://github.com/balwant108/WebRTC-iOS)
- [server](https://github.com/balwant108/WebRTC-Server)


Build with Android Studio 1.1.0. The Intellij IDEA version is in the master branch.
You can import the webrtc-client module in your own app if you want to work with it.


## How To

You need [WebRTC-Server](https://github.com/balwant108/WebRTC-Server) up and running, and it must be somewhere that your android can access. (You can quickly test this with your android browser). Modify the host string (in res/values/strings.xml) to the server IP.

When you launch the app, you will be given several options to send a message : "Call someone".
Use this menu to send a link of your stream. This link can be opened with a WebRTC-capable browser or by another WebRTC-Android.
The video call should then start.


## Libraries

### [libjingle peerconnection](https://code.google.com/p/webrtc/)
### [socket.io-client](https://github.com/nkzawa/socket.io-client.java)

