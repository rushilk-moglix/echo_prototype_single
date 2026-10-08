# Echo prototype, in one file

Echo by Cognilix: build voice agents, run calling campaigns from a sheet, and get every answer back.

This repository holds the whole clickable prototype as **one HTML file**, for design, engineering and leadership review.
Nothing to install and nothing to run.

| Way | How |
| :--- | :--- |
| Open it online | https://rushilk-moglix.github.io/echo_prototype_single/Echo-Prototype.html |
| Download it | https://rushilk-moglix.github.io/echo_prototype_single/ and press **Download the file**, then double click the file |
| Share it | Send `Echo-Prototype.html` by email or chat. It works offline |

Sign in with any email and password.

## What to look at

| Where | What |
| :--- | :--- |
| Overview | How calling is going: dialled, reached, completed, call status. Pick one agent at the top to see its own answers. |
| Input and "Picked up, not completed" | On the Overview: what was wrong in the uploaded rows, and why picked up calls did not finish. |
| Share | Top right of the Overview: picture, PDF, spreadsheet, or a report by email on a schedule. |
| Campaigns | New campaign: pick an agent, download its template, upload it, start. Calls play out in a few seconds. |
| A call | Click any call: recording, transcript, answers and every dial. |
| Follow ups | Contacts calling cannot settle: owner, notes, corrected number, call again. |
| Agents | Open an agent: Prompt, Call data, Answers, Settings. |
| Workspace switcher | Bottom of the side bar: a second workspace whose agent covers several rows on one call. |

## Good to know

- The data is invented sample data held in memory. It starts fresh each time the file is opened or reloaded.
- Calls are simulated. Nothing is dialled and nothing leaves your computer.
- Use Chrome or Edge.
- Page addresses use `#`, for example `Echo-Prototype.html#/overview`. You can send someone a link to a specific page.
- This is a prototype of the planned product, not the live product.

## Source

The file is built from the full prototype: https://github.com/rushilk-moglix/echo_prototype (`npm run build:single`).
The running demo of that prototype is at https://rushilk-moglix.github.io/echo_prototype/.
