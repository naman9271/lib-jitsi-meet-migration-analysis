# Repository Architecture - lib-jitsi-meet

📂 ./types - 97.9% migrated

├── 📂 hand-crafted - 100.0% migrated
│   ├── 📜 authenticateAndUpgradeRole.d.ts ✅ (Migrated)
│   ├── 📜 EventEmitter.d.ts ✅ (Migrated)
│   ├── 📜 JitsiConference.d.ts ✅ (Migrated)
│   ├── 📜 JitsiConferenceErrors.d.ts ✅ (Migrated)
│   ├── 📜 JitsiConferenceEvents.d.ts ✅ (Migrated)
│   ├── 📜 JitsiConnection.d.ts ✅ (Migrated)
│   ├── 📜 JitsiConnectionErrors.d.ts ✅ (Migrated)
│   ├── 📜 JitsiConnectionEvents.d.ts ✅ (Migrated)
│   ├── 📜 JitsiLogLevels.d.ts ✅ (Migrated)
│   ├── 📜 JitsiMediaDevices.d.ts ✅ (Migrated)
│   ├── 📜 JitsiMediaDevicesEvents.d.ts ✅ (Migrated)
│   ├── 📜 JitsiMeetJS.d.ts ✅ (Migrated)
│   ├── 📜 JitsiParticipant.d.ts ✅ (Migrated)
│   ├── 📜 JitsiTrackError.d.ts ✅ (Migrated)
│   ├── 📜 JitsiTrackErrors.d.ts ✅ (Migrated)
│   ├── 📜 JitsiTrackEvents.d.ts ✅ (Migrated)
│   ├── 📜 JitsiTranscriptionStatus.d.ts ✅ (Migrated)
│   ├── 📂 modules - 100.0% migrated
│   │   ├── 📂 browser - 100.0% migrated
│   │   │   └── 📜 BrowserCapabilities.d.ts ✅ (Migrated)
│   │   ├── 📂 connectivity - 100.0% migrated
│   │   │   ├── 📜 ConnectionQuality.d.ts ✅ (Migrated)
│   │   │   ├── 📜 IceFailedHandling.d.ts ✅ (Migrated)
│   │   │   ├── 📜 NetworkInfo.d.ts ✅ (Migrated)
│   │   │   └── 📜 ParticipantConnectionStatus.d.ts ✅ (Migrated)
│   │   ├── 📂 detection - 100.0% migrated
│   │   │   ├── 📜 ActiveDeviceDetector.d.ts ✅ (Migrated)
│   │   │   ├── 📜 DetectionEvents.d.ts ✅ (Migrated)
│   │   │   ├── 📜 NoAudioSignalDetection.d.ts ✅ (Migrated)
│   │   │   ├── 📜 P2PDominantSpeakerDetection.d.ts ✅ (Migrated)
│   │   │   ├── 📜 TrackVADEmitter.d.ts ✅ (Migrated)
│   │   │   ├── 📜 VADAudioAnalyser.d.ts ✅ (Migrated)
│   │   │   ├── 📜 VADNoiseDetection.d.ts ✅ (Migrated)
│   │   │   ├── 📜 VADReportingService.d.ts ✅ (Migrated)
│   │   │   └── 📜 VADTalkMutedDetection.d.ts ✅ (Migrated)
│   │   ├── 📂 e2ee - 100.0% migrated
│   │   │   ├── 📜 Context.d.ts ✅ (Migrated)
│   │   │   ├── 📜 crypto-utils.d.ts ✅ (Migrated)
│   │   │   ├── 📜 E2EEContext.d.ts ✅ (Migrated)
│   │   │   ├── 📜 E2EEncryption.d.ts ✅ (Migrated)
│   │   │   ├── 📜 OlmAdapter.d.ts ✅ (Migrated)
│   │   │   ├── 📜 utils.d.ts ✅ (Migrated)
│   │   │   └── 📜 Worker.d.ts ✅ (Migrated)
│   │   ├── 📂 e2eping - 100.0% migrated
│   │   │   └── 📜 e2eping.d.ts ✅ (Migrated)
│   │   ├── 📂 event - 100.0% migrated
│   │   │   └── 📜 Jvb121EventGenerator.d.ts ✅ (Migrated)
│   │   ├── 📂 proxyconnection - 100.0% migrated
│   │   │   ├── 📜 constants.d.ts ✅ (Migrated)
│   │   │   ├── 📜 ProxyConnectionPC.d.ts ✅ (Migrated)
│   │   │   └── 📜 ProxyConnectionService.d.ts ✅ (Migrated)
│   │   ├── 📂 qualitycontrol - 100.0% migrated
│   │   │   ├── 📜 ReceiveVideoController.d.ts ✅ (Migrated)
│   │   │   └── 📜 SendVideoController.d.ts ✅ (Migrated)
│   │   ├── 📂 recording - 100.0% migrated
│   │   │   ├── 📜 JibriSession.d.ts ✅ (Migrated)
│   │   │   ├── 📜 recordingConstants.d.ts ✅ (Migrated)
│   │   │   ├── 📜 RecordingManager.d.ts ✅ (Migrated)
│   │   │   └── 📜 recordingXMLUtils.d.ts ✅ (Migrated)
│   │   ├── 📂 red - 100.0% migrated
│   │   │   └── 📜 red.d.ts ✅ (Migrated)
│   │   ├── 📂 RTC - 100.0% migrated
│   │   │   ├── 📜 BridgeChannel.d.ts ✅ (Migrated)
│   │   │   ├── 📜 CodecSelection.d.ts ✅ (Migrated)
│   │   │   ├── 📜 JitsiLocalTrack.d.ts ✅ (Migrated)
│   │   │   ├── 📜 JitsiRemoteTrack.d.ts ✅ (Migrated)
│   │   │   ├── 📜 JitsiTrack.d.ts ✅ (Migrated)
│   │   │   ├── 📜 RTC.d.ts ✅ (Migrated)
│   │   │   ├── 📜 RTCUtils.d.ts ✅ (Migrated)
│   │   │   ├── 📜 ScreenObtainer.d.ts ✅ (Migrated)
│   │   │   ├── 📜 TPCUtils.d.ts ✅ (Migrated)
│   │   │   └── 📜 TraceablePeerConnection.d.ts ✅ (Migrated)
│   │   ├── 📂 sdp - 100.0% migrated
│   │   │   ├── 📜 LocalSdpMunger.d.ts ✅ (Migrated)
│   │   │   ├── 📜 RtxModifier.d.ts ✅ (Migrated)
│   │   │   ├── 📜 SDP.d.ts ✅ (Migrated)
│   │   │   ├── 📜 SDPDiffer.d.ts ✅ (Migrated)
│   │   │   ├── 📜 SdpTransformUtil.d.ts ✅ (Migrated)
│   │   │   └── 📜 SDPUtil.d.ts ✅ (Migrated)
│   │   ├── 📂 settings - 100.0% migrated
│   │   │   └── 📜 Settings.d.ts ✅ (Migrated)
│   │   ├── 📂 statistics - 100.0% migrated
│   │   │   ├── 📜 AnalyticsAdapter.d.ts ✅ (Migrated)
│   │   │   ├── 📜 AvgRTPStatsReporter.d.ts ✅ (Migrated)
│   │   │   ├── 📜 constants.d.ts ✅ (Migrated)
│   │   │   ├── 📜 LocalStatsCollector.d.ts ✅ (Migrated)
│   │   │   ├── 📜 PerformanceObserverStats.d.ts ✅ (Migrated)
│   │   │   ├── 📜 PrecallTest.d.ts ✅ (Migrated)
│   │   │   ├── 📜 RTPStatsCollector.d.ts ✅ (Migrated)
│   │   │   ├── 📜 SpeakerStats.d.ts ✅ (Migrated)
│   │   │   ├── 📜 SpeakerStatsCollector.d.ts ✅ (Migrated)
│   │   │   └── 📜 statistics.d.ts ✅ (Migrated)
│   │   ├── 📂 transcription - 100.0% migrated
│   │   │   ├── 📜 audioRecorder.d.ts ✅ (Migrated)
│   │   │   ├── 📜 recordingResult.d.ts ✅ (Migrated)
│   │   │   ├── 📜 transcriber.d.ts ✅ (Migrated)
│   │   │   ├── 📜 transcriberHolder.d.ts ✅ (Migrated)
│   │   │   ├── 📂 transcriptionServices - 100.0% migrated
│   │   │   │   ├── 📜 AbstractTranscriptionService.d.ts ✅ (Migrated)
│   │   │   │   └── 📜 SphinxTranscriptionService.d.ts ✅ (Migrated)
│   │   │   └── 📜 word.d.ts ✅ (Migrated)
│   │   ├── 📂 util - 100.0% migrated
│   │   │   ├── 📜 AsyncQueue.d.ts ✅ (Migrated)
│   │   │   ├── 📜 AuthUtil.d.ts ✅ (Migrated)
│   │   │   ├── 📜 Deferred.d.ts ✅ (Migrated)
│   │   │   ├── 📜 EventEmitterForwarder.d.ts ✅ (Migrated)
│   │   │   ├── 📜 GlobalOnErrorHandlerImpl.d.ts ✅ (Migrated)
│   │   │   ├── 📜 Listenable.d.ts ✅ (Migrated)
│   │   │   ├── 📜 MathUtil.d.ts ✅ (Migrated)
│   │   │   ├── 📜 RandomUtil.d.ts ✅ (Migrated)
│   │   │   ├── 📜 Retry.d.ts ✅ (Migrated)
│   │   │   ├── 📜 ScriptUtil.d.ts ✅ (Migrated)
│   │   │   ├── 📜 StringUtils.d.ts ✅ (Migrated)
│   │   │   ├── 📜 TestUtils.d.ts ✅ (Migrated)
│   │   │   └── 📜 UsernameGenerator.d.ts ✅ (Migrated)
│   │   ├── 📂 version - 100.0% migrated
│   │   │   └── 📜 ComponentsVersions.d.ts ✅ (Migrated)
│   │   ├── 📂 videosipgw - 100.0% migrated
│   │   │   ├── 📜 JitsiVideoSIPGWSession.d.ts ✅ (Migrated)
│   │   │   ├── 📜 VideoSIPGW.d.ts ✅ (Migrated)
│   │   │   └── 📜 VideoSIPGWConstants.d.ts ✅ (Migrated)
│   │   ├── 📂 webaudio - 100.0% migrated
│   │   │   ├── 📜 AudioMixer.d.ts ✅ (Migrated)
│   │   │   └── 📜 WebAudioUtils.d.ts ✅ (Migrated)
│   │   └── 📂 xmpp - 100.0% migrated
│   │       ├── 📜 AVModeration.d.ts ✅ (Migrated)
│   │       ├── 📜 Caps.d.ts ✅ (Migrated)
│   │       ├── 📜 ChatRoom.d.ts ✅ (Migrated)
│   │       ├── 📜 ConnectionPlugin.d.ts ✅ (Migrated)
│   │       ├── 📜 JingleSession.d.ts ✅ (Migrated)
│   │       ├── 📜 JingleSessionPC.d.ts ✅ (Migrated)
│   │       ├── 📜 JingleSessionState.d.ts ✅ (Migrated)
│   │       ├── 📜 Lobby.d.ts ✅ (Migrated)
│   │       ├── 📜 MediaSessionEvents.d.ts ✅ (Migrated)
│   │       ├── 📜 moderator.d.ts ✅ (Migrated)
│   │       ├── 📜 ResumeTask.d.ts ✅ (Migrated)
│   │       ├── 📜 SignalingLayerImpl.d.ts ✅ (Migrated)
│   │       ├── 📜 strophe.emuc.d.ts ✅ (Migrated)
│   │       ├── 📜 strophe.jingle.d.ts ✅ (Migrated)
│   │       ├── 📜 strophe.logger.d.ts ✅ (Migrated)
│   │       ├── 📜 strophe.ping.d.ts ✅ (Migrated)
│   │       ├── 📜 strophe.rayo.d.ts ✅ (Migrated)
│   │       ├── 📜 strophe.util.d.ts ✅ (Migrated)
│   │       ├── 📜 StropheLastSuccess.d.ts ✅ (Migrated)
│   │       ├── 📜 xmpp.d.ts ✅ (Migrated)
│   │       └── 📜 XmppConnection.d.ts ✅ (Migrated)
│   └── 📂 service - 100.0% migrated
│       ├── 📂 authentication - 100.0% migrated
│       │   └── 📜 AuthenticationEvents.d.ts ✅ (Migrated)
│       ├── 📂 connectivity - 100.0% migrated
│       │   └── 📜 ConnectionQualityEvents.d.ts ✅ (Migrated)
│       ├── 📂 e2eping - 100.0% migrated
│       │   └── 📜 E2ePingEvents.d.ts ✅ (Migrated)
│       ├── 📂 RTC - 100.0% migrated
│       │   ├── 📜 BridgeVideoType.d.ts ✅ (Migrated)
│       │   ├── 📜 CameraFacingMode.d.ts ✅ (Migrated)
│       │   ├── 📜 CodecMimeType.d.ts ✅ (Migrated)
│       │   ├── 📜 MediaDirection.d.ts ✅ (Migrated)
│       │   ├── 📜 MediaType.d.ts ✅ (Migrated)
│       │   ├── 📜 Resolutions.d.ts ✅ (Migrated)
│       │   ├── 📜 RTCEvents.d.ts ✅ (Migrated)
│       │   ├── 📜 SignalingEvents.d.ts ✅ (Migrated)
│       │   ├── 📜 SignalingLayer.d.ts ✅ (Migrated)
│       │   ├── 📜 StreamEventTypes.d.ts ✅ (Migrated)
│       │   └── 📜 VideoType.d.ts ✅ (Migrated)
│       ├── 📂 statistics - 100.0% migrated
│       │   ├── 📜 AnalyticsEvents.d.ts ✅ (Migrated)
│       │   ├── 📜 constants.d.ts ✅ (Migrated)
│       │   └── 📜 Events.d.ts ✅ (Migrated)
│       └── 📂 xmpp - 100.0% migrated
│           └── 📜 XMPPEvents.d.ts ✅ (Migrated)
├── 📜 index.d.ts ✅ (Migrated)
└── 📂 types-comparer - 0.0% migrated
    ├── 📜 index.js ❌ (Unmigrated)
    ├── 📜 package-lock.json 
    └── 📜 package.json 
