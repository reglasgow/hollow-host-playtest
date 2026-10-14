# HOLLOW HOST — free Android playtest

You are a small parasite inside a dead colossus. Explore connected rooms, collect relics and fight the creatures guarding its heart. Move with your left thumb and aim/shoot with your right.

**[Download APK v0.6.18](https://github.com/reglasgow/hollow-host-playtest/releases/download/android-0.6.18/Hollow-Host-Godot-0.6.18-test.apk)** (89.1 MB). Android 7.0+, ARM64/ARMv7, landscape. No account or payment required. Update the previous native Godot APK without uninstalling to preserve progress.

**[Game page and feedback](https://gamecreepstudio.itch.io/hollow-host)**

[Watch the 50-second English 1080p trailer](https://github.com/reglasgow/hollow-host-playtest/releases/download/android-0.6.17/Hollow-Host-Montaggio-2D-10-1080p.mp4). The trailer combines prepared native gameplay from an earlier build with illustrated promotional cinematics made outside the engine; the cinematics are not playable scenes.

## What changed

Attacking enemies and bosses now have small, grounded visual movements. Hits have a brief sprite-only animation pause and an impact response. Critical hits, player damage and major impacts have subtle camera movement. These effects leave movement, collisions and damage unchanged. Settings > Reduced motion & camera shake disables the added deformation and camera movement.

English is the default. Settings > Language provides two clearly marked buttons, English and Italiano; selection applies immediately and is saved. This is an early development candidate, not a finished 1.0 or a Google Play release.

## A useful 10-minute test

Play the tutorial and a few rooms, then tell us:
1. Are moving and aiming comfortable on your phone?
2. Which attack or room exit is hard to read?
3. Where did you stop, and why?

Ten minutes is a suggested test window, not an observed average. Use FEEDBACK in Settings, Pause or after a run, or leave a comment on the game page. Written feedback is submitted only when you press SEND and does not require analytics consent. Please avoid personal information; device model and Android version are optional.

## Optional measurements and disclosures

Analytics are disabled until explicit consent. You can decline and play normally. With consent, active play time, movement/aim time, tutorial progress, room visits, run outcomes, semantic UI actions and coarse 12x8 initial control-touch cells go to the existing PostHog Cloud USA project. A random installation code is used; no name, e-mail, advertising ID, location, screen/audio/keyboard recording, session replay or analytics SDK. Only Android INTERNET permission is requested.

Written feedback is a separate deliberate submission, includes build/session/room context and is queued locally when offline with bounded retries. Settings > Playtest analytics lets you stop measurements or request deletion. Deletion requests are handled by the team, not an immediate automatic purge. The project's one-year query window is not a guarantee of automatic deletion. Version 0.6.14 remains an offline candidate without these measurements.

Contains stylized blood and body horror. Development uses AI assistance for code, generated artwork and music composition; the soundtrack uses sampled instruments and wordless choir, not a recorded live orchestra or singers.

## Verification and limits

The signed APK and its exact compiled game resources passed automated checks. There are 51 native checks for combat feedback, language, consent, written feedback and persistence, plus an 18-case seeded simulation comparison against 0.6.17: damage, movement, trajectories and save snapshots matched. These tests used native Windows Godot and generated no remote analytics. They do not exercise Android native execution or establish human enjoyment.

**Physical Android testing, human balance/listening, battery and thermal measurements are NOT RUN by the agent.** We need real device feedback before considering 1.0. Source remains in a separate private repository. Older public test builds remain available for comparison.

APK SHA256: `2995b1120cd1467f70bf868070cb5c8e2cf5ee8a997c585318a7295d914ad40d`
