# Essential parts
Current phase MVP consists of several software and hardware parts.

1. Computer with a video camera, configured for fast performance with machine learning algorithms, that can run recognition as fast as 60 frames per second.
2. Pose recognition engine
3. Pose to Midi Converter module, that is also responsible for caching, object detection and other computational tasks
4. Midi bridge software, that runs on Audio Designer's Mac. It connects to Pose-to-Midi-Converter with wifi, and exposes midi connections for a final use case.
5. Audio set up - Ableton session, that maps Mirror's midi outputs to specific musical instruments inside the musical session. 