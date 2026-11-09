# B&A Training

Home-screen training app for the B&A Trail Marathon (Sun 7 Mar 2027).

- `index.html`: the app. It reads everything from `plan.json`.
- `plan.json`: the data. The weekly review and plan updates rewrite only this file.
- `sw.js`: offline cache. It always fetches the newest plan first.
