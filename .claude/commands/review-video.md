---
description: "Retention review of a video — where it loses viewers, and the re-cut that wins them back"
argument-hint: "path/to/video.mp4 [optional: platform, goal, or what to focus on]"
---

Launch the `director` agent (Agent tool, `subagent_type: "director"`) to review this video
for retention.

Pass it, verbatim: `$ARGUMENTS`

If no path was given, ask for the file path first — do not review anything you haven't seen.

Relay the agent's full note back to the user. Do not summarize it away: the retention map,
the timestamps, and the re-cut list are the deliverable.
