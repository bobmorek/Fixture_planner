# Fixture_planner

**Fixtures to Spond** — a single-file browser tool that turns a fixture list copied from FA Full-Time into a block you can paste into Spond's season planner, plus `.ics` and `.csv` exports.

Everything lives in `index.html`. No build step, no dependencies, no network calls: open the file in a browser, or serve it from GitHub Pages.

## Using it

1. Copy the fixture rows from the Full-Time fixture table and paste them into the box.
2. Pick your team from the dropdown, set the default kick-off, meet time and match length.
3. Correct anything in the table. Untick rows you don't want.
4. Copy for Spond (tab-separated, column order matches the season planner grid), or download the calendar / spreadsheet.

Full-Time writes `00:00` when no kick-off is set; those rows are flagged and fall back to your default, with "kick-off time to be confirmed" appended to the description.

Title and description templates accept `{opponent} {home} {away} {ha} {venue} {comp} {team} {date}`.
