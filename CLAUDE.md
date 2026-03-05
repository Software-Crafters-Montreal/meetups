# Adding Quick Shares Links After a Meetup

After each meetup, we collect the links that were shared during the event and add them to the current year's markdown file (e.g. `2026.md`).

## Steps

1. Add a new section at the top of the year file, under `# <year> events`, with the date of the meetup (e.g. `## March 4`)
2. Add each link as a list item in the format: `- [Label](url) short description of the link`
3. Every link should have a short blurb describing what it is — check the existing entries for the tone and style
4. If a link description isn't provided, visit the URL to write a short, factual description
5. Use prefixes for specific content types, matching the conventions in existing entries:
   - Books: prefix with `📕`
   - Videos: prefix with `▶️`
   - Events/conferences: prefix with `👥`
   - Regular links: no prefix
6. Commit with the message: `Add quick shares links for <month> <day> meetup`
