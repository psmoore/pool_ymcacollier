# YMCA of Collier County aquatics — Pool Relay embed preview

A mockup of an aquatics section for [ymcacollier.org](https://ymcacollier.org/): both YMCA of Collier County
pools (North Campus, Naples; South Campus, Marco Island) on live [Pool Relay](https://www.poolrelay.com)
calendars, with a page per program.

Not an official YMCA of Collier County page. It says so in a ribbon across the top.

Built with `python3 build.py` (the chrome lives there; edit it, not the HTML) and served by GitHub Pages.

## The pages

| Page | Calendar | Scoped to |
|---|---|---|
| `index.html` — Find a swim time | [`4yDZ3OFs…`](https://www.poolrelay.com/v/4yDZ3OFsq5WkNdhi2zmxUw) | one pool at a time, lane by lane; **Pools** menu; **Teams** menu |
| `week.html` | [`zgwZ3RYl…`](https://www.poolrelay.com/v/zgwZ3RYlPRRanWwEYspZW9) | one campus, the whole week; **Facilities** menu, opens on North |
| `lap-swim.html` | [`Glpoiwy4…`](https://www.poolrelay.com/v/Glpoiwy4qOzsSJ8ZCKLmLy) | lap swim plus the high school blocks that close the pool |
| `swim-lessons.html` | [`489jlY8A…`](https://www.poolrelay.com/v/489jlY8AAwllA22oMASAF6) | group lessons (South Campus is the only one with sessions) |
| `water-fitness.html` | [`fvAsyrx6…`](https://www.poolrelay.com/v/fvAsyrx66tGkwVEipfhdDB) | water fitness at both campuses |
| `swim-team.html` | [`vXIZ5FQs…`](https://www.poolrelay.com/v/vXIZ5FQsUvOq8W5lUJJfrV) | Y swim teams and high school swim & dive |

## Sources (read 2026-09-25)

- **Pool schedule**: the Schedules page's embedded schedule (a WP Engine page fed by YMCA360, `window.apiSchedules`,
  seven days, filter *Pool*). Lap swim, water fitness and the high school blocks come from here.
- **Hours** page: lap swim hours per campus and the South Campus swim team / "2 lanes only" note.
- **Program registration** (Daxko, categories AQ | Aquatics, AQ | Swim Lesson): 8 lesson sessions at Marco Island,
  the Novice Team at Naples.
- The Open Swim page's "check pool schedules" link goes to a GroupEx schedule with no pool entries.

## What is ours

- **Lanes:** North 8 (25 yd), South 6 (25 yd), per places2swim. No page says which lanes lap swim keeps, so lane
  numbers are our estimate.
- **South Campus lap swim** follows the Hours page (7–3:30, then 4:30–6 on 2 lanes), not the schedule
  (7–6 straight), because the Hours page names the lanes.
- **High school practice and meets** are open-ended weekly series, as the schedule lists them.

## Open questions (also on the hub page)

| | |
|---|---|
| **Conflict** | North lap swim "until 7:30pm" (Hours) vs. the pool closed 3–6 / 3–9pm for high school (schedule). |
| **Conflict** | South lap swim: 2 lanes 4:30–6 with swim team (Hours) vs. open lap swim 7–6 (schedule). |
| **Gap** | High school season end date. |
| **Gap** | North Campus group lessons (page says both campuses; registration lists only Marco). |
| **Gap** | Competitive Swim Team, clinics, synchronized swimming, Splash Ball: no times published. |
