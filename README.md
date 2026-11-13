# Marathon Training Log

A simple training planner and logbook for one marathon build, all in a single web page.

It gives you a week-by-week plan for the 28 weeks leading up to the Cape Town Marathon (Sunday 23 May 2027), then lets you log what you actually did and see how the training is going.

## The idea

Most training plans are a static PDF or spreadsheet. You follow them, forget to track anything, and lose track of how the build is really going. This tool puts the plan and the log in the same place:

- The plan tells you what to run each day, with a target pace for every session.
- You tick sessions off, add the details, and get quick feedback on each run.
- The charts and calendar show how your real training compares to the plan.

## What it does

- **Plan:** 28 weeks across Base, Build and Taper phases, with a long run that builds to 32 km, alternating interval and tempo sessions, and a lighter week every fourth week. Every run is at least 5 km.
- **Pace targets:** worked out from your goal time, or from a recent race result.
- **Logging:** record distance, time, heart rate and effort for each run. Log strength sessions and extra workouts whenever you like, or mark a session as skipped with a reason.
- **Feedback:** after each run, a short check on whether you ran it too fast, too slow or on target.
- **Progress:** weekly kilometres against the plan, trend charts, a calendar of the whole build, and milestones.

## Using it

Open `index.html` in any browser, or host it for free with GitHub Pages:

1. In the repository, go to **Settings → Pages**.
2. Choose the main branch as the source and save.
3. Your page appears at `https://<your-username>.github.io/<repo-name>/`.

## Your data

Your log is saved in your browser, on the device you use. Nothing is uploaded anywhere. Clearing your browser data erases it, so use the CSV export on the Progress tab now and then to keep a backup.

## Making it your own

The plan is a simple list of weekly distances near the top of the script in `index.html`, along with the start date, race date and goal time. Change those to build a plan for a different race.

## Built with

HTML, CSS and vanilla JavaScript. No frameworks, no installs, no dependencies. Built with Claude.