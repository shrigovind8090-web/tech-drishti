# Tech Drishti

A professional, fully online platform — live news, weather,
a free AI assistant, market rates, knowledge search and a first-class
accessibility mode, all in one place.

No installation. No sign-in. No API keys. Everything runs in the browser.

## Sections

- **Home** — live clock, weather for your current location, top headlines and market glance.
- **Live News** — headlines from Google News with a **language selector** (English, हिन्दी, தமிழ், తెలుగు, বাংলা, मराठी, ગુજરાતી, ಕನ್ನಡ, മലയാളം, ਪੰਜਾਬੀ, اردو) and a **category filter** (Top stories, India, World, Business, Technology, Sports, Entertainment, Health, Science), plus **city news** for your location or any city you type.
- **Weather** — current conditions and a 5-day forecast for wherever you are, or any city you search.
- **AI Assistant** — a chat assistant that needs **no API key** and answers in English or any Indian language, with voice input.
- **Tools** — live currency converter, live crypto prices (USD and INR), and instant Wikipedia knowledge search.
- **Accessibility** — a dedicated mode for visually impaired users: read-anything-aloud, voice search, high contrast, dyslexia-friendly font, adjustable text size, reduced motion, and full keyboard shortcuts.
- **Profile** — your private profile, plus About &amp; Support and the legal pages (Privacy Policy, Terms of Service, data sources).

## Live data sources

| Data | Source |
|---|---|
| Weather &amp; city search | Open-Meteo |
| News headlines | Google News, via a public CORS relay (with a Wikipedia world-news fallback) |
| Exchange rates | European Central Bank (Frankfurter) and the fawcet-ahmed currency API |
| Crypto prices | CoinGecko (with a currency-api fallback) |
| Knowledge summaries | Wikipedia |
| AI answers | A public, key-free open text endpoint |

Every feed has a fallback, and the interface says plainly which source answered.

## Privacy

Tech Drishti collects nothing. There is no server, no analytics and no tracking.
Your name and preferences stay in your own browser's local storage. Location is
used only when you press a location button, only to fetch your local weather and
news.

## Deploy it yourself

This is a single static `index.html` — host it anywhere.

**Netlify:** drag this folder onto <https://app.netlify.com/drop>, or connect
this repository and Netlify will publish it automatically (`netlify.toml` is
already set to publish the root folder).

**Anywhere else:** copy `index.html` to any web host. There is no build step.

## Developer

- GitHub: <https://github.com/shrigovind8090-web>
- Email: <mailto:shrigovind8090@gmail.com>
- Telegram: <https://t.me/Techdrishti>

## Live sites

- **Netlify (main):** <https://techdrishti.netlify.app>
- **GitHub Pages (backup):** <https://shrigovind8090-web.github.io/tech-drishti/>

Every push to this repository is published automatically to both.
