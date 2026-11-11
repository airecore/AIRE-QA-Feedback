# AIRE QA Feedback

Tester feedback for the **AIRE Extension** (the Chrome extension for claude.ai).
There's no code here. This repository exists only to collect reports from
testers as **Issues**, so the team can discuss, assign and close them.

## Where the feedback is

Open the **Issues** tab. Each issue is one report a tester sent from the
extension (Settings → **Send feedback or report a problem**). It includes:

- what the tester wrote
- the type: `bug`, `enhancement` or `question`, plus `tester-feedback`
- the extension build and browser they used
- their recent activity and errors, if they chose to attach them

Testers' emails are not included here. They're on the QA dashboard.

## What is not here

Automatic error reports. Those go to the QA dashboard
(https://claude-extension-xi.vercel.app/qa.html), grouped by cause, so one
bug that happens 50 times doesn't open 50 issues.

## Getting notified

Click **Watch** → **All Activity** (top right) to get an email or app
notification for every new report.

## How issues get here

The AIRE backend opens them with a GitHub token that can only read and write
issues in this one repository. Nothing else in the organisation is
accessible to it.

This repository is private because the extension's code repository
(airecore/AIRE-Claude-Extension) is public.
