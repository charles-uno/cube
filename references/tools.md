# External Tools

You may use these tools to query, filter, and evaluate cards. 

To reduce duplicate queries, you may cache data locally in `cache/`. Details are up to you, but JSON is probably easiest

You may write scripts for data analysis. Put them in `cache/` too

## Scryfall

Scryfall is a tool for searching existing MTG cards. 

- API docs: https://scryfall.com/docs/api
- Query syntax docs: https://scryfall.com/docs/syntax
- Bulk data access: https://scryfall.com/docs/api/bulk-data

NOTE: Scryfall has a rate limits! Be a good consumer. Be attentive to error messages

## 17lands

We can use 17lands.com to eyeball power level. It provides card-by-card power rankings based on data from MTG Arena drafts. 

Two big disclaimers about using this data:
- Data comes from drafts. Cards are played only within their set. Careful with comparisons across sets.
- Power level may depend on theme support. Cube themes are often different from draft themes. 
- Draft environments are often skewed in terms of color. For example, red cards in MSH rank poorly red was weak in that format overall. Individual red cards may still be usable.
- Not all cards have data! Commander sets don't get drafted, but we still have access to those cards

We should steer clear of anything rated A+ or A. Those cards are likely bombs that can run away with a game on their own, independent of theme support. 

It looks like the strongest recent uncommons show up at A-/B+/B. In order to be viable, each theme probably needs a few of those.
