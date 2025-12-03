# Obsidian
A collection of all the scripts I use to control Obsidian behaviour.

## Dataview
`dataviewjs` scripts used to create custom tables. Includes, but is not limited to:
- `upcomingTasks` - displays all upcoming birthdays and tasks, ordered by date, on my homepage.
- `reviewTable` - displays all items in a given folder and their `rating` property.
- `wips` - displays all the short stories I am currently working on (see [rowleysmiscellany.com]() for details), and links to the latest draft of each.
### Charts
Scripts used to create visuals from vault information. Includes, but is not limited to:
- `bodyWeight` - displays my weight and body fat percentage over time.
- `renderCorrelationChart` - displays the relationship between two given properties, connected by a date, with a line of best fit.
- `pieChart` - creates a pie chart displaying the totals of a list of given properties in a given folder.

## Meta Bind
Scripts used to create custom buttons. Includes, but is not limited to:
- `quickNote` - creates a new note in the root folder, titled after current GMT/UTC.
- `targetNote` - links to a specific note (only needed to ensure consistent formatting on my homepage).
- `randomPage` - opens a random page in a given folder.

## Quick Add
Scripts used to bind keyboard shortcuts to specific `.js` actions. Includes, but is not limited to:
- `quickDate` - inserts a link to either the next or most recent instance of a given day's daily note. For instance, entering "mo" on 2025-12-03 returns a link to the daily note for 2025-12-08 (next monday); entering "lmo" returns a link to the daily note for 2025-12-01 (last monday).
- `addDateCreated` - either creates or overrides the `dateCreated` property of an open note, with a link to the current day's daily note.
- `retroAddDateCreated` - same as above, but the daily note is defined not by the day of execution but by the date in the title of the open note.
