<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HesGoal Live Hub</title>
  <style>
    :root {
      color-scheme: dark;
      --bg: #030712;
      --bg-alt: #0b1020;
      --card: #11172d;
      --accent: #2fff9f;
      --accent-soft: rgba(47, 255, 159, 0.2);
      --text: #e4e9ff;
      --muted: #98a1c0;
      --danger: #ff5f7b;
      font-family: "Segoe UI", "Inter", system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      
      padding: 0;
    }

    body {
      background: radial-gradient(circle at top, #101b3d, var(--bg));
      color: var(--text);
      min-height: 100vh;
    }

    body.light-mode {
      --bg: #f7f8ff;
      --bg-alt: #edf0ff;
      --card: #ffffff;
      --accent: #167dff;
      --accent-soft: rgba(22, 125, 255, 0.15);
      --text: #0b1020;
      --muted: #0b1020;
      --danger: #d22f5b;
      background: linear-gradient(180deg, #f7f9ff, #eef2ff);
      color: #0b1020;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .page {
      max-width: 1200px;
      margin: 0 auto;
      padding: 32px 20px 80px;
      display: flex;
      flex-direction: column;
      gap: 24px;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 16px;
      flex-wrap: wrap;
    }

    .logo {
      font-size: 1.5rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.1em;
    }

    .nav-links {
      display: flex;
      gap: 18px;
      font-weight: 500;
      color: var(--muted);
      padding: 10px 20px;
      border-radius: 999px;
      background: rgba(17, 23, 45, 0.7);
      border: 1px solid rgba(255, 255, 255, 0.05);
    }

    body.light-mode .nav-links {
      background: rgba(255, 255, 255, 0.9);
      border-color: rgba(11, 16, 32, 0.08);
    }

    .nav-links a:hover {
      color: var(--accent);
    }

    .nav-categories {
      display: flex;
      align-items: center;
      gap: 12px;
      padding: 8px 0 4px;
      overflow-x: auto;
      scroll-snap-type: x proximity;
      border-bottom: 1px solid rgba(255, 255, 255, 0.08);
    }

    .nav-categories::-webkit-scrollbar {
      display: none;
    }

    .category-pill {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 8px 14px;
      border-radius: 999px;
      background: rgba(17, 23, 45, 0.8);
      border: 1px solid rgba(255, 255, 255, 0.08);
      color: var(--text);
      font-size: 0.9rem;
      font-weight: 600;
      scroll-snap-align: center;
      transition: background 0.2s ease, border-color 0.2s ease;
      cursor: pointer;
    }

    .category-pill:hover {
      background: rgba(47, 255, 159, 0.15);
      border-color: var(--accent);
    }

    .category-pill.active {
      background: rgba(47, 255, 159, 0.2);
      border-color: var(--accent);
      color: var(--text);
    }

    .category-pill img {
      width: 20px;
      height: 20px;
      object-fit: contain;
      filter: drop-shadow(0 0 6px rgba(0, 0, 0, 0.4));
    }

    body.light-mode .category-pill {
      background: rgba(255, 255, 255, 0.9);
      border-color: rgba(11, 16, 32, 0.08);
    }

    .header-tagline {
      background: rgba(7, 10, 20, 0.7);
      border-radius: 16px;
      padding: 16px 20px;
      border: 1px solid rgba(255, 255, 255, 0.05);
      color: var(--muted);
    }

    .header-tagline strong {
      display: block;
      font-size: 1.1rem;
      color: var(--text);
      margin-bottom: 6px;
    }

    .tagline-links {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      margin-top: 6px;
    }

    .tagline-links a {
      color: var(--accent);
      font-weight: 600;
    }

    .search-panel {
      display: flex;
      flex-direction: column;
      gap: 8px;
      padding: 16px 0;
    }

    .search-input {
      width: 100%;
      padding: 12px 16px;
      border-radius: 999px;
      border: 1px solid rgba(255, 255, 255, 0.12);
      background: rgba(17, 23, 45, 0.8);
      color: var(--text);
      font-size: 0.95rem;
      outline: none;
    }

    body.light-mode .search-input {
      background: rgba(255, 255, 255, 0.9);
      border-color: rgba(11, 16, 32, 0.08);
      color: #0b1020;
    }

    .search-input::placeholder {
      color: rgba(228, 233, 255, 0.4);
    }

    .search-hint {
      font-size: 0.85rem;
      color: var(--muted);
    }

    .streams-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 18px;
      align-items: start;
      justify-items: center;
    }

    .stream-card {
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      gap: 12px;
      padding: 18px;
      background: var(--card);
      border-radius: 20px;
      border: 1px solid rgba(255, 255, 255, 0.06);
      aspect-ratio: 1 / 1;
      box-shadow: inset 0 0 20px rgba(0, 0, 0, 0.25);
      width: 100%;
      max-width: 360px;
    }

    .stream-top {
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 0.85rem;
      color: var(--muted);
      gap: 6px;
    }

    .kickoff-pill {
      padding: 4px 10px;
      border-radius: 999px;
      background: rgba(255, 255, 255, 0.05);
      font-size: 0.8rem;
    }

    .teams-square {
      flex: 1;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 10px;
      text-transform: uppercase;
    }

    .team-side {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 8px;
      flex: 1;
      text-align: center;
      color: var(--text);
      font-weight: 600;
      font-size: 0.95rem;
    }

    .team-side img {
      width: 64px;
      height: 64px;
      border-radius: 16px;
      background: rgba(255, 255, 255, 0.04);
      object-fit: contain;
      padding: 8px;
    }

    .vs-chip {
      font-size: 0.8rem;
      letter-spacing: 0.3em;
      color: var(--muted);
    }

    .stream-title {
      font-size: 0.95rem;
      font-weight: 600;
      text-align: center;
    }

    .stream-actions {
      display: flex;
      justify-content: center;
      gap: 8px;
      flex-wrap: wrap;
    }

    .watch-btn {
      padding: 10px 18px;
      border-radius: 999px;
      border: 1px solid rgba(255, 255, 255, 0.1);
      background: rgba(255, 255, 255, 0.02);
      color: var(--text);
      font-weight: 600;
      font-size: 0.9rem;
      cursor: pointer;
      transition: background 0.2s ease, color 0.2s ease;
    }

    .watch-btn.primary {
      background: var(--accent);
      color: #08111f;
      border-color: transparent;
    }

    .watch-btn:hover {
      background: rgba(47, 255, 159, 0.2);
      color: var(--text);
    }

    .stream-info {
      font-size: 0.85rem;
      color: var(--muted);
      line-height: 1.5;
    }

    .seo-section {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 18px;
    }

    .seo-card {
      background: var(--card);
      border-radius: 18px;
      padding: 18px;
      border: 1px solid rgba(255, 255, 255, 0.05);
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .seo-card h3 {
      font-size: 1rem;
      color: var(--text);
    }

    .seo-card p {
      color: var(--muted);
      font-size: 0.9rem;
      line-height: 1.6;
    }

    .seo-card ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
      margin-top: 6px;
    }

    .seo-card li {
      padding: 4px 10px;
      border-radius: 999px;
      background: rgba(255, 255, 255, 0.08);
      font-size: 0.8rem;
      color: var(--muted);
    }

    .seo-card strong {
      color: var(--accent);
      font-weight: 600;
    }

    .theme-toggle {
      border: 1px solid rgba(255, 255, 255, 0.3);
      background: rgba(17, 23, 45, 0.7);
      color: var(--text);
      font-weight: 600;
      border-radius: 999px;
      padding: 8px 16px;
      cursor: pointer;
      transition: background 0.2s ease, color 0.2s ease;
    }

    .theme-toggle:hover {
      background: rgba(255, 255, 255, 0.1);
    }

    body.light-mode .theme-toggle {
      border-color: rgba(11, 16, 32, 0.1);
      background: rgba(255, 255, 255, 0.9);
      color: #0b1020;
    }

    .live-banner {
      padding: 28px;
      border-radius: 20px;
      background: linear-gradient(135deg, #1a2547, #0e172d);
      position: relative;
      overflow: hidden;
    }

    .live-indicator {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 6px 14px;
      border-radius: 999px;
      background: rgba(255, 95, 123, 0.16);
      color: var(--danger);
      font-size: 0.85rem;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.08em;
    }

    .pulse {
      width: 10px;
      height: 10px;
      border-radius: 50%;
      background: currentColor;
      position: relative;
    }

    .pulse::after {
      content: "";
      position: absolute;
      inset: 0;
      border-radius: 50%;
      border: 1px solid currentColor;
      animation: pulse 1.6s infinite;
    }

    @keyframes pulse {
      from {
        transform: scale(0.6);
        opacity: 1;
      }

      to {
        transform: scale(2);
        opacity: 0;
      }
    }

    .banner-content {
      margin-top: 18px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 24px;
      align-items: center;
    }

    .banner-text h1 {
      font-size: clamp(1.8rem, 4vw, 2.6rem);
      margin-bottom: 12px;
    }

    .banner-text p {
      color: var(--muted);
    }

    .cta-group {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      margin-top: 20px;
    }

    .btn {
      border: none;
      border-radius: 999px;
      padding: 12px 22px;
      font-size: 0.95rem;
      font-weight: 600;
      cursor: pointer;
    }

    .btn.primary {
      background: var(--accent);
      color: #0f172a;
    }

    .btn.secondary {
      border: 1px solid rgba(255, 255, 255, 0.2);
      background: transparent;
      color: var(--text);
    }

    section {
      background: rgba(7, 10, 20, 0.6);
      border-radius: 20px;
      padding: 24px;
      border: 1px solid rgba(255, 255, 255, 0.05);
      box-shadow: 0 40px 120px rgba(0, 0, 0, 0.35);
    }

    section h2 {
      display: flex;
      align-items: center;
      gap: 10px;
      font-size: 1.2rem;
      margin-bottom: 18px;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      color: var(--muted);
    }

    section h2::before {
      content: "";
      width: 32px;
      height: 2px;
      background: var(--accent);
    }

    .match-grid,
    .highlight-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 16px;
    }

    .match-card {
      background: var(--card);
      border-radius: 16px;
      padding: 18px;
      display: flex;
      flex-direction: column;
      gap: 14px;
      border: 1px solid rgba(255, 255, 255, 0.04);
    }

    .match-league {
      font-size: 0.85rem;
      color: var(--muted);
    }

    .match-score {
      display: flex;
      align-items: center;
      justify-content: space-between;
      font-size: 1.5rem;
      font-weight: 700;
    }

    .match-team {
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .match-status {
      font-size: 0.85rem;
      color: var(--accent);
      text-transform: uppercase;
      letter-spacing: 0.08em;
    }

    .tag {
      padding: 4px 10px;
      border-radius: 999px;
      font-size: 0.75rem;
      font-weight: 600;
      background: rgba(255, 255, 255, 0.08);
      color: var(--muted);
    }

    .highlight-card {
      background: var(--card);
      border-radius: 16px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      border: 1px solid rgba(255, 255, 255, 0.04);
    }

    .highlight-thumb {
      aspect-ratio: 16/9;
      background: linear-gradient(135deg, rgba(47, 255, 159, 0.2), rgba(15, 23, 42, 0.9));
      position: relative;
      display: grid;
      place-items: center;
      font-size: 2.4rem;
      color: rgba(255, 255, 255, 0.4);
    }

    .highlight-body {
      padding: 16px 18px 24px;
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .news-list {
      display: flex;
      flex-direction: column;
      gap: 18px;
    }

    .news-item {
      display: flex;
      flex-direction: column;
      gap: 6px;
      border-bottom: 1px solid rgba(255, 255, 255, 0.05);
      padding-bottom: 12px;
    }

    .news-item:last-child {
      border-bottom: none;
      padding-bottom: 0;
    }

    footer {
      text-align: center;
      color: var(--muted);
      font-size: 0.85rem;
      padding-bottom: 30px;
    }

    .api-status {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      font-size: 0.85rem;
    }

    .status-dot {
      width: 8px;
      height: 8px;
      border-radius: 50%;
      background: var(--muted);
    }

    .status-dot.online {
      background: #12f08a;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }

      .nav-links {
        flex-wrap: wrap;
      }
    }
  </style>
</head>
<body>
  <div class="page">
    <header>
      <div class="logo">HesGoal Live</div>
      <nav class="nav-links">
        <a href="#live-matches">Live</a>
        <a href="#upcoming">Upcoming</a>
        <a href="#highlights">Highlights</a>
        <a href="#news">News</a>
      </nav>
      <div class="api-status">
        <span class="status-dot" id="apiStatusDot"></span>
        <span id="apiStatusLabel">Checking API…</span>
      </div>
      <button class="theme-toggle" id="themeToggle" type="button">Dark Mode</button>
    </header>
    <div class="header-tagline">
      <strong>Hesgoal Live HD</strong>
      Watch your favorite matches live in high quality
      <div class="tagline-links">
        <a href="https://hesgoal.com" target="_blank" rel="noreferrer noopener">Hesgoal</a>
        <a href="https://evogoal.com" target="_blank" rel="noreferrer noopener">EvoGoal</a>
      </div>
    </div>
    <div class="nav-categories" id="navCategories" aria-live="polite"></div>
    <div class="search-panel">
      <input
        type="search"
        id="streamSearch"
        class="search-input"
        placeholder="Search teams, leagues, channels or keywords..."
        autocomplete="off"
      />
      <span class="search-hint">Try “Barcelona”, “NFL”, “StreamEast”, or channel codes like “ch2”.</span>
    </div>

    <section id="all-streams">
      <h2>All Live Streams</h2>
      <div class="streams-grid" id="streamsList">
        <p class="match-league">Loading streams…</p>
      </div>
    </section>

    <section id="stream-guides">
      <h2>Sports Streaming Guides</h2>
      <div class="seo-section">
        <article class="seo-card">
          <h3><strong>StreamEast</strong> Alternatives for HD Streams</h3>
          <p>
            Fans searching for <strong>StreamEast</strong> mirrors can bookmark HesGoal Live Hub as a safer, ad-light
            destination. We aggregate NBA, NFL, UFC, and EPL feeds with verified servers so you can
            watch without pop-up chaos. Pair our live stream grid with a VPN and you have a reliable
            replacement when <strong>StreamEast</strong>, <strong>VIPRow</strong>, or <strong>Buffstreams</strong> go offline.
          </p>
          <ul>
            <li>streameast</li>
            <li>viprow</li>
            <li>buffstreams</li>
          </ul>
        </article>
        <article class="seo-card">
          <h3><strong>CrackStreams</strong> vs Free Soccer Streams</h3>
          <p>
            <strong>CrackStreams</strong> caught fire with boxing and PPV coverage, but football fans still crave
            predictable schedules. Our API-driven cards track kickoff times for La Liga, Serie A, and
            MLS so you never miss a derby. Tap Watch to open our embed player, or copy the short
            player link to share with friends who usually rely on <strong>FreeSoccer</strong> or <strong>RojaDirecta</strong>.
          </p>
          <ul>
            <li>crackstreams</li>
            <li>freesoccer</li>
            <li>rojadirecta</li>
          </ul>
        </article>
        <article class="seo-card">
          <h3><strong>Sportsurge</strong> &amp; <strong>TotalSportek</strong> Companion</h3>
          <p>
            <strong>Sportsurge</strong> and <strong>TotalSportek</strong> are legendary for NFL RedZone and Champions League updates.
            We complement those hubs by embedding point-and-click servers for every category—soccer,
            NBA, NHL, and motorsport. Filter the navbar by sport, then launch our HesGoal-style player
            for a distraction-free stream in seconds.
          </p>
          <ul>
            <li>sportsurge</li>
            <li>totalsportek</li>
            <li>hesgoal</li>
          </ul>
        </article>
        <article class="seo-card">
          <h3>Free Sports <strong>IPTV</strong> Tips</h3>
          <p>
            Looking to replace legacy <strong>IPTV</strong> lists? Combine our schedule data with apps like <strong>Kodi</strong>,
            Tivimate, or VLC by dropping in the server URLs you grab from each Watch button. Your
            personalized “HesGoal playlist” works across smart TVs, Fire Stick, and iOS without hunting
            around Reddit threads for expired links.
          </p>
          <ul>
            <li>iptv</li>
            <li>kodi</li>
            <li>firestick</li>
          </ul>
        </article>
      </div>
    </section>

    <footer>
      Built for live football fans · Replace API endpoints inside `theme.html` with your own HesGoal data source.
    </footer>
  </div>

  <script>
    /**
     * Replace API_ENDPOINTS with your real services.
     * Expected response structure:
     * - /live: [{ league, homeTeam, awayTeam, homeScore, awayScore, status, kickoff }]
     * - /upcoming: same fields, scores optional
     * - /highlights: [{ title, duration, thumbnail, videoUrl }]
     * - /news: [{ title, source, published }]
     */
    const API_ENDPOINTS = {
      live: "https://api.example.com/matches/live",
      upcoming: "https://api.example.com/matches/upcoming",
      highlights: "https://api.example.com/highlights",
      news: "https://api.example.com/news"
    };
    const CATEGORY_ENDPOINT = "https://backendstreamcenter.youshop.pro:488/api/Categories";
    const STREAM_API_BASE = "https://backendstreamcenter.youshop.pro:488/api";
    const STREAMS_ENDPOINT = `${STREAM_API_BASE}/Parties?pageNumber=1&pageSize=500`;

    let cachedCategories = [];
    let allStreams = [];
    let selectedCategoryId = "all";
    let searchTerm = "";

    const apiStatusDot = document.getElementById("apiStatusDot");
    const apiStatusLabel = document.getElementById("apiStatusLabel");

    async function fetchJSON(url) {
      const controller = new AbortController();
      const timeout = setTimeout(() => controller.abort(), 7000);
      try {
        const res = await fetch(url, { signal: controller.signal });
        if (!res.ok) throw new Error("Request failed");
        const data = await res.json();
        return { data, ok: true };
      } catch (error) {
        console.warn("API fallback for", url, error.message);
        return { data: null, ok: false };
      } finally {
        clearTimeout(timeout);
      }
    }

    function updateApiStatus(isOnline) {
      apiStatusDot.classList.toggle("online", isOnline);
      apiStatusLabel.textContent = isOnline ? "API Connected" : "";
    }

    function renderMatchCard(match, isLive = false) {
      const {
        league,
        homeTeam,
        awayTeam,
        homeScore = 0,
        awayScore = 0,
        status = "",
        kickoff = ""
      } = match;

      return `
        <article class="match-card">
          <div class="match-league">${league}</div>
          <div class="match-score">
            <div class="match-team">
              <span class="tag">${homeTeam?.short || homeTeam?.slice(0, 3) || "H"}</span>
              ${homeTeam?.name || homeTeam}
            </div>
            <span>${isLive ? `${homeScore} - ${awayScore}` : kickoff || "—"}</span>
            <div class="match-team">
              <span class="tag">${awayTeam?.short || awayTeam?.slice(0, 3) || "A"}</span>
              ${awayTeam?.name || awayTeam}
            </div>
          </div>
          <div class="match-status">${isLive ? status || "Live" : status || "Starts soon"}</div>
        </article>
      `;
    }

    function renderHighlightCard(item) {
      return `
        <article class="highlight-card">
          <div class="highlight-thumb">
            ▶
          </div>
          <div class="highlight-body">
            <span class="tag">${item.duration || "02:30"}</span>
            <h3>${item.title}</h3>
            <a href="${item.videoUrl || "#"}" class="btn secondary" style="align-self:flex-start">Watch</a>
          </div>
        </article>
      `;
    }

    function renderNewsItem(story) {
      return `
        <article class="news-item">
          <h3>${story.title}</h3>
          <div class="match-league">${story.source} · ${story.published}</div>
        </article>
      `;
    }

    function mountHTML(el, html) {
      const target = document.getElementById(el);
      if (!target) return;
      target.innerHTML = html;
    }

    function fallbackData() {
      return {
        live: [
          {
            league: "Premier League",
            homeTeam: { name: "Manchester City", short: "MCI" },
            awayTeam: { name: "Liverpool", short: "LIV" },
            homeScore: 1,
            awayScore: 1,
            status: "42’ 1st Half"
          },
          {
            league: "La Liga",
            homeTeam: { name: "Barcelona", short: "BAR" },
            awayTeam: { name: "Real Madrid", short: "RMA" },
            homeScore: 0,
            awayScore: 0,
            status: "Kickoff 21:00 CET"
          }
        ],
        upcoming: [
          {
            league: "Serie A",
            homeTeam: { name: "Inter", short: "INT" },
            awayTeam: { name: "Juventus", short: "JUV" },
            status: "Tomorrow · 19:45"
          },
          {
            league: "Bundesliga",
            homeTeam: { name: "Bayern", short: "FCB" },
            awayTeam: { name: "Dortmund", short: "BVB" },
            status: "Sat · 18:30"
          }
        ],
        highlights: [
          { title: "City vs Arsenal - 6 Goal Thriller", duration: "06:42" },
          { title: "PSG demolish Lyon 5-1", duration: "03:58" }
        ],
        news: [
          { title: "Champions League Final Venue Confirmed", source: "UEFA Desk", published: "20 min ago" },
          { title: "Top 5 Transfers Heating Up", source: "Transfer Watch", published: "1 hr ago" },
          { title: "Injury Report: Key Strikers Out", source: "MatchCenter", published: "2 hrs ago" }
        ]
      };
    }

    function fallbackCategories() {
      return [
        { id: 9, name: "Football", sportCode: "Soccer", imagePath: "https://static.vecteezy.com/system/resources/previews/015/720/560/non_2x/abstract-creative-football-illustration-isolated-on-transparent-background-free-png.png", reverse: true },
        { id: 4, name: "Basketball", sportCode: "basketball", imagePath: "https://streamcenter.xyz/basketball.png", reverse: false },
        { id: 13, name: "Baseball", sportCode: "Baseball", imagePath: "https://streamcenter.xyz/Baseballicon.png", reverse: false },
        { id: 14, name: "American Football", sportCode: "Football", imagePath: "https://streamcenter.xyz/americanfootball.png", reverse: false },
        { id: 15, name: "Motor Sport", sportCode: "racing", imagePath: "https://cdn-icons-png.flaticon.com/512/4539/4539830.png", reverse: false },
        { id: 16, name: "Hockey", sportCode: "hockey", imagePath: "https://cdn-icons-png.flaticon.com/512/3153/3153881.png", reverse: false },
        { id: 17, name: "Fight MMA", sportCode: "mma", imagePath: "https://streamcenter.xyz/mma.png", reverse: false },
        { id: 18, name: "Boxing", sportCode: "boxing", imagePath: "https://cdn-icons-png.flaticon.com/512/2736/2736123.png", reverse: false },
        { id: 19, name: "NCAA Division", sportCode: "football", imagePath: "https://streamcenter.xyz/ncaa.png", reverse: false },
        { id: 20, name: "WWE", sportCode: "wwe", imagePath: "https://upload.wikimedia.org/wikipedia/commons/thumb/0/03/WWE_Logo.svg/2243px-WWE_Logo.svg.png", reverse: false },
        { id: 21, name: "Tennis", sportCode: "tennis", imagePath: "https://cdn-icons-png.flaticon.com/512/5022/5022062.png", reverse: false }
      ];
    }

    function renderCategoryPill(category) {
      return `
        <button class="category-pill" data-category-id="${category.id}" data-sport="${category.sportCode || ""}">
          ${category.imagePath ? `<img src="${category.imagePath}" alt="${category.name}" loading="lazy" />` : ""}
          <span>${category.name}</span>
        </button>
      `;
    }

    async function loadCategories() {
      const { data, ok } = await fetchJSON(CATEGORY_ENDPOINT);
      const apiCategories = Array.isArray(data) && data.length ? data : fallbackCategories();
      cachedCategories = apiCategories;
      const categoriesWithAll = [{ id: "all", name: "All Sports" }, ...apiCategories];
      mountHTML("navCategories", categoriesWithAll.map(renderCategoryPill).join(""));
      bindCategoryFilters();
      if (!ok) {
        console.warn("Using fallback categories");
      }
    }

    function fallbackStreams() {
      return [
        {
          id: 3877,
          categoryId: 15,
          name: "F1 Las Vegas GP Race",
          description: "F1 Las Vegas GP Race",
          logoTeam1: "https://streamcenter.xyz/motorsport.png",
          logoTeam2: "https://streamcenter.xyz/motorsport.png",
          videoUrl: "https://streamcenter.xyz/embed/ch99.php<English",
          beginPartie: "2025-11-18T03:00:00"
        },
        {
          id: 3867,
          categoryId: 9,
          name: "Slovakia vs Germany",
          description: "Slovakia at Germany - SVK @ GER",
          logoTeam1: "https://a.espncdn.com/i/teamlogos/countries/500/ger.png",
          logoTeam2: "https://a.espncdn.com/i/teamlogos/countries/500/svk.png",
          videoUrl: "https://streamcenter.xyz/embed/ch2.php<English",
          beginPartie: "2025-11-17T20:45:00"
        },
        {
          id: 3868,
          categoryId: 9,
          name: "Lithuania vs Netherlands",
          description: "Lithuania at Netherlands - LTU @ NED",
          logoTeam1: "https://a.espncdn.com/i/teamlogos/countries/500/ned.png",
          logoTeam2: "https://a.espncdn.com/i/teamlogos/countries/500/ltu.png",
          videoUrl: "https://streamcenter.xyz/embed/ch1.php<English",
          beginPartie: "2025-11-17T20:45:00"
        }
      ];
    }

    function formatKickoff(dateString) {
      if (!dateString) return "Kickoff TBA";
      const date = new Date(dateString);
      if (isNaN(date)) return dateString;
      const datePart = date.toLocaleDateString(undefined, { month: "short", day: "numeric" });
      const timePart = date.toLocaleTimeString([], { hour: "2-digit", minute: "2-digit" });
      return `${datePart} · ${timePart}`;
    }

    function extractStreams(game) {
      let raw = [];
      if (Array.isArray(game.streams) && game.streams.length) raw = game.streams;
      else if (Array.isArray(game.servers) && game.servers.length) raw = game.servers;
      else if (typeof game.videoUrl === "string" && game.videoUrl.length) {
        raw = game.videoUrl
          .split(";")
          .map(entry => entry.trim())
          .filter(Boolean)
          .map(entry => {
            const [url, label] = entry.split("<");
            return {
              url: url?.trim(),
              name: (label || "Stream").trim()
            };
          });
      }

      return raw
        .map((stream, index) => {
          if (typeof stream === "string") {
            return { url: stream, name: `Stream ${index + 1}` };
          }
          const url = stream.url || stream.stream;
          const name = stream.name || stream.label || `Stream ${index + 1}`;
          return url ? { url, name } : null;
        })
        .filter(Boolean);
    }

    function formatMatchTitle(game) {
      const raw = (game.name || game.gameName || "")
        .replace(/\s+\|\s+/g, " vs ")
        .replace(/\s+@\s+/gi, " vs ");
      if (raw.toLowerCase().includes(" vs ")) return raw;
      if (game.description && game.description.toLowerCase().includes(" vs ")) {
        return game.description;
      }
      if (game.description && game.description.toLowerCase().includes(" at ")) {
        return game.description.replace(/\s+at\s+/i, " vs ");
      }
      return raw || game.description || "Live Event";
    }

    function splitMatchTitle(title) {
      const parts = title.split(/vs/i).map(part => part.trim()).filter(Boolean);
      return [parts[0] || "Home", parts[1] || "Away"];
    }

    function logoImg(src, alt = "") {
      if (!src) return "";
      return `<img src="${src}" alt="${alt}" loading="lazy" />`;
    }

    const STREAM_EMBED_BASE = "https://streamcenter.xyz/embed/";

    function simplifyStreamSrc(streamUrl) {
      if (!streamUrl) return "";
      try {
        const parsed = new URL(streamUrl);
        if (parsed.hostname.includes("streamcenter.xyz") && parsed.pathname.includes("/embed/")) {
          const file = parsed.pathname.split("/").pop();
          return file || streamUrl;
        }
        return streamUrl;
      } catch {
        return streamUrl;
      }
    }

    function buildPlayerLink(streamUrl, detail = {}) {
      if (!streamUrl) return "#";
      const params = new URLSearchParams();
      params.set("s", simplifyStreamSrc(streamUrl));
      if (detail.title) params.set("t", detail.title);
      if (detail.category) params.set("c", detail.category);
      if (detail.home) params.set("h", detail.home);
      if (detail.away) params.set("a", detail.away);
      return `player.html?${params.toString()}`;
    }

    function renderStreamCard(game) {
      const title = formatMatchTitle(game);
      const [homeName, awayName] = splitMatchTitle(title);
      const category =
        game.category ||
        cachedCategories.find(cat => String(cat.id) === String(game.categoryId)) ||
        null;
      const kickoff = formatKickoff(game.beginPartie || game.date);
      const streams = extractStreams(game);

      const buttons =
        streams.length > 0
          ? streams
              .slice(0, 3)
              .map((stream, index) => {
                const rawLabel = stream.name || stream.label || `Stream ${index + 1}`;
                const label = /english/i.test(rawLabel) ? "Watch" : rawLabel;
                const url = stream.url || stream.stream;
                if (!url) return "";
                const playerUrl = buildPlayerLink(url, {
                  title,
                  category: category?.name,
                  home: homeName,
                  away: awayName
                });
                return `<a class="watch-btn ${index === 0 ? "primary" : ""}" href="${playerUrl}" rel="noreferrer noopener">${label}</a>`;
              })
              .join("")
          : "<span class='match-league'>Streams coming soon</span>";

      return `
        <article class="stream-card">
          <div class="stream-top">
            ${category ? `<span>${category.name}</span>` : "<span>Live Game</span>"}
            <span class="kickoff-pill">${kickoff}</span>
          </div>
          <div class="teams-square">
            <div class="team-side">
              ${logoImg(game.logoTeam1, homeName)}
              <span>${homeName}</span>
            </div>
            <div class="vs-chip">VS</div>
            <div class="team-side">
              ${logoImg(game.logoTeam2, awayName)}
              <span>${awayName}</span>
            </div>
          </div>
          <div class="stream-title">${title}</div>
          <div class="stream-actions">
            ${buttons}
          </div>
          ${
            game.description
              ? `<p class="stream-info">${game.description}</p>`
              : ""
          }
        </article>
      `;
    }

    function bindCategoryFilters() {
      const buttons = document.querySelectorAll("#navCategories .category-pill");
      buttons.forEach(button => {
        button.addEventListener("click", () => {
          const categoryId = button.dataset.categoryId;
          setActiveCategory(categoryId || "all");
        });
      });
      setActiveCategory(selectedCategoryId);
    }

    function setActiveCategory(categoryId = "all") {
      selectedCategoryId = categoryId;
      document.querySelectorAll("#navCategories .category-pill").forEach(button => {
        button.classList.toggle("active", button.dataset.categoryId === categoryId);
      });
      renderStreams();
    }

    function matchesSearch(game) {
      if (!searchTerm) return true;
      const query = searchTerm.toLowerCase();
      const title = formatMatchTitle(game).toLowerCase();
      const fields = [
        title,
        game.name?.toLowerCase(),
        game.gameName?.toLowerCase(),
        game.description?.toLowerCase(),
        game.category?.name?.toLowerCase()
      ].filter(Boolean);
      return fields.some(field => field.includes(query));
    }

    function renderStreams() {
      if (!allStreams.length) return;
      const filtered =
        selectedCategoryId === "all"
          ? allStreams
          : allStreams.filter(
              game =>
                String(game.categoryId) === String(selectedCategoryId) ||
                (game.category && String(game.category.id) === String(selectedCategoryId))
            );
      const searched = filtered.filter(matchesSearch);
      mountHTML(
        "streamsList",
        searched.map(renderStreamCard).join("") || "<p class='match-league'>No games found.</p>"
      );
    }

    async function loadStreams() {
      const { data, ok } = await fetchJSON(STREAMS_ENDPOINT);
      const list = Array.isArray(data) && data.length ? data : fallbackStreams();
      const sorted = list
        .map(item => ({
          ...item,
          beginPartie: item.beginPartie || item.date || item.parsedDate
        }))
        .sort((a, b) => new Date(a.beginPartie) - new Date(b.beginPartie));

      allStreams = sorted;
      renderStreams();

      if (!ok) {
        console.warn("Using fallback streams list");
      }
    }

    async function bootstrap() {
      const [live, upcoming, highlights, news] = await Promise.all([
        fetchJSON(API_ENDPOINTS.live),
        fetchJSON(API_ENDPOINTS.upcoming),
        fetchJSON(API_ENDPOINTS.highlights),
        fetchJSON(API_ENDPOINTS.news)
      ]);

      const online = live.ok || upcoming.ok || highlights.ok || news.ok;
      updateApiStatus(online);

      const fallback = fallbackData();
      const liveData = live.data?.matches || live.data || fallback.live;
      const upcomingData = upcoming.data?.matches || upcoming.data || fallback.upcoming;
      const highlightData = highlights.data?.items || highlights.data || fallback.highlights;
      const newsData = news.data?.articles || news.data || fallback.news;

      mountHTML(
        "liveMatchesGrid",
        (liveData || []).map(match => renderMatchCard(match, true)).join("") || "<p>No live games.</p>"
      );
      mountHTML(
        "upcomingMatchesGrid",
        (upcomingData || []).map(match => renderMatchCard(match, false)).join("") || "<p>No fixtures.</p>"
      );
      mountHTML(
        "highlightGrid",
        (highlightData || []).map(renderHighlightCard).join("") || "<p>No highlights.</p>"
      );
      mountHTML(
        "newsList",
        (newsData || []).map(renderNewsItem).join("") || "<p>No stories right now.</p>"
      );
    }

    const themeToggleBtn = document.getElementById("themeToggle");
    const searchBox = document.getElementById("streamSearch");
    if (themeToggleBtn) {
      const storedTheme = localStorage.getItem("hesgoal-theme");
      function applyTheme(mode = "dark") {
        const isLight = mode === "light";
        document.body.classList.toggle("light-mode", isLight);
        themeToggleBtn.textContent = isLight ? "Light Mode" : "Dark Mode";
        localStorage.setItem("hesgoal-theme", mode);
      }
      applyTheme(storedTheme === "light" ? "light" : "dark");
      themeToggleBtn.addEventListener("click", () => {
        const nextMode = document.body.classList.contains("light-mode") ? "dark" : "light";
        applyTheme(nextMode);
      });
    }

    if (searchBox) {
      searchBox.addEventListener("input", event => {
        searchTerm = event.target.value.trim();
        renderStreams();
      });
    }

    loadCategories();
    loadStreams();
    bootstrap();
  </script>
</body>
</html>

