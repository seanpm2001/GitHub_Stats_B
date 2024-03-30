
***

<details open><summary><p><b>Click/tap here to expand/collapse this entire document</b></p></summary>

[![GitHub Metrics (Lowlighter) daily run for @seanpm2001](https://github.com/seanpm2001/GitHub_Stats_B/actions/workflows/github-stats-b.yml/badge.svg?branch=GitHub_Stats_B_Main-dev)](https://github.com/seanpm2001/GitHub_Stats_B/actions/workflows/github-stats-b.yml)

# [🅱️ GitHub Stats B](#-GitHub-Stats-B)

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

`:octocat: 📊️📈️🗃️ My tertiary GitHub statistics repository, with daily stats generation generated from the @lowlighter source repository.`

</details>

***

## [⬆️ Upstream repository](#-Upstream-repository)

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

The repository that this repository relies on is located here: [:octocat: `lowlighter/metrics`](https://github.com/lowlighter/metrics/)

</details>

***

## [🅰️ GitHub Stats A](#-GitHub-Stats-A)

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

This project is not meant to replace [:octocat: `GitHub_Stats_A`](https://github.com/seanpm2001/GitHub_Stats_A/) it is meant to supplement it. This project has been in planning for a few days, and was previously under consideration for a few months. I am still not entirely sure if it is going to work as intended. GitHub Stats A isn't going anywhere anytime soon regardless.

</details>

***

## [🪵️ Logs](#-Logs)

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

Daily logs for this project are stored [`here`](/Logs/)

Log file tree

- [2024](/Logs/2024/)
- - [03_March](/Logs/2024/03_March/)

This workflow produces logs that are larger than any other GitHub logs I have created so far. The logs for the 14th run when uncompressed were nearly 6 megabytes in size.

</details>

***

## [⚠️ Problems](#-Problems)

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

During the first night, I consistently had problems getting the workflow configured properly. Close to midnight, I got it to run, but as of 5:26 pm PST the next day, I am consistently running into an error regarding an access token. I have tried creating classic and fine grained access tokens with 2 different names for each type (`METRICS_TOKEN` and `metrics`) and copied the key to the secrets tab (which is named `METRICS_TOKEN`) each time. Yet I am consistently met with the same error:

```
You must provide a valid GitHub personal token to gather your metrics (see https://github.com/lowlighter/metrics/blob/master/.github/readme/partials/documentation/setup/action.md for more informations)
```

I have made 7 variants of the action as well, every version so far has not gotten to or past this point.

Update 2024.03.27: I have gotten it to work, the action had some errors that needed to be fixed. I am now trying to see what will and won't run. I will have to see tomorrow.

Update 2024.03.27: The main error I now receive is `Resource not accessible by integration` each job failed after 10-14 minutes.

Update 2024.03.28: This process may need to be tweaked for weeks or months until I get it right

Next planned change:

Split up into multiple workflows

- GitHub skyline (5)
- Name: github-stats-b_gh-skyline.yml

- [ ] 🌆️ @seanpm2001 GitHub Skyline (2020)
- [ ] 🌆️ @seanpm2001 GitHub Skyline (2021)
- [ ] 🌆️ @seanpm2001 GitHub Skyline (2022)
- [ ] 🌆️ @seanpm2001 GitHub Skyline (2023)
- [ ] 🌆️ @seanpm2001 GitHub Skyline (2024)

- GitHub city (5)
- Name: github-stats-b_gh-city.yml

- [ ] 🏙️ @seanpm2001 GitHub City (2020)
- [ ] 🏙️ @seanpm2001 GitHub City (2021)
- [ ] 🏙️ @seanpm2001 GitHub City (2022)
- [ ] 🏙️ @seanpm2001 GitHub City (2023)
- [ ] 🏙️ @seanpm2001 GitHub City (2024)

- GitHub calendar (4)
- Name: github-stats-b_gh-calendar.yml

- [ ] 📅️ @seanpm2001 GitHub Half-year isometric calendar 🔳️
- [ ] 📅️ @seanpm2001 GitHub Full-year isometric calendar 🔳️
- [ ] 🗓️ @seanpm2001 GitHub heatmap Current year calendar
- [ ] 🗓️ @seanpm2001 GitHub heatmap Full history calendar

- GitHub stars (4)
- Name: github-stats-b_gh-stars.yml

- [ ] 🏷️ @seanpm2001 GitHub starred Labels ⭐️
- [ ] 🐍️ @seanpm2001 GitHub starred topics Icons ⭐️
- [ ] 📈️ @seanpm2001 GitHub Stargazer graph ⭐️
- [ ] 📊️ @seanpm2001 GitHub Stargazers chart ⭐️

- GitHub legal and financial (3)
- Name: github-stats-b_gh-legal-and-financial.yml

- [ ] 💝 @seanpm2001 GitHub Sponsorships
- [ ] 💳️ @seanpm2001 GitHub Licenses and permissions
- [ ] 📈️ @seanpm2001 GitHub Licenses with open-source ratio graphs 💳️

- GitHub profile (4)
- Name: github-stats-b_gh-profile.yml

- [ ] 🚦️ @Seanpm2001 GitHub Repositories traffic
- [ ] ⚙️ @seanpm2001 GitHub General
- [ ] 💬️ @seanpm2001 GitHub Discussions 🗨️
- [ ] 💫️ @seanpm2001 GitHub Achievements

</details>

***

## [📋️ TODO](#-TODO)

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

- [ ] Get the workflow functional
- [ ] Split into 6 workflows
- [ ] Add time zone parameter
- [ ] Add documentation from the upstream repository
- [ ] Integrate into [`seanpm2001/seanpm2001`](https://github.com/seanpm2001/seanpm2001/)

</details>

***

## [🪜️ Workflow order](#-Workflow-order)

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

Version 2, changes may need to be made (entries re-arranged, added, or possibly removed)

Version 2 hopes to put less demanding tasks first, and more demanding tasks later.

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

```
# 🌆️ @seanpm2001 GitHub Skyline (2020)
# 🌆️ @seanpm2001 GitHub Skyline (2021)
# 🌆️ @seanpm2001 GitHub Skyline (2022)
# 🌆️ @seanpm2001 GitHub Skyline (2023)
# 🌆️ @seanpm2001 GitHub Skyline (2024)
# 🏙️ @seanpm2001 GitHub City (2020)
# 🏙️ @seanpm2001 GitHub City (2021)
# 🏙️ @seanpm2001 GitHub City (2022)
# 🏙️ @seanpm2001 GitHub City (2023)
# 🏙️ @seanpm2001 GitHub City (2024)
# 💬️ @seanpm2001 GitHub Discussions 🗨️
# 📅️ @seanpm2001 GitHub Half-year isometric calendar 🔳️
# 📅️ @seanpm2001 GitHub Full-year isometric calendar 🔳️
# 🏷️ @seanpm2001 GitHub starred Labels ⭐️
# 🐍️ @seanpm2001 GitHub starred topics Icons ⭐️
# 💝 @seanpm2001 GitHub Sponsorships
# 🗓️ @seanpm2001 GitHub heatmap Current year calendar
# 🗓️ @seanpm2001 GitHub heatmap Full history calendar
# 💫️ @seanpm2001 GitHub Achievements
# 📈️ @seanpm2001 GitHub Stargazer graph ⭐️
# 📊️ @seanpm2001 GitHub Stargazers chart ⭐️
# 💳️ @seanpm2001 GitHub Licenses and permissions
# 📈️ @seanpm2001 GitHub Licenses with open-source ratio graphs 💳️
# 🚦️ @Seanpm2001 GitHub Repositories traffic
# ⚙️ @seanpm2001 GitHub General
```

<img src="/Graphics/GitHub/Workflow/V3/GitHub_Stats_B_Workflow_V3.png" alt="Workflow V3" title="GitHub workflow (V3)" width="576" height="381">

</details>

Version 1, changes may need to be made (entries re-arranged, added, or possibly removed)

<details open><summary><p><b>Click/tap here to expand/collapse this section</b></p></summary>

```
⚙️ @seanpm2001 GitHub General
💫️ @seanpm2001 GitHub Achievements
📈️ @seanpm2001 GitHub Stargazer graph ⭐️
📊️ @seanpm2001 GitHub Stargazers chart ⭐️
💳️ @seanpm2001 GitHub Licenses and permissions
📈️ @seanpm2001 GitHub Licenses with open-source ratio graphs 💳️
💝 @seanpm2001 GitHub Sponsorships
🗓️ @seanpm2001 GitHub heatmap Current year calendar
🗓️ @seanpm2001 GitHub heatmap Full history calendar
🚦️ @Seanpm2001 GitHub Repositories traffic
🌆️ @seanpm2001 GitHub Skyline (2020)
🌆️ @seanpm2001 GitHub Skyline (2021)
🌆️ @seanpm2001 GitHub Skyline (2022)
🌆️ @seanpm2001 GitHub Skyline (2023)
🌆️ @seanpm2001 GitHub Skyline (2024)
🏙️ @seanpm2001 GitHub City (2020)
🏙️ @seanpm2001 GitHub City (2021)
🏙️ @seanpm2001 GitHub City (2022)
🏙️ @seanpm2001 GitHub City (2023)
🏙️ @seanpm2001 GitHub City (2024)
🏷️ @seanpm2001 GitHub starred Labels ⭐️
🐍️ @seanpm2001 GitHub starred topics Icons ⭐️
📅️ @seanpm2001 GitHub Half-year isometric calendar 🔳️
📅️ @seanpm2001 GitHub Full-year isometric calendar 🔳️
💬️ @seanpm2001 GitHub Discussions 🗨️
```

<img src="/Graphics/GitHub/Workflow/V1/GitHub_Stats_B_Workflow_V1.png" alt="Workflow V1" title="GitHub workflow (V1)" width="576" height="651"> <img src="/Graphics/GitHub/Workflow/V2/GitHub_Stats_B_Workflow_V2.png" alt="Workflow V2" title="GitHub workflow (V2)" width="576" height="381">

</details>

</details>

***

# [📜 File info](#-File-info)

<details open><summary><p lang="en"><b>Click/tap here to expand/collapse this section</b></p></summary>

- **File type:** `Markdown (*.md *.mkd *.mdown *.markdown)`
- **File version:** `4 (2024, Thursday, March 28th at 04:40 pm PST)` <!-- TODO: This line should be updated daily !-->
- **Line count (including blank lines and compiler line):** `405` <!-- This line doesn't need to be updated daily !-->
- **Word count:** `02,053` <!-- TODO: This line should be updated daily !-->
- **Character count (including spaces):** `14,337` <!-- TODO: This line should be updated daily !-->
- **Character count (excluding spaces):** `12,103` <!-- TODO: This line should be updated daily !-->
- **Size (in bytes):** `14,876` <!-- TODO: This line should be updated daily !-->
- **Current article language:** `English (EN_USA)` / `Markdown (CommonMark)` / `HTML5 (HyperText Markup Language 5.3)`
- **Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`
- **All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

> **Note** _On 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

> **Note** **You may need special rendering support for the `<details>` HTML tag being used in this document**


</details>

***

# [⌛️ File history](#-File-history)

<details><summary><p><b>Click/tap here to expand/collapse the file history section</b></p></summary>

---

## Version 1 (2024, Tuesday, March 26th at 11:04 pm PST)

<details><summary><p><b>Click/tap here to expand/collapse the file history entry for version 1</b></p></summary>

> Changes:

- [x] Started the file
- [x] Added the title section
- [x] Added the `Upstream repository` section
- [x] Added the `GitHub Stats A` section
- [x] Added the `Workflow order` section
- [x] Added the `File info` section
- [ ] No other changes in version 1

</details> <!-- End of V1 !-->

---

## Version 2 (2024, Wednesday, March 27th at 05:26 pm PST)

<details><summary><p><b>Click/tap here to expand/collapse the file history entry for version 2</b></p></summary>

> Changes:

- [x] Added a workflow run badge
- [x] Added the `Problems` section
- [x] Added the `TODO` section
- [x] Updated the `File info` section
- [x] Added the `File history` section
- - [x] Added an entry for version 1 and version 2
- [x] Added the `Footer` section
- [ ] No other changes in version 2

</details> <!-- End of V2 !-->

---

## Version 3 (2024, Wednesday, March 27th at 06:14 pm PST)

<details><summary><p><b>Click/tap here to expand/collapse the file history entry for version 3</b></p></summary>

> Changes:

- [x] Updated the title section
- - [x] Added dropdown support
- [x] Updated the `Upstream repository` section
- - [x] Added dropdown support
- [x] Updated the `GitHub Stats A` section
- - [x] Added dropdown support
- [x] Updated the `Problems` section
- - [x] Added new information
- - [x] Added dropdown support
- [x] Updated the `TODO` section
- - [x] Added dropdown support
- [x] Updated the `Workflow order` section
- - [x] Added version 2 of the workflow order
- - [x] Added dropdown support
- [x] Updated the `File info` section
- - [x] Added dropdown support
- [x] Updated the `File history` section
- - [x] Added an entry for version 3
- - [x] Added dropdown support
- [x] Updated the `Footer` section
- - [x] Added dropdown support
- [x] Made the entire file collapse-able
- [ ] No other changes in version 3

</details> <!-- End of V3 !-->

---

## Version 4 (2024, Thursday, March 28th at 04:40 pm PST)

<details><summary><p><b>Click/tap here to expand/collapse the file history entry for version 4</b></p></summary>

> Changes:

- [x] Updated the title section
- - [x] Added emoji and anchor link to heading
- [x] Updated the `Upstream repository` section
- - [x] Added emoji and anchor link to heading
- [x] Updated the `GitHub Stats A` section
- - [x] Added emoji and anchor link to heading
- [x] Updated the `TODO` section
- - [x] Added 3 new goals
- - [x] Added emoji and anchor link to heading
- [x] Added the `Logs` section
- - [x] Added the log file tree
- - [x] Added emoji and anchor link to heading
- [x] Updated the `Problems` section
- - [x] Added recent updates
- - [x] Added emoji and anchor link to heading
- [x] Updated the `Workflow order` section
- - [x] Added images for V1, V2, and V3 workflows
- - [x] Added emoji and anchor link to heading
- [x] Updated the `File info` section
- - [x] Added the file type field
- - [x] Updated the file version field
- - [x] Added the line count field
- - [x] Added the word count field
- - [x] Added the character count (without spaces) field
- - [x] Added the character count (with spaces) field
- - [x] Added the file size field
- - [x] Added the file language field
- - [x] Added the encoding field
- - [x] Added the daylight savings time field
- - [x] Added emoji and anchor link to heading
- [x] Updated the `File history` section
- - [x] Added an entry for version 4
- - [x] Added emoji and anchor link to heading
- [x] Updated the `Footer` section
- - [x] Added emoji and anchor link to heading
- [ ] No other changes in version 4


</details> <!-- End of V4 !-->

---

_End of file history._

</details> <!-- End of file history !-->

***

# [🦶️ Footer](#-Footer)

<details open><summary><p lang="en"><b>Click/tap here to expand/collapse the footer</b></p></summary>

**You have reached the end of this file.**

- [`Back to top`](#Top)
- [:octocat: `Exit to GitHub`](https://github.com/)
- [:octocat: `Exit to Bing`](https://bing.com/)
- [:octocat: `Exit to DuckDuckGo`](https://duckduckgo.com/)
- [:octocat: `Exit to Ecosia`](https://ecosia.org/)
- [:octocat: `Exit to Swisscows`](https://swisscows.com/)

###### [🔚️ EOF](#-EOF)

<!-- EOF:
End
Of
File
!-->

</details> <!-- End of footer !-->

***