---
layout: page
title: Listening
permalink: /listening
---

### Listening

I'm a big indie music buff. I make small playlists for moods, and name each one
after the colour I associate with that mood.

**Rainbow** is the one I had been wanting to make for years: a compilation of
every track I have shared on Instagram over the past 6+ years. It was too much
work to compile manually, but Penguin is magic 🙂

Both Spotify and YouTube Music versions linked below!

<div class="play-actions">
  <a class="play-btn" href="https://open.spotify.com/playlist/2cJQxGOoThzVQczjtG8bZq" target="_blank" rel="noopener">Play on Spotify</a>
  <a class="play-btn" href="https://music.youtube.com/playlist?list=PLAwUtqsrl3L8" target="_blank" rel="noopener">Play on YouTube Music</a>
</div>

<div class="rainbow-embed">
  <iframe
    src="https://open.spotify.com/embed/playlist/2cJQxGOoThzVQczjtG8bZq?utm_source=generator&theme=0"
    width="100%"
    height="500"
    frameborder="0"
    allowfullscreen
    allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
    loading="lazy"
    title="Rainbow on Spotify"></iframe>
</div>

<p class="oss-credit">Built on <a href="https://github.com/sigma67/ytmusicapi">ytmusicapi</a> and <a href="https://github.com/subzeroid/instagrapi">instagrapi</a>. Both MIT licensed 🙏</p>

<style>
  .play-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.7rem;
    margin: 1.6rem 0 1.5rem;
  }

  .play-actions a.play-btn {
    display: inline-block;
    padding: 0.5em 1em;
    border: 1px solid var(--color-border);
    border-radius: 4px;
    background: var(--color-box-background);
    color: var(--color-primary);
    font-size: 0.95rem;
    line-height: 1.5;
    text-decoration: none;
  }

  .play-actions a.play-btn:hover {
    border-color: var(--color-accent);
    text-decoration: none;
  }

  /* keep the theme's outbound-link arrow, but align it inside the button */
  .play-actions a.play-btn:after {
    top: 0;
    margin-left: 0.4em;
  }

  .rainbow-embed iframe {
    display: block;
    width: 100%;
    border: 0;
    border-radius: 4px;
  }

  .oss-credit {
    margin: 2.5rem 0 0;
    font-size: 0.8em;
    line-height: 1.6;
    color: var(--color-subtext);
  }
</style>
