# Privacy

KL Rush is a free browser game. It has no accounts, no ads, no cookies and no analytics or tracking scripts.

## Error reports (from version 0.2)

To find and fix problems on devices the developer doesn't own, the game can send **anonymous error reports**. They are switched on by default and you can turn them off at any time in **Settings → Error reports**.

A report contains only:

- the game version (for example `0.2.0-preview`);
- browser name and device type (for example "Safari · iOS"), the graphics renderer (WebGPU or WebGL2), the graphics quality setting and the window size;
- how long each loading step took;
- for errors: the error message and the part of the game's code where it happened (stack trace);
- whether you were on the title screen or playing.

The game also sends one report if loading takes longer than 20 seconds, at most once per device per version.

Reports **never** include your name, email, account, location, save game, or anything you type. A session sends at most three reports, and the same error is sent only once.

Reports are stored privately in the developer's Vercel Blob storage (Singapore region). Only the developer can read them, and they are deleted after 90 days.

KL Rush does not store IP addresses. Like any website, the hosting provider (Vercel) processes connection details such as IP addresses to deliver the site, under its own [privacy policy](https://vercel.com/legal/privacy-policy).

## Data on your device

Your progress and settings are saved in your browser's local storage on your device. They are not uploaded anywhere. **Export backup** in Settings creates a file only when you choose to. Clearing your browser's site data deletes your progress.

## Feedback and donations

- The **Feedback** button opens a form on GitHub. Anything you post there is public and covered by [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
- The **Support** button opens Ko-fi. If you donate, Ko-fi and its payment providers handle that under their own policies. The game itself receives nothing from them.

## Questions

Open an issue on this repository. Please don't include personal details, because issues are public.

_Last updated: 7 October 2026._
