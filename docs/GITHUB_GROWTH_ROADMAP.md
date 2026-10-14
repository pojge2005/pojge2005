# GitHub Profile Growth Roadmap

**Owner:** [@pojge2005](https://github.com/pojge2005)  
**Started:** 2026-10-14  
**Purpose:** Improve profile quality, engineering credibility, project discoverability, and authentic open-source participation.

This roadmap tracks work that can be evidenced. GitHub awards platform achievements automatically; this document cannot grant badges or guarantee eligibility.

## Rules of execution

- Prefer useful engineering outcomes over contribution-count inflation.
- Work in focused branches; inspect changes before merging.
- Run available checks and record exact results. Never claim unrun tests passed.
- Keep private repositories and prototypes private.
- For `SmartKeychain-V2`, the local repository is the source of truth. Do not edit its files directly through GitHub, skip hooks, or force-push.
- Do not publish secrets, access tokens, private project details, or personal data.
- A pull request counts as completed only when its actual GitHub state confirms it was merged.

## Milestone 1 — Profile quality

- [x] Create the username-matching profile repository and README.
- [x] Add original anime-inspired animated SVG artwork.
- [x] Feature selected embedded, IoT, RFID, and computer-vision projects.
- [ ] Verify profile rendering on desktop and mobile.
- [ ] Check all project links, external badges, and image fallbacks.
- [ ] Review pinned repositories and select the strongest demonstrable projects.
- [ ] Add real project screenshots or diagrams where available.

**Completion evidence:** profile URL, link-check notes, and rendered-profile review.

## Milestone 2 — Repository demonstrators

- [x] Improve `ESP32-FreeRTOS-IoT` README and merge [PR #1](https://github.com/pojge2005/ESP32-FreeRTOS-IoT/pull/1).
- [x] Track MQTT task ownership and reliability work in [Issue #2](https://github.com/pojge2005/ESP32-FreeRTOS-IoT/issues/2).
- [ ] Establish a reproducible compile environment for the MQTT project.
- [ ] Refactor MQTT client access to one owning task and a bounded queue.
- [ ] Document queue overflow and reconnect behavior.
- [ ] Verify build results; run hardware checks only when actual hardware testing is performed.
- [ ] Improve one additional FreeRTOS repository with verified setup and expected output.
- [ ] Review OTA projects for authentication, rollback/recovery, and failure handling.
- [ ] Review RFID examples and clearly label demo credentials and security limitations.
- [ ] Improve the object-tracking repository's dependencies and run instructions.

**Completion evidence:** merged PRs, reproducible commands, CI results, and honest hardware test notes.

## Milestone 3 — Quality gates

- [ ] Add a useful GitHub Actions workflow to a repository with a reproducible build.
- [ ] Add formatting, linting, or tests only where appropriate to the actual stack.
- [ ] Fix actionable failures discovered by the checks.
- [ ] Document toolchain and dependency versions.
- [ ] Create a versioned release for a stable project after validation.

**Completion evidence:** workflow run links, test logs, and release notes.

## Milestone 4 — Authentic community contributions

- [x] Complete one merged documentation PR in a personal project.
- [ ] Complete a meaningful code or test PR in a personal project.
- [ ] Identify an external open-source issue that matches existing skills and project scope.
- [ ] Read the maintainer's contribution guide and reproduce the issue before proposing a fix.
- [ ] Submit a focused external PR with tests or evidence appropriate to the change.
- [ ] Participate constructively in relevant issue discussions or reviews.

**Completion evidence:** public issue/PR links and their real status. Do not count drafts or unmerged work as merged contributions.

## Milestone 5 — GitHub profile achievements

These are goals, not promises. GitHub determines eligibility and awards platform achievements.

- [ ] **Pull Shark:** earn through qualifying merged pull requests, according to current GitHub rules.
- [ ] **Galaxy Brain:** earn by having answers accepted in eligible GitHub Discussions.
- [ ] **Pair Extraordinaire:** earn through qualifying co-authored commits with another real contributor.
- [ ] **YOLO:** avoid treating this as a target; it rewards merging a pull request without review and conflicts with this project's review-first safety practice.
- [ ] Review the account's actual achievements page and record only badges GitHub has awarded.

Never manufacture co-authorship, ask for meaningless acceptance, or bypass review just to obtain a badge.

## Milestone 6 — Contribution graph verification

- [ ] Confirm commit author email is associated with the GitHub account.
- [ ] Check that qualifying commits land on a repository's default branch or another GitHub-eligible branch.
- [ ] Verify merged pull requests and profile contribution settings.
- [ ] Check the public contribution calendar directly.
- [ ] Keep a work log containing date, repository, task, branch, commit/PR, validation command, result, and limitations.

## Prioritized next actions

1. Verify the rendered profile and external image/badge links.
2. Establish the MQTT project's actual build environment.
3. Implement the MQTT single-owner task and bounded queue on a feature branch.
4. Review the diff and available checks, then open a PR for review.
5. Pick the next repository based on demonstrable value, not repository count.

## Progress log

| Date | Work | Evidence | Validation / limitations |
| --- | --- | --- | --- |
| 2026-10-14 | Improved `ESP32-FreeRTOS-IoT` documentation | [PR #1](https://github.com/pojge2005/ESP32-FreeRTOS-IoT/pull/1) | Documentation-only; firmware compile and hardware behavior not verified |
| 2026-10-14 | Opened MQTT ownership/reliability issue | [Issue #2](https://github.com/pojge2005/ESP32-FreeRTOS-IoT/issues/2) | Implementation remains pending |
