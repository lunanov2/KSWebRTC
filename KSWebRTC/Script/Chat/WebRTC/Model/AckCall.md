{
action = call;
"call_start" = 0;
callback = 1;
"client_type" = iOS;
from = 17;
member = 0;
"member_count" = 0;
message = "";
offer = "{\n  \"jsep\" : {\n    \"type\" : \"offer\",\n    \"sdp\" : \"v=0\\r\\no=- 8589008553440301670 2 IN IP4 127.0.0.1\\r\\ns=-\\r\\nt=0 0\\r\\na=group:BUNDLE audio video\\r\\na=msid-semantic: WMS ARDAMS\\r\\nm=audio 9 UDP\\/TLS\\/RTP\\/SAVPF 111 103 104 9 102 0 8 106 105 13 110 112 113 126\\r\\nc=IN IP4 0.0.0.0\\r\\na=rtcp:9 IN IP4 0.0.0.0\\r\\na=ice-ufrag:dp0Y\\r\\na=ice-pwd:NZRRej\\/9aE0VMOxSHJ2ghq6P\\r\\na=ice-options:trickle renomination\\r\\na=fingerprint:sha-256 92:DA:19:1D:1B:7A:63:57:30:FD:DB:04:C7:2A:ED:BD:EA:C9:0F:09:88:4C:BD:2A:4C:D9:CF:01:04:88:9A:87\\r\\na=setup:actpass\\r\\na=mid:audio\\r\\na=extmap:1 urn:ietf:params:rtp-hdrext:ssrc-audio-level\\r\\na=extmap:2 http:\\/\\/www.webrtc.org\\/experiments\\/rtp-hdrext\\/abs-send-time\\r\\na=extmap:3 http:\\/\\/www.ietf.org\\/id\\/draft-holmer-rmcat-transport-wide-cc-extensions-01\\r\\na=sendrecv\\r\\na=rtcp-mux\\r\\na=rtpmap:111 opus\\/48000\\/2\\r\\na=rtcp-fb:111 transport-cc\\r\\na=fmtp:111 minptime=10;useinbandfec=1\\r\\na=rtpmap:103 ISAC\\/16000\\r\\na=rtpmap:104 ISAC\\/32000\\r\\na=rtpmap:9 G722\\/8000\\r\\na=rtpmap:102 ILBC\\/8000\\r\\na=rtpmap:0 PCMU\\/8000\\r\\na=rtpmap:8 PCMA\\/8000\\r\\na=rtpmap:106 CN\\/32000\\r\\na=rtpmap:105 CN\\/16000\\r\\na=rtpmap:13 CN\\/8000\\r\\na=rtpmap:110 telephone-event\\/48000\\r\\na=rtpmap:112 telephone-event\\/32000\\r\\na=rtpmap:113 telephone-event\\/16000\\r\\na=rtpmap:126 telephone-event\\/8000\\r\\na=ssrc:831418427 cname:3n6np0Jp7KP93Qzh\\r\\na=ssrc:831418427 msid:ARDAMS ARDAMSa0\\r\\na=ssrc:831418427 mslabel:ARDAMS\\r\\na=ssrc:831418427 label:ARDAMSa0\\r\\nm=video 9 UDP\\/TLS\\/RTP\\/SAVPF 96 97 98 99 100 101 127 124 125\\r\\nc=IN IP4 0.0.0.0\\r\\na=rtcp:9 IN IP4 0.0.0.0\\r\\na=ice-ufrag:dp0Y\\r\\na=ice-pwd:NZRRej\\/9aE0VMOxSHJ2ghq6P\\r\\na=ice-options:trickle renomination\\r\\na=fingerprint:sha-256 92:DA:19:1D:1B:7A:63:57:30:FD:DB:04:C7:2A:ED:BD:EA:C9:0F:09:88:4C:BD:2A:4C:D9:CF:01:04:88:9A:87\\r\\na=setup:actpass\\r\\na=mid:video\\r\\na=extmap:14 urn:ietf:params:rtp-hdrext:toffset\\r\\na=extmap:2 http:\\/\\/www.webrtc.org\\/experiments\\/rtp-hdrext\\/abs-send-time\\r\\na=extmap:13 urn:3gpp:video-orientation\\r\\na=extmap:3 http:\\/\\/www.ietf.org\\/id\\/draft-holmer-rmcat-transport-wide-cc-extensions-01\\r\\na=extmap:5 http:\\/\\/www.webrtc.org\\/experiments\\/rtp-hdrext\\/playout-delay\\r\\na=extmap:6 http:\\/\\/www.webrtc.org\\/experiments\\/rtp-hdrext\\/video-content-type\\r\\na=extmap:7 http:\\/\\/www.webrtc.org\\/experiments\\/rtp-hdrext\\/video-timing\\r\\na=extmap:8 http:\\/\\/tools.ietf.org\\/html\\/draft-ietf-avtext-framemarking-07\\r\\na=extmap:9 http:\\/\\/www.webrtc.org\\/experiments\\/rtp-hdrext\\/color-space\\r\\na=recvonly\\r\\na=rtcp-mux\\r\\na=rtcp-rsize\\r\\na=rtpmap:96 VP8\\/90000\\r\\na=rtcp-fb:96 goog-remb\\r\\na=rtcp-fb:96 transport-cc\\r\\na=rtcp-fb:96 ccm fir\\r\\na=rtcp-fb:96 nack\\r\\na=rtcp-fb:96 nack pli\\r\\na=rtpmap:97 rtx\\/90000\\r\\na=fmtp:97 apt=96\\r\\na=rtpmap:98 H264\\/90000\\r\\na=rtcp-fb:98 goog-remb\\r\\na=rtcp-fb:98 transport-cc\\r\\na=rtcp-fb:98 ccm fir\\r\\na=rtcp-fb:98 nack\\r\\na=rtcp-fb:98 nack pli\\r\\na=fmtp:98 level-asymmetry-allowed=1;packetization-mode=1;profile-level-id=640c1f\\r\\na=rtpmap:99 rtx\\/90000\\r\\na=fmtp:99 apt=98\\r\\na=rtpmap:100 H264\\/90000\\r\\na=rtcp-fb:100 goog-remb\\r\\na=rtcp-fb:100 transport-cc\\r\\na=rtcp-fb:100 ccm fir\\r\\na=rtcp-fb:100 nack\\r\\na=rtcp-fb:100 nack pli\\r\\na=fmtp:100 level-asymmetry-allowed=1;packetization-mode=1;profile-level-id=42e01f\\r\\na=rtpmap:101 rtx\\/90000\\r\\na=fmtp:101 apt=100\\r\\na=rtpmap:127 red\\/90000\\r\\na=rtpmap:124 rtx\\/90000\\r\\na=fmtp:124 apt=127\\r\\na=rtpmap:125 ulpfec\\/90000\\r\\n\"\n  },\n  \"body\" : {\n    \"request\" : \"configure\",\n    \"audio\" : true,\n    \"video\" : true\n  }\n}";
"prev_id" = 0;
revision = 1;
room = "friend_17_18";
"session_id" = "1597719510:783368690";
to = 18;
video = 1;
}