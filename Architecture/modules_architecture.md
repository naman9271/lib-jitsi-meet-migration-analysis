# Repository Architecture - lib-jitsi-meet

📂 ./modules - 37.0% migrated

├── 📂 browser - 0.0% migrated
│   ├── 📜 BrowserCapabilities.js ❌ (Unmigrated)
│   └── 📜 index.js ❌ (Unmigrated)
├── 📂 connectivity - 60.0% migrated
│   ├── 📜 ConnectionQuality.js ❌ (Unmigrated)
│   ├── 📜 IceFailedHandling.spec.js ❌ (Unmigrated)
│   ├── 📜 IceFailedHandling.ts ✅ (Migrated)
│   ├── 📜 NetworkInfo.ts ✅ (Migrated)
│   └── 📜 TrackStreamingStatus.ts ✅ (Migrated)
├── 📂 detection - 50.0% migrated
│   ├── 📜 ActiveDeviceDetector.js ❌ (Unmigrated)
│   ├── 📜 DetectionEvents.spec.ts ✅ (Migrated)
│   ├── 📜 DetectionEvents.ts ✅ (Migrated)
│   ├── 📜 NoAudioSignalDetection.js ❌ (Unmigrated)
│   ├── 📜 P2PDominantSpeakerDetection.ts ✅ (Migrated)
│   ├── 📜 TrackVADEmitter.js ❌ (Unmigrated)
│   ├── 📜 VADAudioAnalyser.js ❌ (Unmigrated)
│   ├── 📜 VADNoiseDetection.js ❌ (Unmigrated)
│   ├── 📜 VADReportingService.ts ✅ (Migrated)
│   └── 📜 VADTalkMutedDetection.ts ✅ (Migrated)
├── 📂 e2ee - 23.1% migrated
│   ├── 📜 Context.js ❌ (Unmigrated)
│   ├── 📜 Context.spec.js ❌ (Unmigrated)
│   ├── 📜 crypto-utils.js ❌ (Unmigrated)
│   ├── 📜 E2EEContext.js ❌ (Unmigrated)
│   ├── 📜 E2EEErrors.ts ✅ (Migrated)
│   ├── 📜 E2EEncryption.js ❌ (Unmigrated)
│   ├── 📜 ExternallyManagedKeyHandler.js ❌ (Unmigrated)
│   ├── 📜 KeyHandler.js ❌ (Unmigrated)
│   ├── 📜 ManagedKeyHandler.js ❌ (Unmigrated)
│   ├── 📜 OlmAdapter.js ❌ (Unmigrated)
│   ├── 📜 SAS.ts ✅ (Migrated)
│   ├── 📜 utils.ts ✅ (Migrated)
│   └── 📜 Worker.js ❌ (Unmigrated)
├── 📂 e2eping - 100.0% migrated
│   └── 📜 e2eping.ts ✅ (Migrated)
├── 📂 event - 100.0% migrated
│   └── 📜 Jvb121EventGenerator.ts ✅ (Migrated)
├── 📂 flags - 100.0% migrated
│   └── 📜 FeatureFlags.ts ✅ (Migrated)
├── 📂 litemode - 100.0% migrated
│   └── 📜 LiteModeContext.ts ✅ (Migrated)
├── 📂 proxyconnection - 40.0% migrated
│   ├── 📜 constants.spec.ts ✅ (Migrated)
│   ├── 📜 constants.ts ✅ (Migrated)
│   ├── 📜 CustomSignalingLayer.js ❌ (Unmigrated)
│   ├── 📜 ProxyConnectionPC.js ❌ (Unmigrated)
│   └── 📜 ProxyConnectionService.js ❌ (Unmigrated)
├── 📂 qualitycontrol - 25.0% migrated
│   ├── 📜 CodecSelection.js ❌ (Unmigrated)
│   ├── 📜 CodecSelection.spec.js ❌ (Unmigrated)
│   ├── 📜 MockClasses.ts ✅ (Migrated)
│   ├── 📜 QualityController.spec.js ❌ (Unmigrated)
│   ├── 📜 QualityController.ts ✅ (Migrated)
│   ├── 📜 ReceiveVideoController.js ❌ (Unmigrated)
│   ├── 📜 ReceiveVideoController.spec.js ❌ (Unmigrated)
│   └── 📜 SendVideoController.js ❌ (Unmigrated)
├── 📂 recording - 50.0% migrated
│   ├── 📜 JibriSession.js ❌ (Unmigrated)
│   ├── 📜 recordingConstants.ts ✅ (Migrated)
│   ├── 📜 RecordingManager.ts ✅ (Migrated)
│   └── 📜 recordingXMLUtils.js ❌ (Unmigrated)
├── 📂 red - 50.0% migrated
│   ├── 📜 red.spec.js ❌ (Unmigrated)
│   └── 📜 red.ts ✅ (Migrated)
├── 📂 RTC - 18.2% migrated
│   ├── 📜 BridgeChannel.ts ✅ (Migrated)
│   ├── 📜 JitsiLocalTrack.js ❌ (Unmigrated)
│   ├── 📜 JitsiRemoteTrack.js ❌ (Unmigrated)
│   ├── 📜 JitsiTrack.js ❌ (Unmigrated)
│   ├── 📜 MockClasses.ts ✅ (Migrated)
│   ├── 📜 RTC.js ❌ (Unmigrated)
│   ├── 📜 RTCUtils.js ❌ (Unmigrated)
│   ├── 📜 ScreenObtainer.js ❌ (Unmigrated)
│   ├── 📜 TPCUtils.js ❌ (Unmigrated)
│   ├── 📜 TPCUtils.spec.js ❌ (Unmigrated)
│   └── 📜 TraceablePeerConnection.js ❌ (Unmigrated)
├── 📂 RTCStats - 100.0% migrated
│   ├── 📜 DefaulLogStorage.ts ✅ (Migrated)
│   ├── 📜 interfaces.ts ✅ (Migrated)
│   ├── 📜 RTCStats.ts ✅ (Migrated)
│   └── 📜 RTCStatsEvents.ts ✅ (Migrated)
├── 📂 sdp - 7.1% migrated
│   ├── 📜 LocalSdpMunger.js ❌ (Unmigrated)
│   ├── 📜 LocalSdpMunger.spec.js ❌ (Unmigrated)
│   ├── 📜 RtxModifier.js ❌ (Unmigrated)
│   ├── 📜 RtxModifier.spec.js ❌ (Unmigrated)
│   ├── 📜 SampleSdpStrings.js ❌ (Unmigrated)
│   ├── 📜 SDP.js ❌ (Unmigrated)
│   ├── 📜 SDP.spec.js ❌ (Unmigrated)
│   ├── 📜 SDPDiffer.js ❌ (Unmigrated)
│   ├── 📜 SDPDiffer.spec.js ❌ (Unmigrated)
│   ├── 📜 SDPSimulcast.spec.js ❌ (Unmigrated)
│   ├── 📜 SdpSimulcast.ts ✅ (Migrated)
│   ├── 📜 SdpTransformUtil.js ❌ (Unmigrated)
│   ├── 📜 SDPUtil.js ❌ (Unmigrated)
│   └── 📜 SDPUtil.spec.js ❌ (Unmigrated)
├── 📂 settings - 100.0% migrated
│   └── 📜 Settings.ts ✅ (Migrated)
├── 📂 statistics - 15.4% migrated
│   ├── 📜 AnalyticsAdapter.js ❌ (Unmigrated)
│   ├── 📜 AvgRTPStatsReporter.js ❌ (Unmigrated)
│   ├── 📜 constants.js ❌ (Unmigrated)
│   ├── 📜 LocalStatsCollector.js ❌ (Unmigrated)
│   ├── 📜 PerformanceObserverStats.js ❌ (Unmigrated)
│   ├── 📜 PerformanceObserverStats.spec.js ❌ (Unmigrated)
│   ├── 📜 PreCallTest.ts ✅ (Migrated)
│   ├── 📜 RTPStatsCollector.js ❌ (Unmigrated)
│   ├── 📜 SpeakerStats.spec.js ❌ (Unmigrated)
│   ├── 📜 SpeakerStats.ts ✅ (Migrated)
│   ├── 📜 SpeakerStatsCollector.js ❌ (Unmigrated)
│   ├── 📜 SpeakerStatsCollector.spec.js ❌ (Unmigrated)
│   └── 📜 statistics.js ❌ (Unmigrated)
├── 📂 util - 76.9% migrated
│   ├── 📜 AsyncQueue.ts ✅ (Migrated)
│   ├── 📜 Deferred.js ❌ (Unmigrated)
│   ├── 📜 EventEmitter.ts ✅ (Migrated)
│   ├── 📜 EventEmitterForwarder.ts ✅ (Migrated)
│   ├── 📜 Listenable.ts ✅ (Migrated)
│   ├── 📜 MathUtil.spec.js ❌ (Unmigrated)
│   ├── 📜 MathUtil.ts ✅ (Migrated)
│   ├── 📜 RandomUtil.js ❌ (Unmigrated)
│   ├── 📜 Retry.ts ✅ (Migrated)
│   ├── 📜 ScriptUtil.ts ✅ (Migrated)
│   ├── 📜 StringUtils.ts ✅ (Migrated)
│   ├── 📜 TestUtils.ts ✅ (Migrated)
│   └── 📜 UsernameGenerator.ts ✅ (Migrated)
├── 📂 version - 100.0% migrated
│   └── 📜 ComponentsVersions.ts ✅ (Migrated)
├── 📂 videosipgw - 50.0% migrated
│   ├── 📜 JitsiVideoSIPGWSession.js ❌ (Unmigrated)
│   ├── 📜 VideoSIPGW.js ❌ (Unmigrated)
│   ├── 📜 VideoSIPGWConstants.spec.ts ✅ (Migrated)
│   └── 📜 VideoSIPGWConstants.ts ✅ (Migrated)
├── 📂 watchRTC - 100.0% migrated
│   ├── 📜 functions.ts ✅ (Migrated)
│   ├── 📜 interfaces.ts ✅ (Migrated)
│   └── 📜 WatchRTC.ts ✅ (Migrated)
├── 📂 webaudio - 0.0% migrated
│   ├── 📜 AudioMixer.js ❌ (Unmigrated)
│   └── 📜 WebAudioUtils.js ❌ (Unmigrated)
└── 📂 xmpp - 25.7% migrated
    ├── 📜 AVModeration.ts ✅ (Migrated)
    ├── 📜 BreakoutRooms.js ❌ (Unmigrated)
    ├── 📜 Caps.js ❌ (Unmigrated)
    ├── 📜 ChatRoom.js ❌ (Unmigrated)
    ├── 📜 ChatRoom.spec.js ❌ (Unmigrated)
    ├── 📜 ConnectionPlugin.ts ✅ (Migrated)
    ├── 📜 JingleHelperFunctions.ts ✅ (Migrated)
    ├── 📜 JingleSession.js ❌ (Unmigrated)
    ├── 📜 JingleSessionPC.js ❌ (Unmigrated)
    ├── 📜 JingleSessionPC.spec.js ❌ (Unmigrated)
    ├── 📜 JingleSessionState.spec.ts ✅ (Migrated)
    ├── 📜 JingleSessionState.ts ✅ (Migrated)
    ├── 📜 Lobby.js ❌ (Unmigrated)
    ├── 📜 MediaSessionEvents.spec.ts ✅ (Migrated)
    ├── 📜 MediaSessionEvents.ts ✅ (Migrated)
    ├── 📜 MockClasses.js ❌ (Unmigrated)
    ├── 📜 moderator.js ❌ (Unmigrated)
    ├── 📜 ResumeTask.spec.js ❌ (Unmigrated)
    ├── 📜 ResumeTask.ts ✅ (Migrated)
    ├── 📜 RoomMetadata.ts ✅ (Migrated)
    ├── 📜 sha1.js ❌ (Unmigrated)
    ├── 📜 SignalingLayerImpl.js ❌ (Unmigrated)
    ├── 📜 SignalingLayerImpl.spec.js ❌ (Unmigrated)
    ├── 📜 strophe.disco.js ❌ (Unmigrated)
    ├── 📜 strophe.emuc.js ❌ (Unmigrated)
    ├── 📜 strophe.jingle.js ❌ (Unmigrated)
    ├── 📜 strophe.logger.js ❌ (Unmigrated)
    ├── 📜 strophe.ping.js ❌ (Unmigrated)
    ├── 📜 strophe.rayo.js ❌ (Unmigrated)
    ├── 📜 strophe.stream-management.js ❌ (Unmigrated)
    ├── 📜 strophe.util.js ❌ (Unmigrated)
    ├── 📜 StropheLastSuccess.js ❌ (Unmigrated)
    ├── 📜 xmpp.js ❌ (Unmigrated)
    ├── 📜 XmppConnection.js ❌ (Unmigrated)
    └── 📜 XmppConnection.spec.js ❌ (Unmigrated)
