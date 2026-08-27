<div align="center">

<a href="https://solarys431.github.io/vortex-intercom/"><img src="assets/banner.png" alt="VORTEX Intercom — the control-room matrix, virtualized" width="100%"></a>

<a href="README.md">Italiano</a> · <strong>English</strong>

🌐 <a href="https://solarys431.github.io/vortex-intercom/">Landing page</a>

</div>

---

## What it is

VORTEX Intercom is a software intercom based on the broadcast **crosspoint matrix** model: who talks to whom, at what level and who listens. Its logic runs on LiveKit/WebRTC and does not require a dedicated proprietary intercom matrix. **The control room manages the matrix and assigns positions through signed invitations.**

![VORTEX Intercom matrix](assets/console.png)

---

## Main features

### Up to 16 differentiated N-1 circuits on compatible interfaces

Each participant needs a return feed with their own voice removed. VORTEX can assign each N-1 to a distinct channel on a compatible multichannel CoreAudio interface, such as Dante Virtual Soundcard, for up to sixteen independent circuits.

![N-1 assignment from an audio-interface channel](assets/nminus.png)

### A position is a link

The control room generates a signed invitation for a role through a QR code or link, with a configurable expiration. The recipient opens the intercom on a phone without creating an account. The beltpack view provides push-to-talk, headphone volume and listening control.

<p>
  <img src="assets/invito.png" width="60%" alt="Expiring QR invitation" />
  <img src="assets/beltpack.png" width="26%" alt="Beltpack view on iPhone" />
</p>

### Configured for each production

Labels can be renamed, party-lines and IFB circuits configured, and active speakers monitored. A guided setup connects the LiveKit room and shares the configuration with connected positions.

![Position label editing](assets/rinomina.png)

---

## Platforms

| | |
|---|---|
| **iPhone** — beltpack | Pocket push-to-talk for operators, reporters and presenters. Link access; locked-screen operation is undergoing beta validation. |
| **iPad** — panel | A matrix panel for mobile control rooms and technical positions. |
| **Mac** — central station | The control room manages the matrix and N-1 circuits from the audio interface, invites positions and routes communications. |

---

## Status

**Beta — under TestFlight testing.** This repository contains the product presentation page; the application source code is private.

The site is static and uses no cookies, tracking or data collection. Fonts are hosted locally. Application images use demonstration data.

<div align="center">

© 2026 Daniele Cappello · part of the VORTEX ecosystem

</div>
