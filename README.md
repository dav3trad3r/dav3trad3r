## Building overhead24: what's above you, and what it's doing

[![overhead24: what's above you, right now](overhead24.png)](https://overhead24.com)

**[overhead24.com](https://overhead24.com)** is a free space-awareness site: every satellite in
orbit on a live globe, the passes you can see tonight, and an open-source-intelligence view of
military satellites.

- **Proximity:** satellites staying close to each other, close passes in the coming hours, and
  military satellites closing in on others
- **Orbit changes:** manoeuvres detected from public orbital elements, confirmed by the next update
- **Conflict zones:** when several of one country's military satellites pass over places where
  fighting was recorded, and how often each country covers each conflict area, week on week
- **Counterspace signals:** geostationary satellites leaving their slots or parking beside others,
  possible breakups, and countries busier than their own normal
- **A daily brief** of all of it, in plain words

Positions are computed in your browser from real orbital elements, so your location never leaves
your device. Built with TypeScript, Next.js and SGP4 on Postgres, from public data:
Space-Track.org, GCAT (J. McDowell), UCDP and Launch Library 2.

The orbit engine is open source: **[overhead24-orbit](https://github.com/dav3trad3r/overhead24-orbit)**
(AGPL-3.0), with the [methodology](https://github.com/dav3trad3r/overhead24-orbit/blob/main/METHODOLOGY.md)
behind every detection.
