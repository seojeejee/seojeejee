# Repository workflow

- This is the public GitHub profile repository `seojeejee/seojeejee`.
- For GitHub updates from this workspace, use the local Git CLI with GitHub CLI authentication. Git and `gh` were installed and the `seojeejee` account authenticated over HTTPS in November 2026. Check `gh auth status` before writing; authentication may expire.
- The ChatGPT GitHub connector returned HTTP 403 for a file update while its installation list was empty. If that happens again, use the authenticated CLI rather than asking for a GitHub desktop app installation.
- Before pushing, inspect `git status` and the diff, stage only the intended files, then verify the remote result.

## Continuing the portfolio

- The user intends to grow this portfolio as new projects, research, papers, and presentations are completed. Treat this repository as the continuing portfolio home; preserve existing work when adding new material.
- Agreed positioning: industrial AI/ML, with battery time-series research and computer vision as the main areas. Robotics and embedded AI are supporting application areas until device measurements or integration experiments provide stronger evidence.
- Write primarily in Korean for Korean employers. Prioritize the problem, implementation or personal contribution, measured results, evidence links, and reproduction instructions. Do not invent dates, responsibilities, awards, publication status, experiments, or performance numbers.
- References consulted for structure: Kwon Siyeon's junior hiring experience (https://techblog.woowahan.com/11998/), Wonny's public resume guide (https://wonny.space/writing/work/engineer-resume), and Danmin's resume revisions (https://www.jeong-min.com/61-resume/). Do not claim that every reference is an award-winning portfolio or that it guarantees hiring success.
- Keep the profile concise with links to project details. Use consistent left-aligned images, a width of 640 where appropriate, preserved aspect ratios, and descriptive captions. FINETECH has four exhibition assets; retain all four in its detail page.
- For future additions, inspect source material and the latest remote state first. Add projects to their own repositories or detail pages as appropriate, then update the profile summary. Maintain clear distinctions among planned research, completed experiments, submitted papers, accepted papers, and published papers.
- Literature notes must distinguish actual documented reading from supplementary references selected while preparing the portfolio. Link to original papers and distinguish literature results from the user's results.
- For team projects, identify supported personal contributions and preserve upstream attribution and collaborator history.

## Current portfolio state

- Profile: `seojeejee/seojeejee`; detailed FINETECH page: `projects/finetech-2026.md`.
- Battery: `seojeejee/physics-guided-marine-battery-soc`. Reported marine-proxy MAE improves from 1.808 to 1.024 percentage points across five seeds. This is internal validation on public-data-informed proxy data, not measured-vessel external validation. Check the result JSON before changing metrics.
- Vision: `seojeejee/jetson-safety-zone-intrusion-detection`. Archived learning artifacts report mAP@0.5 0.795 and Person AP@0.5 0.614. Jetson FPS, latency, and power measurements are not yet documented. The inference code expects class 0=bus and class 1=person.
- Team service project: `seojeejee/MOVE-AI`, forked from `route-whisper/MOVE-AI`. GPS/GeoJSON, reporting, and administrator verification are prototype features; AI structuring and motion/ETA include deterministic demo logic.
- FINETECH: describe the overall topic as flexible sensor materials for humanoid robots. Finger-sensor gloves are the specific poster application. Preserve poster, booth, team, and material/model photos and their explanations. TFT fabrication and sensor-performance measurements remain follow-up work in the supplied mentoring record.
- Research directions under consideration, not completed results: battery prior-removal ablations and independent-data validation; small/occluded pedestrian detection evaluated together with Jetson latency.
- Profile README, the three project READMEs, repository descriptions, and topics were updated together. The unrelated private tutorial repository was not changed.
- GitHub `user` authorization was subsequently granted and BIO updated successfully to: `산업 AI/ML · 배터리 시계열 · 컴퓨터 비전 | 반복 실험과 코드로 연구 결과를 검증합니다.` Recheck authorization when needed; never store access tokens or device codes here.
