pandorabox
==========

mediaserver with surface mapping
Client/Server Modell

@Client
- Client developed in WPF
- Timeline Actions
- Assetmanager
- Livesignal Controller
- Projector Mapping, Quad Warping, Rectification, Softedge
- Supported protocols: DMX, MIDI, OSC, HTTP, JSON


@Server
- OpenCL, OpenGL Renderer
- Realtime Compositing Effect Engine
- Tracking Tools: Contourtracking, Blobdetection and many more ...

Todo
====

- OSC Interface as Remote Control
- Seamless multi-projector display.
- Dynamic shadow elimination with a multi-projector setup.
- Surface mapping.
- Standalone WPF client for editing and composing projects. The client streams the resulting video to the local or others remote devices with sufficient GPU rendering capabilities and a connected projector.