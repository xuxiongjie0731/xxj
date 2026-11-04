# Review Record — A Documentation Edit

**Project:** Chapter 2 guide, revised with the Chapter 3 style rules.
**Date:** 4 November 2026

## 1. Change log (8 changes, six required)

| # | Location | Before | After | Rule | Why it helps the reader |
|---|----------|--------|-------|------|--------------------------|
| 1 | Prerequisites | "A GitHub account, and you are signed in at github.com in a desktop browser." (fragment) | "Before you start" list with three checkable states, plus "If you are not signed in, select **Sign in** in the top-right corner first." | 1 — State the starting point | Readers confirm every precondition and know what to do if one is missing. |
| 2 | Step 2 | "In the **Repository name** box, type a short, unique name..." | "Type a short, unique name, for example `docs-practice`, in the **Repository name** box." | 2 — Begin steps with a verb | The verb comes first, so scanning the step list shows the actions immediately. |
| 3 | Step 2 | "If the name is unavailable, choose another name." | "If the name is unavailable, select another name." | 3 — Keep key terms consistent | One verb (*select*) for every interface action removes hesitation about whether *choose* means a different kind of action. |
| 4 | Step 3 | "select the **Private** option" | "select **Private**. (You can change this later in **Settings**.)" | 3 — Keep key terms consistent | The step names the exact label, not a paraphrase of it, and answers the most common first-time worry. |
| 5 | Step 4 | "Select the checkbox **Add a README file**." | "Select the **Add a README file** checkbox." | 3 — Keep key terms consistent | The term readers see on screen ("Add a README file") is the term the guide uses. |
| 6 | Result check, recovery | "Delete the empty repository (Settings → Danger Zone → Delete this repository) and repeat the steps, making sure step 4 is checked." | A numbered recovery list (Settings → Danger Zone → Delete → repeat steps 1–5) | 5 — Use numbered steps | A recovery path is still a procedure; one action per numbered step prevents a panicked reader from skipping the confirmation dialog. |
| 7 | Result check, recovery | No check after the recovery actions | "Check again: the repository page shows the README content." | 6 — Name the result check | The reader can verify that the recovery actually worked instead of guessing. |
| 8 | Next steps | "You can now use this repository to hold your project documentation." | "If you want to continue, use this repository to hold your project documentation." | 4 — Put conditions first | The condition ("if you want to continue") comes before the action, so readers know the step is optional before following it. |

Additional edit supporting Rule 6: the result check was tightened from "the README file is listed at the top of the file list with its content rendered below the file list" to "the README content is rendered below the file list. You can see your README text on the page." — a visible, screen-checkable result.

## 2. Peer comment (silent peer review)

Peer comment: **"At step 3, I need to know whether I can change Private to Public later."**

Response and revision: I checked GitHub Docs (Setting repository visibility): a repository's visibility can be changed in **Settings** at any time. I added the parenthetical "(You can change this later in **Settings**.)" to step 3 of `after.md` and recorded it as change 4 above.

## 3. Result check (verification)

- I followed `after.md` in a desktop browser (github.com, English interface) and created a private repository with a README. **Observed:** the new repository page shows the README content rendered below the file list — pass.
- I verified every interface label in the revised guide against the live interface and GitHub Docs: **+** menu, **New repository**, **Repository name**, **Private**, **Add a README file**, **Create repository**, **Settings**, **Danger Zone**, **Delete this repository** — all match.
- One item to re-verify after any GitHub interface update: the location of **Delete this repository** inside the **Danger Zone**.

## 4. AI disclosure

Per the lesson's AI-assisted writing guidance: AI assistance was used to draft the six-rule style guide, propose revisions, and prepare this change log. The author reviewed every rule and change, verified all interface labels and the recovery path against GitHub Docs and the live web interface, and performed the result check personally.
