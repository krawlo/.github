# 🌐 Krawlo

High-performance data extraction, intelligent scraping engines, and real-time enterprise APIs.

---

## 🚆 Featured APIs & Actors

### **[Indian Railways (CRIS / NTES) Real-Time API](https://apify.com/krawlo/indian-railways-realtime-api)**
Enterprise-grade, zero-compromise real-time telemetry and schedule data directly from official CRIS/NTES infrastructure with military-grade AES encryption support.

* 🔗 **Apify Store:** [krawlo/indian-railways-realtime-api](https://apify.com/krawlo/indian-railways-realtime-api)
* ⚡ **High-Performance Standby Endpoint:** [https://krawlo--indian-railways-realtime-api.apify.actor](https://krawlo--indian-railways-realtime-api.apify.actor)
* 🤖 **Native MCP Server:** Stdio & SSE integration for Claude Desktop, Cursor, and LLM coding assistants.

#### Core Capabilities:
- 🟢 **Live Train Running Status:** GPS telemetry, current delay, last/next stoppage, distance traveled, and scheduled vs actual times.
- 🕒 **Train Route & Timetable:** Master schedule, halt durations, distance matrix, and day counts.
- 🔄 **Trains Between Stations:** Route discovery between any station pair with classes and departure/arrival times.
- 📋 **Live Station Departure Board:** Real-time 2h, 4h, and 8h arrival/departure window with platform announcements and delay tracking.
- 🚃 **Coach Position Finder:** Full coach composition sequence (S1, S2, B1, A1, GEN), engine placement, and platform location mapping (Front, Middle, Rear).
- ⏱️ **Intermediate Station ETA:** Precision arrival/departure and delay predictions for any stoppage along a train\'s journey.
- 🔔 **Platform Change Alerts:** Station-wide mismatch detector comparing scheduled vs. announced live platform numbers.

---

## 🛠️ Technology Stack & Standards
- **Languages & Frameworks:** Python 3.12+, Requests, Apify SDK, Crawlee, FastMCP.
- **Reliability:** Built-in circuit breakers, automatic exponential backoffs, legacy TLS compatibility adapters, and Indian residential proxy rotation.
- **Strict Data Validation:** Typed schemas, zero fake/fallback projections on non-running days, and deterministic exception handling.

---

## 📬 Contact & Support
* 🌐 **Apify Profile:** [@krawlo](https://apify.com/krawlo)
* 📧 **Support & Custom Inquiries:** [indrohelpdesk@gmail.com](mailto:indrohelpdesk@gmail.com)
* 💼 **Custom Scrapers & Enterprise Integrations:** Available for custom scraping, data pipeline, and actor development.
