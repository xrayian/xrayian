# Hi, I'm Rayian 👋

I build software that connects to the real world: mobile apps, realtime backends, and the devices they talk to.

Right now I'm a Software Engineer at **ChargeMe** (UIU fellowship), working full-stack on an EV charging platform built on OCPP. Mostly the mobile apps, plus whatever else a startup needs that week. I'm also finishing my B.Sc. in Computer Science and Engineering at United International University in Dhaka (graduating 2027).

I started in grade 3, making games in Scratch and using Cheat Engine to flip IGI's ammo instruction from subtract to add, so every shot gave me a bullet instead of costing one. Wrote my first Python "Hello, World" in 2011. Stuck around for the challenges and the occasional dopamine hit.

[Portfolio](https://xrayian.is-a.dev) · [LinkedIn](https://www.linkedin.com/in/xrayian) · [Email](mailto:rbsmahi@gmail.com) · [Devpost](https://devpost.com/rbsmahi)

---

## Where I've worked

- **ChargeMe** (2026 – now): Software Engineer through a UIU fellowship. Mobile apps and backend for an OCPP-based EV charging platform.
- **Prologic**: Founding full-stack engineer. Built web and mobile products for clients, and designed the company's brand identity.
- **CanSat 2025, Team UIU ASCEND**: one of three on the software team. I developed and integrated the flight software on a Teensy 4.1 (C++, PlatformIO). The team placed 7th worldwide, 2nd in Asia and 1st in Bangladesh. ([reference firmware](https://github.com/xrayian/cansat-flight-firmware-2025))
- **Star Tech Shop**: contributed Flutter frontend work to a retail app with 100K+ downloads on Google Play.
- **Aqua-Sweep**: 4th place at the UIU Microprocessor and Microcontroller Project Show, Summer 2026.

---

## Featured projects

### [Digital Sheriff of Nottingham](https://github.com/xrayian/digital-sheriff-of-nottingham)
An online multiplayer version of the board game for 3 to 6 players. The server owns the game state, so nobody can peek at another player's hand or cheat from the browser. 114 automated tests, runs in Docker.

`TypeScript` `Colyseus` `React` `Docker`

### [CanSat Flight Firmware](https://github.com/xrayian/cansat-flight-firmware-2025)
Reference flight software for a Teensy 4.1, built on the architecture we used at CanSat 2025. Five threads handle the barometer, GPS, radio commands, the flight state machine and telemetry, each on its own schedule. The README documents the threading rules that keep them from corrupting each other. Not the exact code we flew, but the same concept, cleaned up for future teams.

`C++` `Teensy 4.1` `TeensyThreads` `PlatformIO`

### [AlgoArena](https://github.com/xrayian/AlgoArena)
An interactive 2D and 3D pathfinding visualizer. Draw walls, adjust weights, and watch 7 algorithms (A\*, Dijkstra, BFS, DFS and more) find their way. 258 automated tests.

`TypeScript` `React` `Three.js`

### [Acoustic Dome](https://github.com/xrayian/acoustic-dome-iot)
A sensor station on an ESP8266. C++ firmware samples sound and environment readings and streams them over MQTT to a live Node.js dashboard.

`C++` `ESP8266` `MQTT` `Node.js`

### HandyLink, built twice
A marketplace that connects households with nearby handymen. I built it as a web platform for my database course, then again as a mobile app for my mobile development course, which required a Node.js backend.

- [**handylink-web**](https://github.com/xrayian/handylink-web): lead developer. Customer, handyman and admin portals, location-based search, OTP-verified bookings, notifications. `Nuxt 3` `PHP 8` `MySQL`
- [**handylink-mobile-platform**](https://github.com/xrayian/handylink-mobile-platform): co-developed. Selected for the UIU Project Show, February 2026. `React Native` `Express` `TypeScript`

---

## Also worth a look

- [**Collabo**](https://github.com/xrayian/Collabo): realtime drawing and video calls over WebRTC (Mediasoup), in the browser and on desktop via Electron.
- [**Storyframe**](https://github.com/xrayian/story-illustrator-storyframe): turns a written story into illustrated scenes with voice narration, using Gemini, ElevenLabs and background job queues.
- **Nexus**: a market dashboard with technical analysis, news sentiment and an AI copilot. Next.js [frontend](https://github.com/xrayian/nexus-fintech-next) and NestJS [backend](https://github.com/xrayian/nexus-fintech-nest-backend). [Live demo](https://nexus-stock-ai.vercel.app/)
- [**Life Simulator**](https://github.com/xrayian/Life-Simulator): a zero-player life simulation that runs itself. [Live demo](https://life-simulator-xray.vercel.app/)

---

## Tools I reach for

- **Languages:** TypeScript, JavaScript, Dart, Python, C++, Java, PHP
- **Web and backend:** React, Next.js, Vue, Nuxt, Node.js, Express, NestJS, Colyseus, WebRTC
- **Mobile:** React Native, Flutter
- **Data and infrastructure:** PostgreSQL, MySQL, MongoDB, Redis, Docker, Vercel, Azure, Cloudflare R2
- **Embedded and IoT:** Teensy 4.1, ESP8266, ESP32, PlatformIO, MQTT, OCPP

---

Always happy to talk about realtime systems, EV charging, or getting hardware and software to play nicely together.
