# 👻 GhostVOD Engine for Stremio/Nuvio

**Combine Multiple XC API / M3U Media Playlists into One Unified, Clean Catalog!**

If you manage one or multiple remote media playlists or personal video servers, you probably hate having to switch to a clunky third-party player just to watch a movie. Stremio is the ultimate media center, so why not bring your personal remote VODs directly into it, fully cleaned and organized alongside your Debrid links?

GhostVOD is a smart, stateless engine that acts as a bridge between your custom data providers and Stremio. It completely ignores linear live feeds and focuses strictly on VOD (Movies & Series).

## 🔥 Key Features (Updated for v2.0.0)

📌 Native Home Screen Catalogs: Optionally display specific provider folders directly on your Stremio/Nuvio home screen. This enables global search for local/regional content that isn't indexed in standard databases like Cinemeta.

🔀 Custom Stream Sorting: Prioritize your stream results based on your preferred Language (e.g., Arabic, French, German) or Quality (4K, 1080p).

🏷️ Visual Stream Badges: The engine parses titles on-the-fly and adds dynamic badges (4K, HD, Dual-Audio, Multi-Sub) directly into the stream selection menu.

🧠 Zero-Cost Hover Metadata: Instantly see IMDb ratings, release years, and genres on media cards while scrolling, without triggering heavy server loads.

⚡ Enterprise-Grade Stability: Built on a custom lightweight caching system that prevents memory leaks, ensuring lightning-fast load times even with massive media libraries (100k+ items).

🚫 VOD Only & Zero Pollution: It ignores live feeds entirely. You decide exactly which folders clutter your screen, keeping your media center pristine.

🔒 Transparent & Stateless: Each stream explicitly shows its origin domain. Zero user credentials or playlists are stored on our servers; everything is dynamically processed on-demand.

---

## 🚀 How to Use (Free Web Dashboard)

You do not need to download or install any files to use GhostVOD. Simply visit our Web Dashboard, enter your server credentials, and generate your Magic Link to install directly into Stremio/Nuvio:

👉 **[Click Here to Open GhostVOD Dashboard](https://ghostvod.online)**
👉 **[Or the official public Stremio Addons index](https://stremio-addons.net/addons/ghostvod)**

---

## 💬 Frequently Asked Questions (FAQ)

**Q1: Why wouldn't I just use a traditional player (like TiviMate) for my Xtream codes?**

A: Traditional players are unbeatable for Live TV, and I still use them for that! But for VOD, Nuvio’s ecosystem, metadata tracking, and UI are simply on another level. GhostVOD is built specifically for users who want to leverage their existing private VOD libraries inside Nuvio without needing to pay for separate Debrid services or rely on slow public scrapers.

**Q2: Does it fetch stream quality and metadata? How does quality display work?**

A: Yes! The engine dynamically extracts the resolution (e.g., 4K, 1080p) and any audio tags directly from your provider's stream title and displays them clearly in Nuvio's stream selection list before you play. However, if you mean displaying live technical metadata (like exact resolution, bitrate, or codec) during video playback, that depends entirely on Nuvio’s built-in video player capabilities, just as it does in standard media players. *(Note: File sizes are not shown, as standard Xtream APIs do not pass file size payloads in their stream lists).*

**Q3: Does it auto-update when my provider adds new movies or episodes?**

A: Absolutely! Because GhostVOD is a 100% stateless gateway, it queries your providers' APIs dynamically on-demand. The moment your provider adds a new movie or episode to their server, it becomes instantly searchable and ready to stream in Nuvio without requiring any manual syncing on your end.

**Q4: Is this open-source? Can I self-host it?**

A: Not yet, but it is officially on the roadmap! I am currently preparing a lightweight open-source version specifically designed for self-hosting.

--

**⚖️ Disclaimer:** *GhostVOD is a pure software engine/tool. We do not host, provide, or stream any media content, nor do we sell streaming subscriptions or access codes. Users are solely responsible for their own media sources and compliance with local laws.*
