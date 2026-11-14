# The World Record

The World Record is a broadsheet newspaper front page summing up world news on Friday 13 November 2026.

It contains 24 stories: 12 featured (numbered 1-12) plus 12 ALSO ON (numbered 13-24).

## Featured Stories

1. **FAA nationwide ground stop halting all U.S. departures as the shutdown strains air traffic control** (4,000+ flights cancelled, 10,000+ delayed) — Lead Story (full-width at top)
2. SpaceX flies Starship Flight 15
3. Nvidia slips below $4 trillion
4. Iran radar claim disputed
5. Trump, Xi and Putin gather at APEC
6. Drones strike Kyiv overnight
7. EU leaders wrangle over Ukraine talks
8. Tanker and cruise ship collide
9. Pope Leo XIV visits Peru
10. Gaza hospital pleads for fuel
11. Bus crash in Assam kills dozens
12. Microsoft outage hits users worldwide

## ALSO ON

13. Airlines waive fees as cancellations mount
14. APEC: Xi and Trump meet on the sidelines
15. Starship booster caught by tower arms
16. Nvidia shares extend slide after earnings
17. Kyiv air defences down overnight drones
18. EU split over Ukraine aid package
19. Gaza hospital appeals for fuel, medicine
20. Assam crash inquiry opens, driver held
21. Microsoft says services restored
22. Cruise line offers refunds after collision
23. Pope Leo XIV greets crowds in Lima
24. Storms sweep northern Europe

The page also carries a numbered dot-matrix world map tying each story number to its place on the map, and a sources line crediting wire and agency reporting.

## How it runs

```bash
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

— which copies entry.png to the output directory.

## Gate verification

Verified facts:
- `entry.png` is 1024x1024 px
- 125,886 bytes (under the 1 MiB gate limit)
- sha256: `ceb274499dfe68636948b806036646ae9d5001df7be9b3eaad0ff1df188c7f86`
