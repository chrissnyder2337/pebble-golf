# Pebble Golf

**[Get it on the Pebble App Store](https://apps.repebble.com/pebble-golf_57f80ba0bfbe4ad7a44dbbcf)**

<a href="https://www.buymeacoffee.com/ChrisSnyder" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" style="height: 60px !important;width: 217px !important;" ></a>

A GPS golf rangefinder and digital scorecard for the **Pebble Time 2**.

Pick a nearby course, choose your tee, and your watch shows live distance to the
front, center, and back of every green plus a hole-by-hole scorecard, all on the
200x228 64-color e-paper display with touch and four buttons. Your phone handles
GPS and networking; the watch keeps working offline for scoring, the hole map, and
your round history.

> This repository is the public home for Pebble Golf: its overview and its
> **issue tracker** for bug reports and feature requests. The app's source code
> isn't published here.

## Features

- **Live distance to green** (front / center / back) from real green geometry,
  updated as you move.
- **Honest fallback** when full geometry isn't available (card yardage, then a
  manual mode) — a fallback number is never shown as if it were a live measurement.
- **Hole map** drawn from OpenStreetMap, rendered hole-up (tee to green points
  toward the top), with tap-to-measure to any point on the hole.
- **Scorecard** with par, handicap, strokes, and putts; supports 18-hole,
  front-9, back-9, and shotgun-start rounds.
- **Round history** kept on the watch and browsable offline; edit strokes/putts
  or delete a past round right on the watch.
- **Custom courses** for anywhere not in the data: create one by name and hole
  count, then enter pars as you play.
- **Pebble Timeline** pins for each finished round (course, score, putts).
- **Export** a finished round as CSV or via a webhook.
- **Configurable** units (yards/meters), score-entry defaults, auto-advance,
  putt tracking, tap-to-measure, and more, from a phone config page.

## Feedback, bugs, and feature requests

Found a bug, or want to tell me the greens read too fast?
**[Open an issue](https://github.com/chrissnyder2337/pebble-golf/issues/new)** —
feedback is genuinely welcome (yes, even the picky kind).

When reporting a bug, it helps to include:

- what you expected to happen, and what actually happened
- the course (and tee) you were playing, if relevant
- roughly when it happened

Browse or search existing reports first:
**[github.com/chrissnyder2337/pebble-golf/issues](https://github.com/chrissnyder2337/pebble-golf/issues)**.

## Support

If Pebble Golf saved you from pacing off yardage like it's 1995, you can
[buy me a coffee](https://www.buymeacoffee.com/ChrisSnyder) to support my time.
Even a fraction of what you'd tip the beer-cart person is hugely appreciated, and
let's be honest, that's a rounding error next to your green fee.

## Data and attribution

Course and map data are provided under the Open Database License (ODbL):

- Course identity, per-hole par and handicap, and tee yardages: **OpenGolfAPI**
- Green / tee / fairway / hazard geometry: **(c) OpenStreetMap contributors**

The app caches data per device and exports a single round at a time; it does not
redistribute the underlying databases. Required attribution is shown in-app.
