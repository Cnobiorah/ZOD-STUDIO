ZoD Outdoor Structures — image drop-in guide
=============================================

Each gallery/home category can now show up to 3 photos in a small
carousel (dots appear automatically once you add more than one).
Nothing breaks if you only add 1 — it just shows that one, no dots.

HERO (home page)
-----------------
images/hero.jpg

GALLERY CATEGORIES — up to 3 images each
--------------------------------------------------------------
Modern flat roof:      cp-001.jpg   cp-001-2.jpg   cp-001-3.jpg
Luxury cantilever:     cp-002.jpg   cp-002-2.jpg   cp-002-3.jpg
Luxury villa canopy:   vl-001.jpg   vl-001-2.jpg   vl-001-3.jpg
Timber finish:         tm-001.jpg   tm-001-2.jpg   tm-001-3.jpg
Glass canopy:          gc-001.jpg   gc-001-2.jpg   gc-001-3.jpg
Pergolas:               pg-004.jpg   pg-004-2.jpg   pg-004-3.jpg
Walkway covers:        wk-001.jpg   wk-001-2.jpg   wk-001-3.jpg
Entrance canopies:     ec-001.jpg   ec-001-2.jpg   ec-001-3.jpg
Gates:                  gt-001.jpg   gt-001-2.jpg   gt-001-3.jpg
Commercial parking:    cp-003.jpg   cp-003-2.jpg   cp-003-3.jpg

The first filename in each row (no suffix) is required for the card to
show a photo at all. The "-2" and "-3" files are optional — add them
whenever you have more photos for that category, in any order, at any
time. As soon as a "-2" file exists, dots appear on that card
automatically so people can click through.

SPEC
----
- Format: .jpg (rename + tell Claude if you'd rather use .png or .webp)
- Aspect ratio: 4:3 works best with the current card layout
- Recommended export size: 1200px on the long edge
- Keep each file under ~200KB where possible for fast loading

WHAT HAPPENS IF A FILE IS MISSING
----------------------------------
Nothing breaks. Missing files are skipped silently:
- If none of the 3 exist for a category, it shows the line-drawn icon
- If only the first exists, it shows just that photo, no dots
- If 2 or 3 exist, dots appear and the card auto-cycles through them
  every few seconds (and on click)

PORTFOLIO PAGE
--------------
Not wired to specific filenames yet, since it's still "coming soon."
Once you have real completed projects, tell Claude and it'll build out
proper project cards/filenames for this page too.
