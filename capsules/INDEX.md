# 🌐 The Ultra Global Internet Time Capsule

## 📦 The Most Complete Open Digital Archive

### 🌍 Global Coverage

| Category | Sources | Coverage |
|----------|---------|----------|
| 💻 Tech | GitHub, HN, Reddit, StackOverflow | Global |
| 📚 Knowledge | Wikipedia (15 lang) | Worldwide |
| 💰 Finance | Forex (160), Crypto (30), Stocks (12) | Worldwide |
| ⚽ Sports | NBA, EPL, La Liga, MLB, F1 | Global |
| 🗞️ News | US, China, UK, India, Brazil | 5 countries |
| 🌤️ Climate | 25 cities, Air Quality (5) | 6 continents |
| 🌋 Nature | USGS Earthquakes | Global |
| 🛰️ Space | NASA, ISS | Orbital |
| 🌍 World | 195 countries, Holidays | Complete |

### 🗂 Browse by Date

$(for year_dir in capsules/*/; do
  year=$(basename "$year_dir")
  if [[ "$year" =~ ^[0-9]{4}$ ]]; then
    echo "- [📁 ${year}](./capsules/${year}/)"
  fi
done)

---
*Updated daily at 00:00 UTC — Zero cost — Open forever*
