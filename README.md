<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&section=header&color=0:5BCEFA,50:F5A9B8,100:ffffff&text=Suellen&fontSize=52&fontColor=2b2b2b&fontAlignY=36&desc=Python%20%C2%B7%20Open%20Source%20%C2%B7%20she%2Fher%20%F0%9F%8F%B3%EF%B8%8F%E2%80%8D%E2%9A%A7%EF%B8%8F&descAlignY=56&descSize=17" alt="banner" />

[![pronouns](https://img.shields.io/badge/pronouns-she%2Fher-F5A9B8?style=flat-square)](#)
[![NCUK → UNSW](https://img.shields.io/badge/NCUK_%E2%86%92_UNSW-Foundation_Year-5BCEFA?style=flat-square)](#)
[![bug hunter](https://img.shields.io/badge/bug_hunter-22_bugs_found%20%C2%B7%20first_PR_merged-DC2626?style=flat-square)](#)
[![open to internships](https://img.shields.io/badge/open_to-SWE_internships-181717?style=flat-square)](#)

</div>

## 🧑‍💻 `$ whoami`

```bash
$ whoami
Suellen — NCUK foundation student, heading to UNSW (Australia).
I read open-source code every day and file issues for the bugs I find.
```

- 🔭 I'm currently working on **[bug-hunting-kit](https://github.com/SuellenQwQ/bug-hunting-kit)** — a CLI toolkit and the bug patterns I've collected from 22 real hunts. My first security fix was just merged upstream
- 🌱 I'm currently learning **Python internals, testing patterns, and how large OSS projects are maintained**
- 💬 Ask me about **writing useful bug reports, the NoneBot/QQ-bot ecosystem, or Galgame**
- 📫 How to reach me: open an issue on one of my repos

## 🧰 Tech Stack

<table>
<tr>
<td valign="top" width="33%">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

</td>
<td valign="top" width="33%">

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub API](https://img.shields.io/badge/GitHub_REST_API-181717?style=flat-square&logo=github&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

</td>
<td valign="top" width="33%">

**Focus**

![Open Source](https://img.shields.io/badge/Open_Source-Contributing-3DA639?style=flat-square&logo=open-source-initiative&logoColor=white)
![Code Review](https://img.shields.io/badge/Code_Review-reading_prod_code-8B5CF6?style=flat-square)
![Debugging](https://img.shields.io/badge/Debugging-repro_first-DC2626?style=flat-square)

</td>
</tr>
</table>

## 📂 Projects

| | Repo | What it is |
|---|---|---|
| 🐛 | [bug-hunting-kit](https://github.com/SuellenQwQ/bug-hunting-kit) | A stdlib-only CLI issue filer + 11 bug patterns from real hunts |
| 🎲 | [galgame-picker](https://github.com/SuellenQwQ/galgame-picker) | Random galgame picker with tag filtering |
| 🌐 | [SuellenQwQ.github.io](https://suellenqwq.github.io) | My personal homepage |

## 🏆 Selected Bug Hunts

> Every issue below has a minimal repro or a line-level proof.
> Full list: 22 repos, 21 issues. My first PR — a path traversal fix with 16 tests — was merged upstream ([#45](https://github.com/Cvandia/nonebot-plugin-whateat-pic/pull/45)).

| | Project | What I found |
|---|---|---|
| 🔥 | [sealdice-core](https://github.com/sealdice/sealdice-core/issues/1864) | D&D hp silently clamped to **0** on any heal when `hpmax` unset — one branch in a function checked existence, its sibling forgot |
| 🔤 | [translate-toolkit](https://github.com/translate/translate/issues/6631) | `zh.puncdict` ate the newline after `?` — 3-line Chinese translations silently merged into 2 |
| 🌐 | [OlivOS](https://github.com/OlivOS-Team/OlivOS/issues/226) | `lstrip("http://")` strips a *character set*, not a prefix — proxy hostnames starting with h/t/p/s got eaten (`proxy.` → `roxy.`) |
| 🎲 | [maimaidx](https://github.com/Yuri-YuzuChaN/nonebot-plugin-maimaidx/issues/93) | DX star thresholds off-by-one at all 5 boundaries — exactly-at-threshold scores displayed one star less than the game |
| 📬 | [ELF_RSS](https://github.com/Quan666/ELF_RSS/issues/641) | When a push count is an exact multiple of the batch size, the flush step never runs — DB connections leak, cache grows forever |
| 🔇 | [nonebot_plugin_admin](https://github.com/yzyyz1387/nonebot_plugin_admin/issues/151) | Random ban duration `[0, 300]` can roll **0** — which the OneBot protocol defines as *unban* |

## 🗺️ Roadmap

| | Milestone |
|---|---|
| 📍 **Now** | NCUK Foundation · one open-source codebase read & one verified issue filed per day |
| 👉 **Next** | 🇦🇺 **UNSW** — Computer Science |
| 🎯 **Then** | SWE internship · keep upstreaming fixes (first one landed ✓) |

## 📊 Analytics

<div align="center">
<img height="150" src="https://github-readme-stats.vercel.app/api?username=SuellenQwQ&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="stats" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SuellenQwQ&layout=compact&theme=tokyonight&langs_count=8" alt="langs" />
</div>

<div align="center">
<img width="60%" src="https://streak-stats.demolab.com?user=SuellenQwQ&theme=tokyonight&date_format=%5BY.%5Dn.j" alt="streak" />
</div>

<div align="center">
<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=SuellenQwQ&theme=react-dark&hide_border=true&area=true" alt="activity" />
</div>

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:5BCEFA,50:F5A9B8,100:F5A9B8" alt="footer" />

</div>
