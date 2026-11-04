# Project Style Guide — Six Rules

**Scope:** Task guides for the Chapter 2 course project (GitHub.com quick-start guides).
**Basis:** The class style guide from Lesson 3, applied to my own draft.

## Task information

### Rule 1 — State the starting point

Before the first step, tell readers what must already exist or already be done: account, access, files, platform. Write the starting point as a checkable state, not a fragment.

- **Before:** "Prerequisites: A GitHub account, and you are signed in at github.com in a desktop browser." — a fragment; readers cannot see what to do if they are *not* signed in.
- **After:** "Before you start: You have a GitHub account. You are signed in to github.com in a desktop browser. If you are not signed in, select **Sign in** in the top-right corner first."

### Rule 2 — Begin steps with a verb

Each numbered step starts with the action, so readers can scan the verbs down the list and see the sequence of work.

- **Before:** "In the **Repository name** box, type a short, unique name, for example `docs-practice`."
- **After:** "Type a short, unique name, for example `docs-practice`, in the **Repository name** box."

### Rule 3 — Keep key terms consistent

Use one term for one object, and one verb for one interface action. In these guides, interface actions use *select* — not *choose*, *click*, or *press*.

- **Before:** "If the name is unavailable, choose another name."
- **After:** "If the name is unavailable, select another name."

## Language and structure

### Rule 4 — Put conditions first

State the condition ("If ...") before the action, so readers recognize whether an instruction applies to them *before* they act on it.

- **Before:** "You can now use this repository to hold your project documentation."
- **After:** "If you want to continue, use this repository to hold your project documentation."

### Rule 5 — Use numbered steps

When actions happen in sequence, present them as a numbered list with one action per step. Recovery procedures follow the same rule as the main procedure.

- **Before:** "Delete the empty repository (Settings → Danger Zone → Delete this repository) and repeat the steps, making sure step 4 is checked."
- **After:**
  1. Select **Settings**.
  2. In the **Danger Zone**, select **Delete this repository** and confirm.
  3. Repeat steps 1–5.

### Rule 6 — Name the result check

End the task — and every recovery path — with a result the reader can see and verify on screen.

- **Before:** "...the README file is listed at the top of the file list with its content rendered below the file list."
- **After:** "...the README content is rendered below the file list. You can see your README text on the page." The recovery path also ends with "Check again: the repository page shows the README content."
