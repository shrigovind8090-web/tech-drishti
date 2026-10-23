# Tech Drishti

A professional, fully online platform — live news, weather,
a free AI assistant, market rates, knowledge search and a first-class
accessibility mode, all in one place.

No installation. No API keys. Everything runs in the browser. You can sign in
with Google or an email address to keep your profile, or continue as a guest.

## Sections — three tabs

The whole platform lives in **three bottom tabs** (Home · Tools · Assistant), with a **Back button**
at the top of every inner screen. Profile and Settings open from the avatar button in the header.

- **Home** — live clock, weather for your location, top headlines and market glance.
- **Tools** — a menu; tap one to open just that tool:
  - **Live News** — Google News headlines with a **language selector** (English, हिन्दी, தமிழ், తెలుగు, বাংলা, मराठी, ગુજરાતી, ಕನ್ನಡ, മലയാളം, ਪੰਜਾਬੀ, اردو), a **category filter**, **city news**, and a **Share** button on every headline.
  - **Weather** — current conditions plus rain chance, sunrise/sunset, UV index and a 5-day forecast, with read-aloud.
  - **Markets & knowledge** — currency converter, crypto prices and Wikipedia knowledge search.
  - **Calculator** — big buttons, works fully offline, reads the answer aloud.
  - **Timer & stopwatch** — counts down or up and says "Time is up" aloud.
  - **My notes** — write or **dictate** a note; saved on your device and readable aloud.
- **Assistant** — free AI, no API key. It knows today's live data from this site (your weather, the
  current headlines, the dollar rate) and answers in your own language. One-tap chips included.
- **Profile** — your account, **Settings → Accessibility** (contrast, text size, voice feedback on/off,
  reading speed), About & Support and the legal pages.


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

You can use Tech Drishti as a guest — in guest mode we receive nothing about you.
If you sign in, we receive only your name, email address and (for Google) your
profile photo; the account is created and stored by Firebase Authentication, and
we never see or store your password. There are no ads, no trackers and no
analytics. Your preferences and your AI conversation stay in your own browser's
local storage. Location is used only when you press a location button, only to
fetch your local weather and news. To delete your account, email us and we will
remove it.

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
