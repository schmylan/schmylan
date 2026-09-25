## Hi, I'm Rylan 👋

**Engineer. Designer. Software bushwhacker.**

📍 Dallas–Fort Worth · 🌐 [rylan.io](https://rylan.io) · 💼 [LinkedIn](https://www.linkedin.com/in/rylanbarnes/)

I've been building native apps, and the tech underneath them, since before the app stores existed. I won Google's first Android Developer Challenge, co-founded ShopSavvy (40M+ downloads), and these days I'm working on the open web's next chapter at [The Web4 Foundation](https://github.com/web4foundation), where most of my code lives.

<a href="https://github.com/web4foundation">
    <picture>
        <source srcset="https://brand.web4.dev/web4/header/dark.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/web4/header/light.svg">
    </picture>
</a>

### 🌐 Now

**BDFL · [The Web4 Foundation](https://github.com/web4foundation)** · 2023–present

A nonprofit (formal status in progress) with a mission to advance the open web through its fourth chapter: local-first, native webapps. Like W3C and WHATWG, Web4 stewards, defines, and extends open web standards. Because Web4 runs outside the browser, it works with language communities rather than browser vendors, supporting consistent implementations across every language to maximize skill portability and minimize framework fatigue.

- **XTML** — Compile HTML into its own binary (`html.exe` or `html.wasm`). Like JSX, except instead of putting HTML inside your JS, you put compiled langs inside your HTML.
- **Keyholes** — The DOM's doorway to other languages. Like React, but runs from WASM or the server, with hardware-accelerated reconciliation and remote interop with the DOM.
- **Web4 SDK for .NET** — The reference implementation and the first of many SDKs to come. It started with C# because this species of webapp has a lot in common with video game dev.

**Principal Mobile Architect · Concord Finance** · 2022–present

Designed and built Concord's native apps as a team of one: SwiftUI on iOS and Kotlin/Compose on Android, architected as line-for-line ports of each other. Concord is a P/E rollup with several legacy backends, so I inverted the architecture: each backend implements its own logic and API access and drives one shared UI through a single ViewModel, swapped at runtime based on the login. The result is 100% reuse of the UI layer.

### 🛒 ShopSavvy · 2008–2022

**Cofounder & CTO.** ShopSavvy began as a mobile app for scanning barcodes, comparing prices, and reading reviews.

- Live in Google's app store the day Android launched
- 40M+ downloads, ranked as high as #1 in its category and #14 overall
- Series A from Facebook cofounder Eduardo Saverin in 2011
- Acquired by Purch in 2015, where I was VP Software Engineering, Mobile & Emerging Platforms (2015–2018)
- Bought back from Purch in 2018 through Monolith, LLC, where I was Cofounder & CTO (2018–2022)

A few things I built there:

- **Meatloaf** ([demo](https://www.youtube.com/watch?v=QSlpodFvXKY)) — A barcode scanner for early iPhones, whose fixed-focus cameras made every barcode blurry. Instead of deblurring the image, it pre-blurred known barcode patterns and matched them one digit at a time. Licensed to Macy's and Sam's Club.
- **Chalupa** ([demo](https://www.youtube.com/watch?v=hvj8EgUxUac)) — Meatloaf running in the cloud, racing the on-device decoder. It sent single 320-byte greyscale scanlines over UDP, like a multiplayer game server, and handled Black Friday peaks on 7 servers.
- **QuickPay** ([demo](https://www.youtube.com/watch?v=jbzSqDeBzYo)) — A patented, zero-keyboard agentic checkout that completed a retailer's whole checkout flow in the background, saving roughly 150 keystrokes.
- **Native/browser hybrid** ([demo](https://www.youtube.com/watch?v=T3pe9nLnNyI)) — A shopping browser that minimized into an overlay drawer on product pages, with native price comparison on top of the webpage.
- **Offline social shopping feed** — Local-first data for friends' posts and optimistic updates for your own.

### 🏆 Earlier

- **GoCart** (2008) — First prize ($275,000) in Google's Android Developer Challenge, out of 1,788 entries from 70+ countries. Built on Android's beta SDK, it became ShopSavvy, launched with the T-Mobile G1, and appeared in T-Mobile commercials.
- **XImage** (2011–2015) — Web server middleware for GPU-accelerated, just-in-time image transformations driven by the query string. It served billions of images.
- **PriceNark** (2004–2010) — Real-time price comparison that parsed HTML as packets arrived and streamed prices back over chunked HTTP, often showing a retailer's price faster than its own website could.
- **Veritix, now AXS** (2006–2008) — Built the first known JavaScript seat picker, with isometric 3D venue maps, when competitors used Flash. Also built a touch-screen ticket kiosk with physics-based scrolling, pre-iPhone.
- **Software Architects, now Pariveda** (2006) — Consultant working on UI and large databases.
- **HP** (2004–2005) — Co-op and intern doing web development in the server division.

### 🎓 Education

**Texas A&M University** — BS, Computer Engineering (2005). Led a team that built a robotic chess board: an FPGA drove two servos that moved an electromagnet under the board, playing against a modified WinBoard chess AI.

### 🎨 Design

I've been designing UI since the '90s, first in GIMP and Photoshop and now mostly in Figma. I've designed logos for Web4, ShopSavvy, and Village Table, and I have some interesting takes on UI design. Ask me about them sometime.
