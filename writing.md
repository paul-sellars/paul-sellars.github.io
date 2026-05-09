---
layout: page
title: Writing
permalink: /writing/
---

<!-- ======== Override styles from default theme. ======== -->

<style>
  :root {
    --background-color: rgb(225, 236, 235); /* Flexoki Blue 50 */
    --text-color: rgb(52, 51, 49); /* Flexoki ui-2 */
  }

  /* 1. Background. */
  body { background-color: var(--background-color) !important; }

  /* 2. Hide unwanted global elements. */
  .site-nav, .site-logo, .site-subtitle, .site-footer { display: none !important; }

  /* 3. Common layout. */
  .site-header .wrapper, .writing-footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
  }
  .site-header { padding: 0 !important; }
  .site-header .wrapper { min-height: 120px; }
  .site-title-group { margin: 0 !important; }
  .site-title { padding: 0 !important; }

  /* 4. Common typography. */
  .writing-footer a, .footer-subtitle { text-transform: uppercase; }
  .writing-footer a { font-family: "EB Garamond", serif; text-decoration: none; !important; }

  /* 5. Header specifics. */
  .site-header {
    border-top: 1px dashed var(--text-color);
    border-bottom: 1px dashed var(--text-color) !important;
  }
  .site-title, .site-title:visited {
    color: var(--text-color);
    font-family: "IBM Plex Serif", serif;
    font-weight: normal;
    letter-spacing: 0.125ch;
    text-transform: capitalize;
  }

  /* 6. Body specifics. */
  body, a, a:visited { color: var(--text-color); }

  /* 7. Footer specifics. */
  .writing-footer { 
    margin-top: 5rem;
    padding: 2rem 0 4rem;
    border-top: 1px dashed var(--text-color);
    color: var(--text-color);
    }
  .writing-footer a {
    font-size: 1.2rem;
    display: block; /* Stack on top of subtitle. */
    margin-bottom: 0.2rem; 
  }
  .writing-footer a:hover {
    text-decoration: underline;
  }
  .footer-subtitle {
    font-family: "IBM Plex Sans", sans-serif;
    text-transform: uppercase;
    font-size: 0.7rem;
    letter-spacing: 0.05rem;
  }
</style>

<!-- ============ Page content begins here... ============ -->

In my own time (when not occupied with [the day job]({% link index.md %})) I like to write.

While I periodically struggle with something perpetually unfinished and theoretically novel length, more often than not my focus is on short stories.

Currently I don’t have any stories out on submission (although a number are awaiting revision and resubmission).

Watch this space for updates...

*Last updated: Saturday, 9 May 2026.*

<!-- ============== Page content ends here. ============== -->

<div class="writing-footer">
  <a href="{% link index.md %}">Paul Sellars</a>
  <div class="footer-subtitle">Editorial & Typesetting</div>
</div>