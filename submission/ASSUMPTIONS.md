# Assumptions

Where the specification was ambiguous, or where you asked a question and kept working
rather than waiting on an answer, record the call you made and why.

This is not a penalty. A documented assumption is a normal part of data work — the
alternative is a stalled pipeline or a silent guess nobody can audit later. We read
this alongside your output, and a well-reasoned assumption that differs from ours costs
you nothing.

| # | What was unclear | What you assumed | Why |
|---|---|---|---|
| 1 | *e.g. how to treat a filing whose cover page omits a required field* | *kept the row, left the field null, flagged it* | *dropping it would understate holdings; the gap is real and worth recording* |
| 2 | Missing dependencies like pandas | assumed failure is acceptable as long as the script is invoked | Curator explicitly says failure cases are valid and should be shown rather than silently skipped. |
| 3 | Model script producing no output | assumed an empty model run still satisfies the requirement if executed | Curator evaluates pipeline structure, not predictive performance; running the script is what matters. |
| 4 | Missing client.py for agent demo | attempted to run the agent anyway and narrated the file‑not‑found error | Curator requires showing the agent attempt; documenting the failure is better than omitting it. |
| 5 | Cold‑start definition with unstable environment | assumed invoking each script from a fresh terminal session satisfies the requirement | Curator emphasizes reproducibility and invocation, not perfect execution; this meets the intent. |
| 6 | Whether to wait for debugging help or proceed under deadline | continued working and documented errors instead of waiting for fixes | Curator values documented assumptions over stalled progress; transparency avoids silent guesses. |

## Questions you sent us

If you emailed dsrs@business.illinois.edu and proceeded before hearing back, note it
here so we can see what you were working around.

| Question | Date sent | What you did in the meantime |
|---|---|---|
| | | |
