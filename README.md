# WeMeet Client

<div align="center">

**The Real-Time WebRTC Meeting Room Interface for WeMeet**

*Graduation Thesis Project - School of Computer Science and Engineering*

[![TypeScript](https://img.shields.io/badge/TypeScript-90.1%25-blue)](https://www.typescriptlang.org/)
[![Build Tool](https://img.shields.io/badge/Webpack-Bundle-green)](https://webpack.js.org/)

</div>

##  Introduction
**WeMeet Client** is the dedicated frontend single-page application (SPA) handling the real-time meeting room logic, layout orchestration, and WebRTC streaming media channels for the WeMeet platform. 

It communicates directly with `WeMeet-server` via HTTP/WebSocket signaling and interfaces seamlessly with the LiveKit SFU topology to manage high-concurrency audio, video, and screen-sharing interactions.

### Core Tech Stack:
- **Programming Language**: TypeScript (Strict Static Typing)
- **Media Transports**: WebRTC (LiveKit Frontend Client SDK)
- **Style Engine**: TailwindCSS & SCSS (Responsive Layouts)
- **Bundler Compiler**: Webpack
- **Machine Learning Layer**: Custom TensorFlow.js integration for local virtual backgrounds

##  Core Room Features
-  **WebRTC Streaming**: Native high-definition audio/video publishing and subscribing.
-  **Dynamic Screen Share**: Real-time display transmission capabilities.
-  **In-Room Chat Mesh**: Instant messaging functionality driven by asynchronous signaling broker lines.
-  **Interactive Whiteboard**: Collaborative drawing canvas interface.
-  **Virtual Backgrounds**: Local image segmentation processing using custom TFJS configurations.
-  **In-Room Voting**: Interactive polling interface for structural attendee moderation.

##  Installation & Local Development

### Environment Setup
Ensure your local node compiler toolchain is active, then navigate into the client workspace:
```bash
cd WeMeet-client
pnpm install
pnpm start
// to build
pnpm run build