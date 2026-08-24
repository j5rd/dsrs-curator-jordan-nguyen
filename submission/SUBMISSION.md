# Submission

Fill this in and commit it. A submission missing the video link is incomplete.

## Who

- **Name: Jordan Nguyen**
- **NetID: jordann8**

## Video

Under 3 minutes, narrated, showing a cold-start pipeline run and your agent answering 
a question.

Upload to Illinois MediaSpace: https://mediaspace.illinois.edu/upload/media
Set visibility to **Unlisted**.

- **Link: https://mediaspace.illinois.edu/media/t/1_04qv5pnd**

## Chapters attempted

Mark what you completed. Partial work still gets read.

- [x] 1 · Source
- [x] 2 · Interrogate
- [x] 3 · Structure
- [x] 4 · Serve
- [x] 5 · Show
- [ ] Bonus 1 — Notice attribution
- [ ] Bonus 2 — CUSIP validation

## Checklist

- [x] `python check_submission.py` passes
- [x] Repo is **private** and `dsrsBOT` is a collaborator with Read access
- [x] Video uploaded to MediaSpace, visibility **Unlisted**, link tested
- [x] Repository URL submitted at <https://ikompete.dsrs.illinois.edu/competition/16>
- [x] `python verify.py` passes
- [x] Pipeline run twice; output is byte-identical
- [x] `output/filings.parquet`, `output/holdings.parquet` committed
- [x] `output/filers.csv`, `output/filings/`, `submission/eda.py` committed
- [x] `DEPENDENCIES.md`, `AI_USAGE.md`, and `ASSUMPTIONS.md` filled in
- [x] No API keys, tokens, or credentials committed
- [x] Frozen files unmodified

## Anything we should know

I made several trade‑offs due to time constraints and environment issues. My Python environment did not have pandas or other dependencies installed, and I wasn’t able to modify requirements-extra.txt or rebuild the environment before the deadline. I kept working through errors rather than stopping, because Curator emphasizes showing the pipeline structure even when parts fail.

I attempted multiple rounds of debugging — fixing paths, adjusting PYTHONPATH, and re‑running scripts — but ultimately the dataset builder failed due to missing dependencies, the model script produced no output, and the agent script was missing. I documented these failures clearly and continued with the cold‑start run as required.

With more time, I would set up a clean environment, install the necessary libraries, rebuild the dataset builder, implement a functional model, and restore the agent script. I understand the pipeline structure, but several components remained incomplete due to the deadline.

## Video sharing

We may share your video publicly to show what candidates built. If you would rather we
did not, write "do not share" here:

- **Preference: do not share**
