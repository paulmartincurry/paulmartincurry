PAULMARTINCURRY.COM — DEPLOY KIT
================================

WHAT'S HERE (4 files + this note). All of them go in the SAME folder:
the top level of your web host (the "web root" — where the site serves from).

  index.html       the entire site/game
  og.png           the social preview card (MUST sit next to index.html
                   at the domain root, or link previews break silently)
  music.mp3        ambient track ("No Destination")
  wagon-wheel.m4a  the omnichord recording

HOW TO DEPLOY
  Drag all four files into your host's web root. That's it.
  Do NOT put them inside a subfolder.

THE ONE LINK THAT NEEDS A DECISION
  Every "here for work" path points at one place, set in ONE line
  near the top of the script in index.html:

      const WORK_URL='https://work.paulmartincurry.com/work-1';

  If the old Squarespace pages die when this goes live, change that
  single line to wherever the portfolio lives (e.g. a subdomain like
  https://work.paulmartincurry.com/work-1) and re-upload index.html.
  Nothing else needs touching.

AFTER UPLOAD, CHECK (5 minutes)
  1. Visit the site on your phone. Tap through the boot. Type something.
  2. Tap [ here for work ]. Make sure it opens the portfolio, not a 404.
  3. Paste the URL into a link-preview checker (e.g. opengraph.xyz)
     and confirm the card shows.
  4. Click a few bio links from [ about ].
