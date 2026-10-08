# Privacy

KL Rush is a free browser game. It has no accounts, no ads, no cookies and no analytics or tracking scripts.

## Error reports (from version 0.2)

To find and fix problems on devices the developer doesn't own, the game can send **anonymous error reports**. They are switched on by default and you can turn them off at any time in **Settings → Error reports**.

A report can contain these technical diagnostics:

- the game version (for example `0.2.0-preview`);
- browser name and device type (for example "Safari · iOS"), the graphics renderer (WebGPU or WebGL2), graphics quality, driving physics and window size;
- how long each loading step took;
- for errors: the error message and the part of the game's code where it happened (stack trace);
- whether you were on the title screen or playing;
- graphics-loss details, loading stage and whether the page was visible or in the background;
- browser and page context collected by Sentry, such as the page address and browser information.

The game also sends a report if loading takes longer than 20 seconds, once per version for that browser.

The game does not attach your name, email, account, location, saved progress or input fields to these reports. Each visit sends at most three error or slow-load reports, plus at most two benchmark reports that you separately choose to send. Consecutive duplicate errors are filtered.

Reports are sent to the developer's project on [Sentry](https://sentry.io), an error-monitoring service, in Sentry's EU data region. Access and retention follow the project's Sentry settings.

The game disables Sentry's default personal-data collection and sends no user identifiers. Sentry and the hosting provider (Vercel) handle connection details such as IP addresses to receive and deliver data, under their own privacy policies ([Sentry](https://sentry.io/privacy/), [Vercel](https://vercel.com/legal/privacy-policy)).

## Benchmark results (from version 0.4)

**Settings → Benchmark** measures how smoothly the game runs on your device. Running a benchmark does not upload its result automatically.

- **Send result anonymously** sends technical benchmark diagnostics to Sentry: the score and recommendation, frame rates and frame times, CPU and physics timings, per-scene results, draw calls, loading times, memory counts, graphics-chip name, renderer and graphics settings, screen size, browser and system names, and game version. It also includes the game and browser context described above. This action is unavailable while **Error reports** is off, and you can send at most two results per visit. The developer uses these results to see how the game runs on real devices.
- **Share in Feedback** opens GitHub's feedback form with the displayed result filled in. GitHub receives that prefilled text when the form opens, but an issue becomes public only if you submit it. This is a separate action from sending a result to Sentry.
- **Copy result** copies the displayed result to your clipboard.

## Data on your device

Your progress and settings are saved in your browser's local storage on your device, as is your choice of graphics engine (Settings → Graphics engine). Saved progress stays on your device. Diagnostic reports include the settings described above. **Export backup** in Settings creates a file only when you choose to. Clearing your browser's site data deletes your progress.

## Feedback and donations

- The **Feedback** button opens a form on GitHub. Anything you post there is public and covered by [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
- The **Support** button opens Ko-fi. If you donate, Ko-fi and its payment providers handle that under their own policies. The game itself receives nothing from them.

## Questions

Open an issue on this repository. Please don't include personal details, because issues are public.

_Last updated: 8 October 2026 (benchmark reporting and technical-report context)._
