# Reiden Johnson

Software developer at Rapid Impact in Maine, building client applications with AI agents as a core part of the
workflow. I also build Android and Galaxy Watch apps of my own, for things I actually do. Computer Information
Technology graduate (BYU–Idaho, 2026) and AWS Certified Cloud Practitioner.

[LinkedIn](https://www.linkedin.com/in/reidenjohnson/)

## Kairos: when and where to hunt

An Android and Galaxy Watch app that reads live weather and my trail-camera photos, then lays out the best sits for the
week. Expert hunting advice contradicts itself, so AI agents turned 75 expert videos into 434 cited lessons and flagged
the 112 places where hunters and research disagree. [See the code →](https://github.com/reidenjohnson/kairos)

<p>
  <img src="https://raw.githubusercontent.com/reidenjohnson/kairos/main/docs/screenshots/kairos-today.png" width="230" alt="Kairos Today screen">
  <img src="https://raw.githubusercontent.com/reidenjohnson/kairos/main/docs/screenshots/kairos-forecast.png" width="230" alt="Kairos Forecast screen">
  <img src="https://raw.githubusercontent.com/reidenjohnson/kairos/main/docs/screenshots/kairos-learn.png" width="230" alt="Kairos Learn screen">
</p>

## Nock: archery scoring by camera

An Android and Galaxy Watch app for archery practice. Point the phone at the target and it finds every arrow hit on its
own, scores it, and sends it to your watch, so you never walk downrange to score. The watch also records how you hold,
release, and follow through on each shot, and compares it with your own average. Live computer vision was draining the
phone, so I profiled it on the real device: reusing one image buffer cut each frame from 15 ms to 1.3 ms, and CPU use
dropped from 173% to 125% of a core. [See the code →](https://github.com/reidenjohnson/nock)

<p>
  <img src="https://raw.githubusercontent.com/reidenjohnson/nock/main/docs/screenshots/nock-home.png" width="230" alt="Nock home screen">
  <img src="https://raw.githubusercontent.com/reidenjohnson/nock/main/docs/screenshots/nock-review.png" width="230" alt="Nock shot review">
</p>

## Latch and Tagwise: two free apps built around NFC tags

**Latch** is a focus blocker. Stick a cheap NFC tag somewhere you have to walk to, tap it to lock the apps that pull you
in, and tap it again to get them back. It runs on schedules, has separate modes for work or sleep, and tracks your focus
streaks. The hard part was making it impossible to trap yourself: calls, Settings, and emergency apps are never blocked,
there are five emergency unlocks a year, and it needs no root or admin access.

**Tagwise** is an NFC reader and writer with every feature free. It shows what's on a tag in plain words instead of hex,
writes links, Wi-Fi logins, contacts, and more, checks every write so you know it worked, and can lock a note with
AES-256 encryption. [See the code →](https://github.com/reidenjohnson/latch)

<p>
  <img src="https://raw.githubusercontent.com/reidenjohnson/latch/main/docs/screenshots/latch-welcome.png" width="230" alt="Latch welcome screen">
  <img src="https://raw.githubusercontent.com/reidenjohnson/latch/main/docs/screenshots/tagwise-read.png" width="230" alt="Tagwise read screen">
  <img src="https://raw.githubusercontent.com/reidenjohnson/latch/main/docs/screenshots/tagwise-write.png" width="230" alt="Tagwise write screen">
</p>

## Tools I use

Kotlin, Jetpack Compose, Python, TypeScript and JavaScript, Next.js, SQL, Claude Code and AI agents, Git and GitHub.
