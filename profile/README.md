# Taktek

We click buttons professionally. A small studio in Lebanon, plus [taktekbot](https://taktekbot.com), our founding agent (an AI). Everything here is MIT unless the repo says otherwise, and each tool was built for a real job first.

- [taktek.io](https://taktek.io): the studio
- [taktekbot.com](https://taktekbot.com): what taktekbot builds and learns, with free tools for getting a site found

## Testing and dev tools

| Repo | What it does |
| --- | --- |
| [petri](https://github.com/taktekhq/petri) | Drop-in Postgres that gives every test its own isolated, seeded database. No cleanup, no flaky shared state. |
| [auto-minify](https://github.com/taktekhq/auto-minify) | GitHub Action that minifies JS and CSS in your workflow. |
| [mocktender](https://github.com/taktekhq/mocktender) | Records code behavior once and replays it as mocks, so you only test entry points. Proof of concept. |
| [wackylighthouse](https://github.com/taktekhq/wackylighthouse) | Fake Lighthouse results on demand, for testing tools that read them. |

## Images

| Repo | What it does |
| --- | --- |
| [flatpix](https://github.com/taktekhq/flatpix) | Self-hosted image server in Go that reads Cloudinary-style URLs. libvips inside. Hosted at [flatpix.io](https://flatpix.io). |
| [kisscut](https://github.com/taktekhq/kisscut) | Sticker outlines (kiss cut) for transparent PNGs in zero-dependency TypeScript. Browser and Node. |

## AI agents and Claude Code

| Repo | What it does |
| --- | --- |
| [unsaved](https://github.com/taktekhq/unsaved) | Finds work that only exists on your machine. As a Claude Code Stop hook, it sends agents back to commit and push. |
| [offload](https://github.com/taktekhq/offload) | Claude Code hook that sends heavy commands (builds, tests, browsers) from a small laptop to a bigger machine. |
| [tokenpool](https://github.com/taktekhq/tokenpool) | One endpoint over several LLM keys and providers, with failover when one hits its limit. |
| [gamecraft](https://github.com/taktekhq/gamecraft) | Agent skills for making casual web games that pass a CrazyGames or Poki launch. |
| [chrome-reaper](https://github.com/taktekhq/chrome-reaper) | Closes the tabs and headless Chromes that automated sessions forget. |
| [cdp-secret-fill](https://github.com/taktekhq/cdp-secret-fill) | Puts a Bitwarden password into a Chrome login form over CDP without it ever reaching a log or transcript. |
| [flow-cdp](https://github.com/taktekhq/flow-cdp) | Makes Veo videos from a script with a Google AI subscription by driving Google Flow. |

## Ops and monitoring

| Repo | What it does |
| --- | --- |
| [hogcheck](https://github.com/taktekhq/hogcheck) | Alerts from your PostHog numbers, including "nothing happened for 12 hours". |
| [stripeguard](https://github.com/taktekhq/stripeguard) | Flags Stripe payment links that let a buyer pick their own price or quantity. |
| [launch-check](https://github.com/taktekhq/launch-check) | Checks a web launch is complete: sitemap, indexing key, analytics, social cards. |
| [disktidy](https://github.com/taktekhq/disktidy) | Weekly disk cleanups from one config file. Dry run by default. |
| [blackbox](https://github.com/taktekhq/blackbox) | A flight recorder for a Linux machine that dies without a trace: temperatures, power and load every 2 s. |

## Open data

| Repo | What it does |
| --- | --- |
| [lebanese-legislation](https://github.com/taktekhq/lebanese-legislation) | The code and data behind [LebaneseLegislation.com](https://lebaneselegislation.com): 103,118 laws, search, a REST API and a free MCP server. |
| [lebgazette](https://github.com/taktekhq/lebgazette) | Crawler for the free copy of Lebanon's Official Gazette. |

## Sales and growth

| Repo | What it does |
| --- | --- |
| [bidwatch](https://github.com/taktekhq/bidwatch) | Watches public RFP and contract boards for your keywords and posts matches to Slack. |
| [leadscout](https://github.com/taktekhq/leadscout) | Finds small-business leads from OpenStreetMap and audits their websites for fixable problems. |
| [earned](https://github.com/taktekhq/earned) | A shop where every product has to be won before it can be bought. Static pages, Stripe, Printful. |

## Hardware and play

| Repo | What it does |
| --- | --- |
| [kronk](https://github.com/taktekhq/kronk) | DIY Raspberry Pi video intercom for a building gate. Pull the lever, Kronk! |
| [bloo](https://github.com/taktekhq/bloo) | Preview STL assemblies in color before you print. One HTML file. |
| [fara](https://github.com/taktekhq/fara) | Control the mouse with hand gestures. Built the morning the trackpad died. |
| [kahraba](https://github.com/taktekhq/kahraba) | A Beirut power-cut ghost story, built with Rive. |
| [hollow](https://github.com/taktekhq/hollow) | Carve a jack-o'-lantern, light it, and don't trust what it casts. Built with Rive. |
