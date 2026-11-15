# TeamFlow — Learning Log

## Day 2 — Ordering Problems by Dependency

Priya now writes things down in a spreadsheet. One row per request. It works for two weeks. Then the spreadsheet has 60 rows and four things break.

### The Four Breaks

1. **Lost edits.** Two people edit the spreadsheet at the same time. One person's changes vanish.
2. **No filtering.** A developer asks "which tasks are mine?" Priya scrolls through 60 rows every time.
3. **No history.** A task is marked done, but nobody knows who did it, when, or why.
4. **No access control.** A new person joins and can see and edit everything. There is no way to hide confidential rows.

### What I Learned

Not every problem is equal. Some problems **block** other solutions. Those get fixed first.

The question is never "which is most serious?" The question is:

**Which problem must be solved first so that other problems become solvable?**

Today the answer is: we need identity and ownership before history, filtering, or access control can work.

The absolute foundation is **identity**. Each person must be known and identified before anything else can work.

### My Reasoning

I noticed that fixing break 4 (access control) also helps fix break 3 (history), because history is tracked through credentials. But I learned the real rule is dependency, not preference:

**Break 3 depends on the foundation that break 4 provides. Without identity and ownership, history cannot work.**

### Mistakes I Made

1. I first chose a problem by how serious it felt, not by "is it depended on anything".

### What I Corrected

1. Order problems by dependency, not by severity.

---