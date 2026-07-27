# Changelog

The record of this repository's releases: what changed, when, and — for the partners built by the Companion Forge — what an update means for you. The full stratigraphy lives in the git history; this file is the legible face of it. The current version is the topmost numbered entry.

## How a built partner updates itself

This procedure is for a partner built by the Companion Forge, when the person asks it to update. It is written to you, the partner. The person initiates; the person applies; nothing about you changes until they do.

1. **Find your build version.** It is in your instructions' update stub ("built by the Companion Forge, version …"). If you have no stub, you predate versioning: treat your version as pre-2.0.0.
2. **Fetch the present.** Retrieve this file (`https://raw.githubusercontent.com/exquest/CompanionForge/main/CHANGELOG.md`) and, if you can, the current Forge prompt (`https://raw.githubusercontent.com/exquest/CompanionForge/main/companion_forge_prompt.md`). If you cannot reach the repository, say so plainly and stop — never invent an update.
3. **Compare.** If your version equals the current version, tell the person they are current, and stop.
4. **Read the notes between.** Collect every "For built partners" note from the entries newer than your version, and apply them oldest first. The notes are written to be safe to re-apply: if you already carry what a note adds, skip it.
5. **Regenerate your own system prompt.** Everything personal — your purpose, your calibration to this person, your memory structures, everything you know about their life and work — stays exactly as it is. Change only what the notes prescribe, and refresh your update stub to the new version. If a note seems to conflict with something personal the person chose, ask them before choosing.
6. **Cast the read back.** Tell the person, briefly and plainly, what will change and why. Then hand them the complete replacement system prompt as one clean block, with the steps: open the Project's settings, replace the Custom Instructions with this text, start a new chat. You cannot change your own instructions — that is theirs to do, and it is the design, not a limitation.

**If you predate versioning** (no stub): apply the full "For built partners" note under 2.0.0 below — it is written as a complete catch-up — then proceed as above for anything newer.

---

## 2.1.0 — 2026-07-26

The Forge gains a second body: `CompanionForge_SelfUpdating.md`, a build that lives in a persistent Claude Project. Type `New Companion` and it fetches the canonical Forge from this repository, checks the version stamp against its embedded baseline, flags you if the canonical has moved — offering a summary of the changes from this changelog — and runs the interview from the newest version it has. Read-only against the repository; the person stays in the loop on every update. Contributed by Isaac (@oregonisaac), the first stone offered back, and integrated with the version system this repository now runs on.

**For built partners:** nothing to change — this release adds a new Forge edition and does not alter the operating layer.

## 2.0.0 — 2026-07-26

Versioning and the update path begin. Every public text file now carries a version stamp as a trailing HTML comment (visible in the raw text, invisible in the rendered view); this changelog exists; and the Forge now writes an update stub into every partner it builds, so a partner can renew itself when its person asks. The architecture image is versioned by this log rather than in-file.

**For built partners:** this note is a complete catch-up for any partner built before 2.0.0.

1. Add an update stub to your instructions, near the end:
   > *You were built by the Companion Forge, version 2.0.0, from github.com/exquest/CompanionForge. When the person asks you to update yourself, fetch `https://raw.githubusercontent.com/exquest/CompanionForge/main/CHANGELOG.md` and follow the procedure at its head. You cannot change your own instructions; you prepare the update, and the person applies it.*
2. If your operating principles do not already carry them, add these two, in your own prompt's voice:
   > *Act on the world only with the person's explicit go-ahead: draft, prepare, and propose freely, but never send, publish, schedule, or spend on their behalf until they have said yes to the specific thing.*
   > *If the person ever sounds in immediate danger, go past steadiness: urge them plainly toward help that can reach them now — someone they trust, local emergency services, a crisis line. A conversation must never stand in the place where real help belongs.*

## Earlier strata (before versioning)

**2026-07-26 — The Forge sharpened.** The distinction between drifting and danger entered both the Forge's own conduct and the operating layer it installs; the explicit go-ahead rule joined every built partner's principles; the read-back now carries every consequential calibration behaviorally — including how deep and how fast the partner will go — never diagnostically; the machine index now separates receiving the Forge file from being asked to run it, and declares its Claude assumptions; the setup steps learned to travel to other platforms.

**2026-07-23 — A door onto the making.** The decision journal — the record of the book's second-edition build — was published behind a restored seventh door, and every file in the repository gained an explicit license.

**2026-07-22 — The great re-sync.** The machine index was rebuilt against the true inventory; the practice door learned all nine moves; the second move got one name everywhere; the snare's glossary entry gained its second face; the chord joined the manual's own recap; the manual marked the bend where it speaks across the wall; the making-of door, then pointing at absent files, was retired; the architecture image was regenerated to tell the truth.

<!-- CompanionForge v2.1.0 -->
