---
title: Tape
permalink: /
---

<div class="hero">
  <img class="app-icon" src="app-icon.png" alt="Tape app icon" width="148" height="148">
  <h1>Tape</h1>
  <p class="kicker">Trading Journal</p>
  <p class="lede">Log each day's P&amp;L and every swing trade on a calendar. See how it all adds up. Everything stays on your device.</p>
  {% if site.app_store_id %}
  <a class="badge" href="https://apps.apple.com/app/id{{ site.app_store_id }}">
    <img src="app-store-badge.svg" alt="Download on the App Store" height="54" width="161">
  </a>
  {% else %}
  <p class="soon">Coming soon to the App Store · iPhone, iPad and Mac</p>
  {% endif %}
  <div class="candles" aria-hidden="true">
    <span class="up" style="--h:26px;--y:14px"></span>
    <span class="up" style="--h:30px;--y:6px"></span>
    <span class="down" style="--h:18px;--y:10px"></span>
    <span class="up" style="--h:36px;--y:-4px"></span>
    <span class="up" style="--h:26px;--y:-10px"></span>
    <span class="down" style="--h:16px;--y:-6px"></span>
    <span class="up" style="--h:24px;--y:-14px"></span>
  </div>
</div>

<div class="shots">
  <img src="shots/1-month.jpg" alt="Month calendar of daily P&amp;L with weekly totals" width="506" height="1100" loading="lazy">
  <img src="shots/3-swing.jpg" alt="Swing trades shown as bars across the days they were held" width="506" height="1100" loading="lazy">
  <img src="shots/5-summary.jpg" alt="Summary of net P&amp;L, win rate and a running total chart" width="506" height="1100" loading="lazy">
</div>

<div class="features">
  <div class="feature">
    <h3>Log a day in seconds</h3>
    <p>Tap a day, enter your P&amp;L, add a note. Your month fills in green and red.</p>
  </div>
  <div class="feature">
    <h3>Every swing, entry to exit</h3>
    <p>Each trade shows as a bar across the days you held it: ticker, long or short, P&amp;L.</p>
  </div>
  <div class="feature">
    <h3>See where you stand</h3>
    <p>Week, month, year or all time: net P&amp;L, win rate, best and worst, average hold.</p>
  </div>
  <div class="feature">
    <h3>Private by design</h3>
    <p>No account, no cloud, no ads. Face ID lock, hide amounts, export to CSV.</p>
  </div>
</div>

<p class="footer-links">
  <a href="support/">Support</a> · <a href="privacy-policy/">Privacy Policy</a>
</p>
