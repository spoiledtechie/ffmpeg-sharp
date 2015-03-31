ffmpeg-sharp is a wrapper library over the FFmpeg multimedia suite that provides easy to use wrappers for use in C# products under both Mono and .NET.

At present audio decoding and encoding are mature and video capabilities are in development (we currently have video decoding working but without synced audio yet).

In addition to the audio decoding and encoding capabilities, all of the native interfaces are made available through the Interop namespace allowing extended use of the FFmpeg libraries without having to navigate the platform invokes on your own.

This project initially began as a fork of SharpFFmpeg due to the clumsiness of their platform invokes, but further evolved into a full rewrite of the p-invokes and the audio/video decoding and audio encoding streams now present.  So with this library, you have the choice of either a simplified view or the full interops.