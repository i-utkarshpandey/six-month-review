# Still hired? — The six-month review

A deeply unserious anniversary survey. British banter, a runaway No button, and a contract-renewal screen with an interactive dab.

Baby-pink edition: original CSS HR mascot, animated survey steps, bouncy choices, pressable buttons, a live escape counter, stamp reveal, and pink confetti.

## Run

Open `index.html` in any modern browser. No installation, build, fonts, CDN, API keys, or internet connection required.

## Upload to GitHub

Upload `index.html`, `.nojekyll`, and this README to the root of your repository. The included ZIP contains just these portable files; it excludes hosting metadata and Git history.

For GitHub Pages, use a branch-based deployment from your default branch and the repository root. The page uses no absolute asset paths, so repository subpaths work too. GitHub Pages availability and publishing options depend on your account and repository settings.

## Edit

All copy, CSS, and JavaScript are in `index.html`. Search for the question text to change it. Edit `--pink`, `--ink`, and `--bg` in the CSS to change the palette. Edit the `excuses` array for different runaway-button jokes.

## Behaviour

- Three short survey steps, with a required rating and optional perks and requests.
- No dodges a mouse hover, touch, or keyboard activation, stays inside the viewport, and avoids the Yes button.
- Yes shows the chosen answers and optional requests, then offers an interactive dab.
- Answers exist only in the current browser tab. They are not sent to anyone or saved on a server. Reloading clears them.
- Keyboard focus styles, labelled controls, live status messages, and reduced-motion support are included.

## Inspiration

Original copy and implementation, informed by Reddit slang discussions:
- https://www.reddit.com/r/ukdrill/comments/8wrbzj/ — UK drill slang cheat sheet
- https://www.reddit.com/r/AskUK/comments/rzcg2f/what_does_take_the_piss_mean/

The copy deliberately mixes British slang with the requested internet phrases; it is not presented as an authentic drill glossary.

## Motion

Animations are short CSS transforms and opacity transitions, with native Web Animations for the mascot wobble. The Motion button disables decorative animation; system reduced-motion settings are also respected. The No button still changes location because that is the core joke. No animation library is needed.

## 2026 design research

These are inspiration sources, not copied code or assets:
- https://schoolofmotion.com/blog/websites-with-great-animation-2026 — playful character motion and purposeful transitions, including Dropbox's brand site.
- https://webflow.com/blog/microinteractions — interaction feedback and restrained hover effects.
- https://www.reddit.com/r/webdev/comments/1andc6h/i_made_a_simple_valentine_site/ — Valentine-site feedback, escaping buttons, hover feedback and mobile readability.
- https://www.reddit.com/r/web_design/comments/1wqpdr0/showoff_saturday_planning_to_add_more_small/ — keep animations brief, useful and optional.

## Validation

JavaScript syntax and simulated survey-flow checks were run. Live browser visual QA was unavailable in the creation environment; check the page on your phone before sharing.
