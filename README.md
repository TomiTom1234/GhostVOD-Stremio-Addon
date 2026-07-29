# 👻 GhostVOD Engine for Stremio/Nuvio

<p align="center">
  <a href="https://ghostvod.online" target="_blank">
    <img src="https://ghostvod.online/logo.png" alt="GhostVOD Logo" width="120" height="120" style="border-radius: 12px;">
  </a>
</p>
**Combine Multiple XC API / M3U Media Playlists into One Unified, Clean Catalog!**

If you manage one or multiple remote media playlists or personal video servers, you probably hate having to switch to a clunky third-party player just to watch a movie. Stremio is the ultimate media center, so why not bring your personal remote VODs directly into it, fully cleaned and organized alongside your Debrid links?

GhostVOD is a smart, stateless engine that acts as a bridge between your custom data providers and Stremio. It completely ignores linear live feeds and focuses strictly on VOD (Movies & Series).

## 🔥 Key Features (Updated for v2.0.7)

📂 **Smart Native Episode Support:** Intelligently parses and renders real TV series seasons and episodes directly inside the interface, instead of stacking them unorganized in the source list.

📋 **Instant M3U Extraction:** Paste either your Xtream Codes API credentials OR a full M3U Playlist URL. The engine instantly extracts the credentials on-the-fly.

✅ **Smart Bulk Category Selection:** Pin specific provider folders to your home screen! You now have full freedom to select all categories (up to 1,000) using the "Select All" toggle. To protect your Smart TV or Firestick from freezing, an elegant smart warning will alert you if your provider has over 50 categories, letting you proceed at your own risk while keeping your app interface lightweight.

📝 **Custom Provider Aliases:** Label your servers with custom names (e.g., "My Backup Server") to display directly on your screen instead of exposing raw domain names.

🔀 **Custom Stream Sorting:** Prioritize your stream results based on your preferred Language (e.g., Arabic, Spanish, French) or Quality (4K, 1080p).

🛡️ **IPTV Firewall Shield (Anti-Ban):** Built-in query rate-limiting and concurrent request queues ensure that your IPTV provider is never spammed with heavy requests, keeping your subscription 100% safe.

💾 **Local Settings Manager:** Securely save your configuration setup locally in your browser's storage for easy future edits.

---

## 🚀 How to Use (Free Web Dashboard)

You do not need to download or install any files to use GhostVOD. Simply visit our Web Dashboard, configure your server, and generate your Magic Link to install directly into Stremio/Nuvio:

👉 **[Click Here to Open GhostVOD Dashboard](https://ghostvod.online)**
👉 **[Or the official public Stremio Addons index](https://stremio-addons.net/addons/ghostvod)**

---

## 💬 Frequently Asked Questions (FAQ)

**Q1: Can I use an M3U link, or does it only accept Xtream Codes?** 

A: You can use either! Our dashboard allows you to paste a full M3U Playlist URL. The engine will instantly and automatically extract the server URL, username, and password from it.

**Q2: Do I *have* to fetch and add provider catalogs to my home screen to see my VODs?** 

A: Not at all! If you prefer a clean home screen, you can skip adding categories completely. GhostVOD operates silently in the background (Streams-Only Mode). Whenever you search for or click on any movie/series in Stremio/Nuvio, GhostVOD will automatically fetch and display your provider's streams in the source list.

**Q3: Will using GhostVOD cause my IPTV provider to ban or block my subscription?** 

A: Absolutely not; your account is 100% safe. GhostVOD is built with an "IPTV Firewall Shield." It uses an aggressive caching system (saving lists for 48 hours) and a strict request queue. Even if hundreds of users click the same movie, your provider only receives *one* single request. GhostVOD acts as a protective shield for your provider, not a burden.
*Please note:* Most IPTV providers strictly limit subscriptions to **one single active stream at a time**. Attempting to stream on multiple devices simultaneously may cause your provider to suspend your account, unless extra connections are purchased. This is a standard provider policy regarding concurrent streaming and is entirely unrelated to GhostVOD.

**Q4: Why wouldn't I just use a traditional player (like TiviMate) for my Xtream codes?** 

A: Traditional players are unbeatable for Live TV! But for VOD, Stremio/Nuvio’s ecosystem, metadata tracking, and UI are simply on another level. GhostVOD is built specifically to leverage your existing private VOD libraries inside a modern cinematic interface.

**Q5: Does it fetch stream quality and metadata? How does quality display work?** 

A: Yes! The engine dynamically extracts the resolution (e.g., 4K, 1080p) and any audio tags directly from your provider's stream title and displays them clearly as visual badges in the stream selection list before you play.

**Q6: Does it auto-update when my provider adds new movies or episodes?** 

A: Yes! GhostVOD queries your providers' APIs dynamically. The moment your provider updates their server with new content, it will automatically become searchable and ready to stream in your app within **24 hours** (matching our optimized cloud caching cycle). No manual syncing or link generation is ever required on your end.

**Q7: Do I need to generate a new Magic Link every time GhostVOD updates to a new version?** 

A: No! GhostVOD core updates (like performance boosts or anti-ban features) are processed completely on our cloud backend. Your existing Magic Links will continue to work seamlessly and automatically benefit from the latest upgrades without any action required on your end.

**Q8: Does it support Stalker/MAC portals?** 

A: No. GhostVOD strictly accepts Xtream Codes API credentials and M3U links.

**Q9: Does this pull Live TV channels?** 

A: No, to keep your interface clean and fast, GhostVOD intentionally filters out Live TV and focuses 100% on VODs (Movies and Series). Use dedicated players for your live broadcasting needs.

**Q10: Is this open-source? Can I self-host it?** 

A: Not yet, but it is officially on the roadmap! I am currently preparing a lightweight open-source version specifically designed for self-hosting.

---

**⚖️ Disclaimer:** *GhostVOD is a pure software engine/tool. We do not host, provide, or stream any media content, nor do we sell streaming subscriptions or access codes. Users are solely responsible for their own media sources and compliance with local laws.*
