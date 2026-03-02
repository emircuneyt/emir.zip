---
layout: layouts/base.njk
title: home
---

<div class="container">
  <!-- Big Title -->
  <h1 class="site-title">
    {{ site.name }}<br>
    <span style="font-size: 0.6em;">{{ site.subtitle }}</span>
  </h1>

  <!-- Top Navigation -->
  



  <!-- Open 24/7 Sign -->
  <div class="open-sign">
    <div class="neon-text">OPEN<br>24<br>HRS</div>
  </div>

  <!-- Flame Divider -->
  <div class="flame-divider"></div>

  <div class="welcome-section">
  <h2>Hey there, welcome!</h2>
  <p>This is my portfolio/CV in a 90’s Neocities coat of paint.</p>
  <p>I’m <strong>{{ site.author }}</strong>, a Senior Security Engineer in Amsterdam focused on AWS cloud security.</p>
  <p>Browse the windows for projects, notes, and the books that shaped how I think.</p>
</div>

  <!-- Flame Divider -->
  <div class="flame-divider"></div>

  <!-- Main Grid Layout -->
  <div class="main-grid">
    
    <!-- LEFT SIDEBAR -->
    <aside class="sidebar-left">
      
      <!-- Books I Read -->
      <div class="window-box">
        <div class="window-title">
          <span>Books I Read</span>
          <div class="window-buttons">
            <div class="window-button">_</div>
            <div class="window-button">□</div>
            <div class="window-button">×</div>
          </div>
        </div>
        <div class="window-content">
          <div class="books-grid">
            <div class="book-item">
              <strong>"Meditations"</strong>
              <span style="font-size: 11px;">by Marcus Aurelius</span>
              <p style="margin-top: 5px; font-size: 11px;">⭐⭐⭐⭐⭐</p>
            </div>
            <div class="book-item">
              <strong>"Siddhartha"</strong>
              <span style="font-size: 11px;">by Hermann Hesse</span>
              <p style="margin-top: 5px; font-size: 11px;">⭐⭐</p>
            </div>
            <div class="book-item">
              <strong>"Man's Search for Meaning"</strong>
              <span style="font-size: 11px;">by Viktor Frankl</span>
              <p style="margin-top: 5px; font-size: 11px;">⭐⭐⭐⭐⭐</p>
            </div>
            <div class="book-item">
              <strong>"Sophie's World"</strong>
              <span style="font-size: 11px;">by Jostein Gaarder</span>
              <p style="margin-top: 5px; font-size: 11px;">⭐⭐⭐⭐⭐</p>
            </div>
          </div>
        </div>
      </div>

      <!-- Projects I'm Working On -->
      <div class="window-box">
        <div class="window-title">
          <span>Projects I'm Working On</span>
          <div class="window-buttons">
            <div class="window-button">_</div>
            <div class="window-button">□</div>
            <div class="window-button">×</div>
          </div>
        </div>
        <div class="window-content">
          <div class="project-item">
            <h4>An Anxiety App</h4>
            <p style="font-size: 12px;">From sufferers to sufferers. There's still lots to go.</p>
          </div>
          <div class="project-item">
            <h4>Fully onsite no-infra risk-based vulnerability prioritization</h4>
            <p style="font-size: 12px;">Already using this in my current job but improving it to make it ready for real world.</p>
          </div>
          <div class="project-item">
            <h4>Amsterdam traffic lights photography</h4>
            <p style="font-size: 12px;">Traffic lights of Amsterdam from the first built one to the last. Each tells differnet story.</p>
          </div>
        </div>
      </div>

      <!-- Projects Abandoned -->
      <div class="window-box">
        <div class="window-title">
          <span>Projects I've Abandoned (many more..)</span>
          <div class="window-buttons">
            <div class="window-button">_</div>
            <div class="window-button">□</div>
            <div class="window-button">×</div>
          </div>
        </div>
        <div class="window-content">
          <div class="project-item" style="background: #ffcccc;">
            <h4>Toilet Empire</h4>
            <p style="font-size: 12px;">RIP 2025-2025. It was going to be cool but... life happened.</p>
          </div>
          <div class="project-item" style="background: #ffcccc;">
            <h4>Story of Yunktul</h4>
            <p style="font-size: 12px;">Sad story of Yunktul, a boy where his eyes are under his armpits. Might come back to this later.</p>
          </div>
        </div>
      </div>

    </aside>

    <!-- CENTER CONTENT -->
    <main class="center-content">
      
      <!-- About Me Section -->
      <div class="window-box">
        <div class="window-title">
          <span>About Me</span>
          <div class="window-buttons">
            <div class="window-button">_</div>
            <div class="window-button">□</div>
            <div class="window-button">×</div>
          </div>
        </div>
        <div class="window-content">
  <p style="margin-bottom: 10px;">
    I’m a Senior Security Engineer based in Amsterdam, focused on AWS cloud security and building security programs that actually work in real teams.
  </p>

  <ul style="margin: 0; padding-left: 18px; font-size: 13px;">
    <li>Cloud security architecture (AWS)</li>
    <li>IAM, identity strategy, least privilege</li>
    <li>Threat modeling, secure-by-default patterns</li>
    <li>Detection/response, hardening, guardrails</li>
    <li>Pragmatic security for fast-moving orgs</li>
  </ul>

  <p style="margin-top: 10px;">
    This site is intentionally old-school: no algorithm, no fluff - just my work, thoughts, and things I’m learning.
  </p>
</div>
      </div>

      <!-- RECRUITER ALERT -->
      <div class="recruiter-box">
        <h3>🚨 ARE YOU A RECRUITER? 🚨</h3>
        <p style="color: #000; font-size: 18px; font-weight: bold; margin: 15px 0;">
          BOOKMARK THIS PAGE RIGHT NOW!!!
        </p>
        <p style="color: #000; margin-bottom: 15px;">
          (seriously)
        </p>
        <a href="#" class="bookmark-button" onclick="alert('Press Ctrl+D (or Cmd+D on Mac) to bookmark!'); return false;">
          ⭐ ADD TO BOOKMARKS ⭐
        </a>
      </div>

      

      <!-- Under Construction -->
      <div class="construction-banner">
        <h2>🚧 UNDER CONSTRUCTION 🚧</h2>
      </div>

    </main>

    <!-- RIGHT SIDEBAR -->
    <aside class="sidebar-right">
      
      <!-- Games Playing -->
      <div class="window-box">
        <div class="window-title">
          <span>Games I'm Playing</span>
          <div class="window-buttons">
            <div class="window-button">_</div>
            <div class="window-button">□</div>
            <div class="window-button">×</div>
          </div>
        </div>
        <div class="window-content">
          <ul class="games-list">
            <li>Path of Exile (every new season)</li>
            <li>Spiritfarer (a game about letting the lost ones go)</li>
            <li>Dota 2 (don't know why)</li>
            <li>WoW (midnight)</li>
          </ul>
        </div>
      </div>

      <!-- Games Finished -->
      <div class="window-box">
        <div class="window-title">
          <span>Games I Finished (5 stars only)</span>
          <div class="window-buttons">
            <div class="window-button">_</div>
            <div class="window-button">□</div>
            <div class="window-button">×</div>
          </div>
        </div>
        <div class="window-content">
          <ul class="games-list">
            <li>The last of us 1-2 ⭐⭐⭐⭐⭐</li>
            <li>Kingdom come deliverance 1-2 ⭐⭐⭐⭐⭐</li>
            <li>Baldur's gate 3 ⭐⭐⭐⭐⭐</li>
            <li>RDR2 ⭐⭐⭐⭐⭐</li>
            <li>Witcher 3 ⭐⭐⭐⭐⭐</li>
          </ul>
        </div>
      </div>

      <!-- Updates -->
      <div class="window-box">
        <div class="window-title">
          <span>Updates</span>
          <div class="window-buttons">
            <div class="window-button">_</div>
            <div class="window-button">□</div>
            <div class="window-button">×</div>
          </div>
        </div>
        <div class="window-content">
          <p style="font-size: 12px; margin-bottom: 8px;"><strong>2/3/26:</strong> Site launched!</p>
          <p style="font-size: 12px; margin-bottom: 8px;"><strong>1/3/26:</strong> Added games section</p>
          <p style="font-size: 12px; margin-bottom: 8px;"><strong>28/2/26:</strong> New design</p>
          <p style="font-size: 12px; margin-bottom: 8px;"><strong>25/2/26:</strong> Started building</p>
        </div>
      </div>

      <!-- Media Player -->
      <div class="media-player">
        <div class="window-title">
          <span>Media Player</span>
          <div class="window-buttons">
            <div class="window-button">_</div>
            <div class="window-button">□</div>
            <div class="window-button">×</div>
          </div>
        </div>
        <div style="padding: 10px; background: #000; color: #00ff00; font-family: monospace;">
          <p>♪ Now Playing: Come into My World</p>
          <p style="font-size: 11px;">Kylie Minoque</p>
          <div style="margin: 10px 0; height: 4px; background: #333;">
            <div style="width: 30%; height: 100%; background: #00ff00;"></div>
          </div>
          <div class="player-controls">
            <button class="player-button">⏮</button>
            <button class="player-button">▶</button>
            <button class="player-button">⏭</button>
            <button class="player-button">🔊</button>
          </div>
        </div>
      </div>

    </aside>

  </div>

  <!-- Footer -->
  <div class="footer">
    <p>©1990 (2026) {{ site.name }}</p>
    <p style="margin-top: 10px;">
      <a href="mailto:{{ site.email }}" style="color: #00ffff;">email</a> | 
      <a href="{{ site.github }}" style="color: #00ffff;">github</a>
    </p>
    <p style="margin-top: 20px; font-size: 12px;">
      Made with nostalgia | but i still keep things up-to-date
    </p>
  </div>

</div>
