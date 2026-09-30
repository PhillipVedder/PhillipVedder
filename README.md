# Hi, I'm Phillip

I'm a computer science graduate interested in **graduate software engineering roles**. I build applications around things I care about, working across interactive interfaces, application logic, and data storage.

**Selected projects:** [Melt · portfolio sandbox](#melt) · [Gym Paradise · 3D gym builder](#gym-paradise)

## Melt

**Make portfolio allocation tangible.**

[![Melt's portfolio sandbox with proportional slime holdings and a transfer ticket](https://raw.githubusercontent.com/PhillipVedder/melt-portfolio/main/docs/images/sandbox.png)](https://github.com/PhillipVedder/melt-portfolio)

A working local application built with **TypeScript, React, Canvas 2D, D3 and Node.js**. Real Finnhub quotes drive a virtual-money portfolio: each holding becomes a slime blob sized by its dollar value. Drag between holdings to stage a transfer, review the exact amount, and see the allocation change.

The expressive interface sits on a tested decimal accounting model, with fractional shares, reversible transfers, quote-freshness checks, validated backups, and independent price-shock scenarios. The repository includes deterministic unit and browser tests, accessibility checks, architecture decisions, and an independent code-review record.

**[Explore the repository](https://github.com/PhillipVedder/melt-portfolio)** · [Architecture](https://github.com/PhillipVedder/melt-portfolio/blob/main/docs/ARCHITECTURE.md) · [Run it locally](https://github.com/PhillipVedder/melt-portfolio#quick-start) · [Checks](https://github.com/PhillipVedder/melt-portfolio/actions)

*Paper portfolio only. No real trades or investment advice. Local use requires your own Finnhub key; there is no public shared-key demo.*

## Gym Paradise

**Design a dream gym, customise the space, then step inside it in 3D.**

[![Gym Paradise's working 3D gym editor](https://raw.githubusercontent.com/PhillipVedder/gym-paradise/main/docs/images/build.jpg)](https://github.com/PhillipVedder/gym-paradise)

A working browser prototype built with **TypeScript, React, Babylon.js and Cloudflare Workers**. It combines a 36-type equipment catalogue, first-person navigation, room customisation, private photo storage and training records.

The engineering work includes validated placement, camera controls, revision-based save conflicts, ownership checks, and automated tests. The repository includes real screenshots, architecture notes, a roadmap, and a local demo that needs no cloud account.

**[Explore the repository](https://github.com/PhillipVedder/gym-paradise)** · [Architecture](https://github.com/PhillipVedder/gym-paradise/blob/main/docs/architecture.md) · [Run it locally](https://github.com/PhillipVedder/gym-paradise#try-it-locally) · [Checks](https://github.com/PhillipVedder/gym-paradise/actions)

## What I'm working with

- **Interfaces and graphics:** TypeScript, React, Canvas 2D, D3, Babylon.js, responsive CSS and touch interaction.
- **Application engineering:** decimal accounting, validation, HTTP and streaming APIs, SQL, private storage and concurrency handling.
- **Development workflow:** GitHub Actions, Vitest, Playwright, accessibility checks, reproducible setup and documented design decisions.

## How I Build

I pair visual experimentation with conventional controls, explicit validation, regression tests, and documented trade-offs. Each featured repository has real screenshots, setup instructions, and a candid account of what is and is not implemented.

My projects are built iteratively with AI assistance. Product direction, implementation, verification, and remaining limitations are documented alongside the code. Current priorities include broader browser and physical-device testing, accessible interactions, and rendering performance.
