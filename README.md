<p align="center">
  <img src="https://raw.githubusercontent.com/sheazywi/Sheazywi/main/assets/aurora-veil.svg" alt="Pier-Olivier Boulianne — engines and developer tooling" width="100%" />
</p>


### currently

The C++20 Vulkan engine at [Starbounded](https://github.com/starbounded-dev), two people, one engine: hlb on occlusion, me on everything else. The `dev` branch moves daily, sample games and the project format get versioned on it, and a full miniaudio layer sits under the editor. Apache-2.0, [Lux](https://starbounded.com/lux) is the homepage.

### writing

Notes and posts at [starbounded.com](https://starbounded.com), [getting-started docs](https://www.starbounded.com/docs/getting-started.html) are live.

    </td>
    <td valign="top" align="right" width="36%">
      <em>"a thick bed really does mean a lot happened"</em><br>
      <sub>— the core sample</sub><br><br>
      <a href="https://starbounded.com">starbounded.com</a><br>
      <a href="https://twitter.com/sheazywi">@sheazywi</a>
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://raw.githubusercontent.com/sheazywi/Sheazywi/main/assets/strata-core.svg" alt="Pier-Olivier Boulianne — six years of commits as a drilled core sample, 1,258 commits counted on the nine repos I own plus LuxEngine on its dev branch" width="100%" />
</p>

### the log

Commit counts below are commits authored by me across the nine repos I own plus LuxEngine on its `dev` branch: 2021 zero, 2022 zero, 2023 one, 2024 108, 2025 239, 2026 910, so 1,258 in total.

2023: opened [Starbounded](https://github.com/starbounded-dev), started building in the open. One commit that year.

2024: the work went public, [starbounded.github.io](https://starbounded.github.io) plus the [test-dev](https://github.com/starbounded-dev/test-dev) and [archive](https://github.com/starbounded-dev/archive) playgrounds, and [sheazywi.github.io](https://sheazywi.github.io). 108 commits.

2025: one repo, [q511](https://github.com/sheazywi/q511), a Vite + React + Tailwind app that watches Québec 511's live road cameras from home over HLS streams. 239 commits.

2026: three runner tools in one day: [actions-runner-console](https://github.com/sheazywi/actions-runner-console) for self-hosted runner fleets, [pi-watchdog](https://github.com/sheazywi/pi-watchdog) keeping a physical eye on the CI VMs they run, and a GTA crew emblem tracer. LuxEngine got the hlb HZB occlusion fix, the tile-grid render-graph viewport, two sample games, and versioned the project format. 910 commits.

### deepest layers

- **LuxEngine** — C++20 Vulkan engine. Two people, one engine: hlb on occlusion, me on the rest. Apache-2.0.
- **actions-runner-console** — dashboard for self-hosted GitHub Actions runners, so a runner fleet runs like the CI I'm replacing.

— [starbounded.com](https://starbounded.com) · [@sheazywi](https://twitter.com/sheazywi)

<p align="center">
  <img src="https://raw.githubusercontent.com/sheazywi/Sheazywi/main/assets/oss-maintainer.svg" alt="Pier-Olivier Boulianne — three projects maintained: LuxEngine, actions-runner-console, pi-watchdog" width="100%" />
</p>

### how to contribute

Come from a repro: platform, expected vs actual, the log output, and a fix if you have one. Repro-first matters because Vulkan validation layers and driver behaviour sit at the bottom of the stack. Branches follow `feature/<thing>` and merge into `dev`; I review on the machine, five to ten minutes per commit, so push small and land the diff clean.

Start with a [good first issue](https://github.com/starbounded-dev/LuxEngine/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) — the label is live, nothing is tagged on it yet. Read [CODE_OF_CONDUCT.md](https://github.com/starbounded-dev/LuxEngine/blob/dev/CODE_OF_CONDUCT.md) first, it is short; CONTRIBUTING.md isn't in the repo yet.

### what I maintain

- **LuxEngine** — the C++20 Vulkan engine, Apache-2.0, 1 star and 90 open issues, latest release `2025.1`. Development lands on the `dev` branch.
- **actions-runner-console** — the runner dashboard, MIT, 2 stars, issues all closed.
- **pi-watchdog** — the Raspberry Pi keeping an eye on the CI VMs, no license file yet, 1 star.

— [starbounded.com](https://starbounded.com) · [@sheazywi](https://twitter.com/sheazywi)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sheazywi/sheazywi/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sheazywi/sheazywi/output/snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/sheazywi/sheazywi/output/snake.svg" width="100%" />
</picture>

### Pier-Olivier Boulianne

> *ship at the speed the graph can see, one real commit at a time*
> *every streak on the snake above is a day I actually worked*

The snake above is built fresh every day — it's eating real commits, not props.

— [starbounded.com](https://starbounded.com) · [@sheazywi](https://twitter.com/sheazywi)
