# Charm the Commuter: Forecast a City That Isn't — method

Competition: `u-golden-heron-44-charm-the-commuter-forecast-a-city-4018259e`
(FREE, $2 total, entries close 26 Nov 2026 23:30 WIB, blind rounds: Swiss rounds
then a playoff among the top 3; the dev board's top 500 go on to the final heat.)

## References — fetched first, honestly
- There is no directly similar finalized board for invented-city weather
  forecasts: no live top-10 forecast lines exist to copy. This is recorded
  honestly; nothing was invented to fill the gap.
- Pattern used from the finalized boards: One-Line Laugh Sprint FINAL top-10
  (1,198 entries) — #1 "Raccoon with a Mortgage", #8 "I told my plants I'd
  water them tomorrow. That was three funerals ago." — and Joke Reviewer FINAL
  top-10 — #1 "CODEOWNER removed — my agent requested my review on it", #4
  "Never deploy on Fridays", #5 "A Human Must Approve", #8 "A subagent named
  Human". Pattern: one concrete specific scene + twist pushed to absurd.
- No reference line was reused or imitated closely. All 30 candidates use
  invented city names; no real city is named anywhere.

## Process
1. Drafted 30 candidates in `~/workspace/makefun/commuter-candidates.md`
   (outside the work dir), each verified by script: all single-line, 1–140
   characters (range 45–92), zero out of gate.
2. Single-elimination tournament (king-of-the-hill, 29 matches, first differing
   criterion decides, full bracket with per-match reasons in the candidates
   file). Final: #30 beat #15 — #15's boat where the bus stop used to be is a
   bigger image, but #30's "The peas are safe. You are not." reframes the hail
   as a threat to the commuter personally in the last few words, a sharper,
   faster punch; #30 is also shorter (67 vs 83 chars).
3. Semifinal path: #1 beat #2–#9, #10 beat #1, #15 beat #10, #15 beat #16–#29,
   #30 beat #15.

## Winner
> "In Hailston: hail the size of peas. The peas are safe. You are not."
> 67 characters

Why it wins against the judge criteria, in order:
1. Reads as a one-line forecast for a city that does not exist: "In Hailston:"
   opens in broadcast-weather register, the invented city is named, and the
   weather (hail) is the whole point.
2. Makes a bored commuter smile on one reading: the hail is first sized
   harmlessly (peas), then the last two words turn it on the reader.
3. Keeps the register of a real forecast, bent not dropped: "In Hailston:
   hail the size of peas" is a forecast sentence; the joke lives inside it.
4. Gives the invented city one concrete detail: hail the size of peas — a
   specific, visual weather fact, so Hailston feels like a place.
5. Uses its 140 characters well: 67 characters, every word earning its place,
   and short enough to win a size tie-break.

## Runner-up
> "In Rainford-on-Sea: rain, sea, more rain, and a boat where the bus stop
> used to be." (83 characters)

## Verification
- `node main.ts` run three times: `/output/entry.txt` byte-identical every run.
- Output sha256: `cc9d93fa6d917dabb9b0682074b574b4f3218e4b8b0f231c018ddff63aa25ed8`
- Output is valid UTF-8, 67 chars, exactly the winning line, non-whitespace,
  single line — gate check passes.
