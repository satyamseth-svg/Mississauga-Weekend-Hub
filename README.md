# YYZ3 Weekend Crew — Performance Dashboard

Live page: https://satyamseth-svg.github.io/Mississauga-Weekend-Hub/

Month-wise performance for the Mississauga (YYZ3) weekend crew — supervisor Suresh Singh
with Kulwinder Kumar, Varinder Khan, Dheeraj Mahajan and Sumeet Kumar.

## Adding a new report

1. Open the live page.
2. Click **＋ Add CSV** and pick the WH Reporting export (a week or a full month).
   The page reads the date range from the first line of the CSV and adds a tab for it.
   Only the weekend crew's rows are kept.
3. Click **⬇ Download Dashboard** — this saves `index.html` with the new report built in.
4. In this repo, open `index.html` → pencil icon is not needed: use **Add file → Upload files**,
   drop the downloaded `index.html`, and commit. The live page updates in about a minute.

Reports in the same month are added together, so weekly uploads roll up into the month tab.
If two reports overlap (e.g. a month-to-date export and a week inside it), the longer one is
used for the month total and the other is marked with ⓘ.

## Calculations

Same rules as the daily YYZ3 dashboard: targets of 140/hr picking, 65/hr stowing,
35/hr packing single, 25/hr packing multi, 15/hr packing large, 80/hr docking.
Packing is scored as a volume-weighted index of single and multi.
IT goal is 6.5h per day worked. Suresh's own output is shown separately and is not in the team totals.
All of these can be changed under ⚙️ Settings on the page.
