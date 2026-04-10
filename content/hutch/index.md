+++
title = "Hutch"
description = "An iOS client for SourceHut."
[extra]
section_label = "Project / Hutch"
meta = "iOS / SourceHut / Active"
+++

<a href="https://apps.apple.com/us/app/hutch-for-sourcehut/id6760742299" class="store-link" aria-label="Download Hutch on the App Store">
  <img src="/storebutton.svg" class="store-img" alt="Download on the App Store">
</a>

SourceHut workflows, built for mobile.

Hutch is a fast, native iOS app for working with SourceHut when you are away from your desk. It focuses on the things that matter on mobile: triaging work, reviewing patches, monitoring builds, following discussions, and managing repositories and tickets without a browser.

Hutch is now available on the App Store for iPhone.

## Why It Exists

SourceHut is intentionally simple, efficient, and workflow-focused. Hutch brings that same philosophy to iOS with an interface designed for quick decisions and real work on the go.

Instead of treating mobile as a stripped-down viewer, Hutch is meant to be a practical client for reading, responding, creating, and managing work across the SourceHut ecosystem.

## What It Does

- Review patch threads and browse mailing lists
- Manage trackers, tickets, assignees, labels, and comments
- Browse Git and Mercurial repositories, files, refs, commits, and diffs
- Submit, monitor, retry, and inspect builds and logs
- Follow projects linking repositories, trackers, and lists
- Manage profile settings, SSH keys, PGP keys, and access tokens

## Interface

From patch review to trackers, builds, repositories, and project organization, Hutch is built to make SourceHut feel at home on iOS.

{% carousel(aria_label="Hutch screenshots") %}
<figure class="shot-card">
  <img src="https://img.cleberg.net/apps/hutch/screenshots/iphone/01_patch.jpg" alt="Patch review screenshot" loading="lazy">
  <figcaption>Review patches anywhere</figcaption>
</figure>
<figure class="shot-card">
  <img src="https://img.cleberg.net/apps/hutch/screenshots/iphone/02_thread.jpg" alt="Threaded inbox screenshot" loading="lazy">
  <figcaption>Stay on top of discussions</figcaption>
</figure>
<figure class="shot-card">
  <img src="https://img.cleberg.net/apps/hutch/screenshots/iphone/03_builds.jpg" alt="Builds screenshot" loading="lazy">
  <figcaption>Monitor builds in real time</figcaption>
</figure>
<figure class="shot-card">
  <img src="https://img.cleberg.net/apps/hutch/screenshots/iphone/04_tickets.jpg" alt="Tickets screenshot" loading="lazy">
  <figcaption>Manage issues on the go</figcaption>
</figure>
<figure class="shot-card">
  <img src="https://img.cleberg.net/apps/hutch/screenshots/iphone/05_repo.jpg" alt="Repository diff screenshot" loading="lazy">
  <figcaption>Explore your code</figcaption>
</figure>
<figure class="shot-card">
  <img src="https://img.cleberg.net/apps/hutch/screenshots/iphone/06_projects.jpg" alt="Projects screenshot" loading="lazy">
  <figcaption>Everything in one place</figcaption>
</figure>
<figure class="shot-card">
  <img src="https://img.cleberg.net/apps/hutch/screenshots/iphone/07_actions.jpg" alt="Build submission screenshot" loading="lazy">
  <figcaption>Take action instantly</figcaption>
</figure>
{% end %}

## Major Features

- Home dashboard with projects, assigned tickets, recent builds, and inbox shortcuts
- Unread-first inbox with thread detail, patch rendering, and reply via Apple Mail
- Git and Mercurial repository browsing, settings, ACLs, and creation flows
- Tracker and ticket workflows including comments, assignees, resolutions, and labels
- Build submission, build history, log viewing, cancellation, and rebuild flows
- Project views linking repositories, trackers, and mailing lists into one hub

## Built For SourceHut Users

- Native Swift interface with no analytics, ads, or tracking SDKs
- Deep links for repositories, tickets, and builds via `hutch://`
- Share actions across repositories, files, commits, tickets, builds, and profiles
- Pull-to-refresh, loading states, empty states, and error overlays across major screens
- Keychain-backed authentication with secure SourceHut personal access tokens
- Profile management including avatars, SSH keys, PGP keys, and token/grant viewing

## Resources

- [Download on the App Store](https://apps.apple.com/us/app/hutch-for-sourcehut/id6760742299)
- [Project homepage](https://sr.ht/~ccleberg/Hutch/)
- [Issue tracker](https://todo.sr.ht/~ccleberg/Hutch/)
- [hutch-devel mailing list](https://lists.sr.ht/~ccleberg/hutch-devel)
- [hutch-announce mailing list](https://lists.sr.ht/~ccleberg/hutch-announce)
- [Privacy policy](/hutch/privacy-policy/)
