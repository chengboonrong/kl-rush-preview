# Privacy

KL Rush is a free browser game. It has no accounts, no ads and no cookies. From version 0.4.20 the public site counts visits with cookie-free analytics (see below), and it has no advertising or cross-site tracking.

## Visit counts (from version 0.4.20)

The public site (kl-rush.vercel.app) uses [Vercel Web Analytics](https://vercel.com/docs/analytics/privacy-policy) to count visits. It records page views and, for each visit, the country, device type, browser, operating system and the site that referred you. It sets no cookies, does not follow you across other sites, and stores no name, account or saved progress. Vercel handles connection details such as IP addresses to produce the counts, under [its privacy policy](https://vercel.com/legal/privacy-policy). The script loads only on kl-rush.vercel.app, after the loading screen. Browsers or extensions that block trackers will usually block it, and then nothing is counted.

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

## Online rooms (test builds only)

The developer is testing online rooms where friends drive around KL together. They are not in the public game. They appear only in test builds opened with a special link, and a player who never opens a room sends nothing to the room server.

- **Who can join.** Only people who have the room's code. There is no room list, no chat and no voice.
- **What the room server processes.** While you are in a room it handles your IP address (to keep the connection open), your character's name, where your car or character is and which way it is moving, the room code and the game version. To stop anyone guessing codes, it also counts how often an address creates or joins rooms over one minute.
- **Where it runs.** On [Cloudflare](https://www.cloudflare.com) (Workers and Durable Objects), in a data centre near the players, usually Singapore. Cloudflare handles connection details under [its privacy policy](https://www.cloudflare.com/privacypolicy/).
- **What is kept.** Nothing after the room closes. A room closes 10 minutes after the last player leaves, and its record is deleted. The room server keeps no request logs.
- **Your progress.** Rooms never read or change your saved progress.
- **Test measurements.** Test builds show connection and frame-time numbers on your own screen. **Copy log** copies them to your clipboard, and they go nowhere else unless you paste them somewhere.

## Data on your device

Your progress and settings are saved in your browser's local storage on your device, as is your choice of graphics engine (Settings → Graphics engine). Saved progress stays on your device. Diagnostic reports include the settings described above. **Export backup** in Settings creates a file only when you choose to. Clearing your browser's site data deletes your progress.

## Feedback and donations

- The **Feedback** button opens a form on GitHub. Anything you post there is public and covered by [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
- The **Support** button opens Ko-fi. If you donate, Ko-fi and its payment providers handle that under their own policies. The game itself receives nothing from them.

## Questions

Open an issue on this repository. Please don't include personal details, because issues are public.

_Last updated: 16 October 2026 (online rooms in test builds)._
