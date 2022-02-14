# MCHC Automation

This code repository contains helpful scripts for automating some tech tasks.

These run automatically.

| Workflow | Status |
|----------|--------|
| :gear: [`update-shortlinks`][] | :scroll: [![Shortlink Badge][shortlink-badge]][shortlink-logs]

[`update-shortlinks`]: /.github/workflows/update-shortlinks.yml
[shortlink-badge]: https://github.com/patcon/mchc-automation/actions/workflows/update-shortlinks.yml/badge.svg
[shortlink-logs]: https://github.com/patcon/mchc-automation/actions/workflows/update-shortlinks.yml


## Technologies Used

- **Python.** A programming langauge common in scripting.
- [**`spreadsheet2shortlinks`**][spreadsheet2shortlinks]. Command-line tool for updating Rebrandly shortlinks from a spreadsheet.
- [**GitHub Actions.**][github-actions] A script-running service that runs scheduled tasks for us in the cloud. (Incoming)

[spreadsheet2shortlinks]: https://github.com/hyphacoop/spreadsheet2shortlinks
[github-actions]: https://github.com/features/actions

## Prior Art

- [`hyphacoop/worker-coop-scripts`](https://github.com/hyphacoop/worker-coop-scripts)
- [`CivicTechTO/civictechto-scripts`](https://github.com/CivicTechTO/civictechto-scripts)
