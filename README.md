# Trapped-ion systems · ARTIQ · quantum control · AI tooling

I build engineering workflows that keep physics intent, hardware behavior, and verification evidence aligned.

My work spans deterministic experiment control, calibration and benchmarking pipelines, hardware-aware validation, and AI-assisted tools. I keep automated tests, deployed behavior, electrical emulation, and physical-hardware evidence as separate claims.

## Selected work

| Work | Problem | My role | Result | Verification |
|---|---|---|---|---|
| [Trapped-ion control systems case study](https://github.com/Yueh-H/trapped-ion-systems-case-study) | Connect pulse intent, controller execution, readout, and calibration without exposing lab-specific settings. | Designed the orchestration contracts, primitive compilation path, deterministic simulation, TTL/photon emulation, and evidence-gated calibration boundaries. | Published a sanitized system map that separates implemented mechanisms from integration targets. | Software simulation and electrical emulation are labeled separately. This public artifact does **not** claim physical-ion operation or gate fidelity. |
| [Industrial worker training app](https://github.com/Yueh-H/NTU-hackathon-team12-industrial-worker-training) | Help multilingual operators learn machine parts while supervisors see progress and weak spots. | As part of NTU Hackathon Team 12, contributed the learning assistant, reminder state, build/deployment fixes, and privacy-safe public demo. | Shipped mobile employee/admin flows in Chinese and Indonesian. [Live demo](https://yueh-h.github.io/NTU-hackathon-team12-industrial-worker-training/). | Automated tests are included; the latest GitHub Pages workflow succeeded and the deployed demo is publicly reachable. |
| [Engineer Blackboard site](https://github.com/Yueh-H/engineers-blackboard-site) | Turn a learning-method concept into a maintainable public product. | Built the TypeScript/React site, static Pages export, rendered-output tests, and release workflow. | Shipped a versioned public site with repeatable local and Pages builds. [Live site](https://yueh-h.github.io/engineers-blackboard-site/). | The latest deployment workflow succeeded and the live site is publicly reachable. |
| [macOS Control-modifier fix](https://github.com/rullerzhou-afk/clawd-on-desk/pull/946) | Physical Control shortcuts were conflated with Command on macOS. | Diagnosed the event/parser boundary, implemented the fix, and extended shortcut tests. | Submitted a focused two-file upstream pull request while preserving Windows/Linux behavior. | The PR reports 8,672 automated tests passed and 30 skipped; manual Electron Settings UI smoke testing was not performed. The PR is still open. |

## Evidence labels

- **Automated** — unit, integration, or deterministic simulation evidence.
- **Deployed** — a public artifact was built, published, and read back.
- **Electrical** — controller timing or I/O was exercised without claiming ion behavior.
- **Physical hardware** — stated only when the relevant instrument or ion-system run was actually performed.

## Portfolio and research

- [Trapped-ion systems engineering portfolio](https://yueh-h.github.io/trapped-ion-systems-engineering/)
- [Google Scholar](https://scholar.google.com/citations?user=HxzfXY4AAAAJ&hl=en)

