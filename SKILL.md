# WeChat GitHub Weekly Article

The same format below is used for both weekly lists. The GitHub list runs every Monday; the model blind-test list runs every Friday and is described in its own section at the end, written in the same style.

## Build the weekly list

- Check for a pending weekly article from an earlier cycle at the start of the task and finish or report it before you start a new issue.

- Check the GitHub weekly trending chart fresh for the current week through `browser.browse` and take the top 10 entries in rank order from first to tenth.

- Keep the list exactly as the chart gives it and do not remove an entry because it appeared in an earlier issue.

- Write one sentence for each entry that states who the entry is for and what it can do.

- Write only descriptions and star counts that you verified from the entry itself and omit any number you could not verify.

- Check each entry for political content and pause for user review when an entry raises a political question instead of completing the draft silently.

## Build the magazine long image

- Build one magazine page for each entry with a distinct colour, a large ranking numeral and a visual motif.

- Use a real screenshot or an AI generated scene image on each page and do not rely on line illustration alone.

- Embed every image in the final file so the image displays in the viewer and do not rely on a relative path that may fail to load.

- Stitch the pages into one long image that starts directly with the first entry and does not repeat the cover in the body.

- Make a separate cover thumbnail that shows GitHub related iconography so a reader can tell at a glance that the article is about GitHub trending.

- Use an artistic bold style for titles and large ranking numerals and keep body text in a regular readable font.

- Use a date anchored title for the issue and do not use a relative week word that will go stale after a few days.

- Keep working notes and meta explanations out of the article itself so the article reads as clean magazine content.

## Save as draft and verify the state

- Work through the browser only for this account and do not build an API or MCP connector for it.

- Expect the login session to expire between weeks. When it has expired, log in again by WeChat scan in the browser and do not ask the user to fill in a QQ or password login form because that form does not substitute for the scan.

- Save the finished article as a draft only and never publish it yourself.

- Before you act on a change request, check the current draft list and published list fresh so you do not promise a draft edit for an article that is already published or deleted.

- After saving, read the draft back from the backend and confirm its title, cover thumbnail and long image before you report success.

## Report and hand over

- Report the draft state, the scheduled state and the live state as different states and never reuse an earlier status report.

- Tell the user that the draft is saved and that submission is theirs to make.

- List any unverified number you left out and any item you paused for review so the user can check the result at a glance.

- Do not create a second draft for an issue the user already submitted or deleted until you have checked the current state and the user asks for a new draft.

## Available connectors

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- Do not build an API or MCP connector for this browser-only account.

## Alternatives for better results

- Ask the user to confirm the publication date in the title when the trending chart and the draft date could differ.

- Reuse an approved magazine style across weeks and change only the entries, the date and the cover thumbnail so the format stays stable.

- Keep the previous issue as a format reference but rebuild the list fresh each week instead of copying its entries.

# WeChat Model Blind-Test Weekly Article

## Build the weekly list

- Check for a pending model blind-test article from an earlier cycle at the start of the task and finish or report it before you start a new issue.

- Check the Contra Labs × BenchFlow Frontier Design Benchmark leaderboard fresh for the current week through `browser.browse` at https://contralabs.com/frontierdesign/leaderboard and take the top 10 entries in rank order from first to tenth.

- Keep the list exactly as the leaderboard gives it and do not remove an entry because it appeared in an earlier issue.

- Keep Human designers in the list exactly where the leaderboard puts it, even though it is a human reference design and not a model, and do not skip it or fill its place with the next model.

- Write one sentence for each entry that states who the entry is for and what design work it can do, in the same who + what style as the GitHub list. Do not write a tool function for it, because a model is not a tool with one function.

- Give each entry the same three parts: the who + what sentence, then its Elo score, win rate and vote count, then one design trait only when the official research page verifies it for that model or lab. When no trait is verified for that entry, write only the first two parts and do not invent one.

- Write only descriptions, Elo scores and win rates that you verified from the leaderboard itself and omit any number you could not verify.

- State in the article that this is a design blind test, judged by professional designers on real client design briefs, and do not present it as a general model capability ranking.

- Do not invent an origin for Gestalt. It is a stealth model whose developer is not publicly named, so describe it only as an unnamed stealth model.

- Check each entry for political content and pause for user review when an entry raises a political question instead of completing the draft silently.

- Publish only when the list has changed. Compare the fresh top 10 (rank, model and Elo) with the last published issue's snapshot in `~/workspace/wechat-github-weekly/model-blind-test-top10-snapshot.md`. If rank, model or Elo differs anywhere, build the new issue and update the snapshot after it is published. If everything is identical, skip that week: build no draft and tell the user the list is unchanged. The first issue has no published snapshot, so always build it.

- Do not treat Friday as the leaderboard's release day. The benchmark has no fixed weekly release time and updates as new votes and models arrive, so Friday 00:00 is only this task's own rhythm.

## Build the magazine long image

- Build one magazine page for each entry with a distinct colour, a large ranking numeral and a visual motif.

- Use a real screenshot or an AI generated scene image on each page and do not rely on line illustration alone.

- Embed every image in the final file so the image displays in the viewer and do not rely on a relative path that may fail to load.

- Stitch the pages into one long image that starts directly with the first entry and does not repeat the cover in the body.

- Make a separate cover thumbnail that shows AI model and design related iconography so a reader can tell at a glance that the article is about an AI design blind test, and do not use GitHub iconography for this list.

- Use an artistic bold style for titles and large ranking numerals and keep body text in a regular readable font.

- Use a date anchored title for the issue and do not use a relative week word that will go stale after a few days.

- Keep working notes and meta explanations out of the article itself so the article reads as clean magazine content.

## Save as draft and verify the state

- Work through the browser only for this account and do not build an API or MCP connector for it.

- Expect the login session to expire between weeks. When it has expired, log in again by WeChat scan in the browser and do not ask the user to fill in a QQ or password login form because that form does not substitute for the scan.

- Save the finished article as a draft only and never publish it yourself.

- Before you act on a change request, check the current draft list and published list fresh so you do not promise a draft edit for an article that is already published or deleted.

- After saving, read the draft back from the backend and confirm its title, cover thumbnail and long image before you report success.

## Report and hand over

- Report the draft state, the scheduled state and the live state as different states and never reuse an earlier status report.

- Tell the user that the draft is saved and that submission is theirs to make.

- List any unverified number you left out and any item you paused for review so the user can check the result at a glance.

- When the list is unchanged and the week is skipped, tell the user the list is unchanged and no draft was made, instead of reporting a draft.

- Do not create a second draft for an issue the user already submitted or deleted until you have checked the current state and the user asks for a new draft.
