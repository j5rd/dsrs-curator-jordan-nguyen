# AI Usage

Declare what you used and how. We are not scoring the amount — we are checking that
you can account for your own work.

## Tools used

Copilot (Microsoft), ChatGPT (OpenAI)

## Where you used them

I used AI tools throughout the project mainly for debugging help, clearing structure, and clarifying Curator requirements. Below is a chapter‑by‑chapter breakdown.

| Chapter | How you used AI |
|---|---|
| 1 · Source | I used AI to help understand how the dataset builder should be structured and what fields Form 4 filings normally contain. AI helped me reason about the expected pipeline behavior even though my environment didn’t detect filings. |
| 2 · Interrogate | I used AI to clarify how the agent should respond to questions and what Curator expects for the “success” and “failure” cases. AI helped me draft the questions I would ask the agent. |
| 3 · Structure | AI helped me understand how the dataset builder and model scripts should connect, and how to narrate the pipeline even when the dataset was empty or dependencies were missing. |
| 4 · Serve | I used AI to help write the short narration script for the video and to understand how to present the agent portion even though client.py was missing and the agent couldn’t run. |

## What you would change

There were parts of the pipeline that failed due to missing dependencies (like pandas) and missing files (like client.py). AI helped me debug these issues, but I wasn’t able to fully resolve them before the deadline.

If I had more time, I would:

Rewrite the dataset builder to handle missing dependencies more gracefully

Rebuild the model script so it produces meaningful output

Implement or restore client.py so the agent can run properly

Clean up the environment so Python paths and imports work consistently

I understand the structure of the pipeline, but some of the AI‑generated debugging steps were rushed due to time constraints, and I would refine them if I had more time.
