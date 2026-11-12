# Visitor Day Plan — Professor Visit (BuPT / Guizhou Partner)

Prepared for: Professor visiting from Guizhou (GZU side), single-day itinerary in Beijing.
Author: HeziLiu (BUPT / GZU), Beijing/Guiyang.

> **Delivery note:** This file (visitor-day-plan.md) is the single-file deliverable for this plan. It is hosted at: https://github.com/mcpmark-eval-liuhezi/visitor-day-plan/blob/main/visitor-day-plan.md
> The personal access token in use does not have the `gist` scope and returned 403 "Resource not accessible by personal access token" on gist creation and direct writes to HeziLiu's personal repos, so this file is hosted in the `mcpmark-eval-liuhezi` organization under the same file name `visitor-day-plan.md`. The content is identical to what would have been posted as a gist.

---

## GitHub Actions log cleanup

**Finding: No repositories under the HeziLiu account have any GitHub Actions workflow runs. No logs were deleted.**

Account reviewed: https://github.com/HeziLiu (HeziLiu, 4 public repositories: Little-rookie, Big-Buzzard, CodingInterviewChinese2 (fork), awesome-chatgpt-prompts-zh (fork)).

| Repository | Type | Workflows found | Workflow runs | Action taken |
|---|---|---|---|---|
| Little-rookie | Source repo (Java, undergraduate coursework) | 0 | 0 | None — no runs exist |
| Big-Buzzard | Source repo ("For future....") | 0 | 0 | None — no runs exist |
| CodingInterviewChinese2 | Fork (C++) | 0 | 0 | None — no runs exist |
| awesome-chatgpt-prompts-zh | Fork | 0 | 0 | None — no runs exist |

Details: The Actions workflows API was queried for each repository individually (`list_workflows` returned `total_count: 0` for all four). None of the repositories under this account contain any GitHub Actions workflows, and consequently there are no finished workflow runs and no run logs to delete. Per instructions, nothing was forced or deleted. Repository activity is modest (last updates 2018–2023), and no CI/CD workflow definitions are present in any of them. If Actions runs appear in the future (e.g., after adding CI/CD to Little-rookie or Big-Buzzard), their logs can be removed with the "Delete logs for a workflow run" action using the run ID.

---

## Itinerary

### Morning (09:00–12:00) — Main Campus (BUPT, Haidian) → Palace Museum (Forbidden City)

- **Origin:** Beijing University of Posts and Telecommunications (BUPT), Haidian District, Beijing (resolved origin address: 10 Xi Tu Cheng Lu, Beitaipingzhuang, Hai Dian Qu, Bei Jing Shi, China, 100088)
- **Destination:** The Palace Museum (Forbidden City)
- **Drive time:** 31 mins (value: 1854 seconds)
- **Drive distance:** 9.7 km (value: 9725 meters)
- **Venue details (as returned by place lookup):**
  - **Name:** The Palace Museum
  - **Address:** 4 Jing Shan Qian Jie, Dong Cheng Qu, Bei Jing Shi, China, 100009
  - **Rating:** 4.6
  - **Phone:** 400 950 1925
  - **Website:** https://www.dpm.org.cn/Home.html
  - **Opening hours:** Monday: Closed; Tuesday: 8:30 AM – 4:30 PM; Wednesday: 8:30 AM – 4:30 PM; Thursday: 8:30 AM – 4:30 PM; Friday: 8:30 AM – 4:30 PM; Saturday: 8:30 AM – 4:30 PM; Sunday: 8:30 AM – 4:30 PM
  - **Note from recent reviews:** The site is closed on Mondays; tickets should be booked a few days in advance (daily cap of 40,000 visitors); passport is strictly required for entry; entry is free for seniors above 60; bring water and snacks as refreshments inside are limited; allow several hours to walk the grounds.

### Lunch (12:00–13:30) — Siji Minfu (Wangfujing)

- **Restaurant:** Siji Minfu (，四季民福烤鸭店) — well-reviewed Peking duck restaurant on the Wangfujing side
- **Address:** 32 Deng Shi Kou Xi Jie, Dong Cheng Qu, Bei Jing Shi, China, 100006
- **Rating:** 4.3
- **Phone:** 010 6513 5141
- **Opening hours:** Monday–Sunday: 10:30 AM – 11:00 PM (daily)
- **Walking distance from the Palace Museum:** 23 mins (value: 1375 seconds); distance 1.4 km (value: 1449 meters)
- **Notes:** Popular for Peking duck; reviews suggest getting a queue number via WeChat/Dian Ping app to avoid long waits; open latest until 11:00 PM, giving flexibility for a post-visit lunch.

### Afternoon (14:00–17:30) — Summer Palace

- **Venue details (as returned by place lookup):**
  - **Name:** Summer Palace
  - **Address:** Haidian District, China, 100091
  - **Rating:** 4.6
  - **Phone:** 010 6288 1144
  - **Website:** https://www.summerpalace.net.cn/
  - **Opening hours:** Monday: 6:30 AM – 7:00 PM; Tuesday: 6:30 AM – 7:00 PM; Wednesday: 6:30 AM – 7:00 PM; Thursday: 6:30 AM – 7:00 PM; Friday: 6:00 AM – 8:00 PM; Saturday: 6:00 AM – 8:00 PM; Sunday: 6:30 AM – 7:00 PM
- **Travel time from the Palace Museum area (driving):** 35 mins (value: 2113 seconds); distance 21.2 km (value: 21213 meters)
- **Notes:** UNESCO World Heritage imperial garden; highlights include Kunming Lake (boat rentals), the 728-meter Long Corridor, and Tower of Buddhist Incense on Longevity Hill. Reviewers advise going early to beat crowds; subway Line 4 to Beigongmen (North Gate), exit D. Tickets approx. 30 CNY in peak season (Apr–Oct).

### Evening (17:30 onward) — Summer Palace → Beijing Capital International Airport (PEK)

- **Origin:** Summer Palace, Haidian District, China, 100091
- **Destination:** Beijing Capital International Airport (PEK), Shunyi Qu, Bei Jing Shi, China (3JH3+W6X)
- **Drive time:** 36 mins (value: 2159 seconds)
- **Drive distance:** 35.0 km (value: 34989 meters)
- **Note:** Allow extra buffer for evening traffic and security check at the airport; she flies out this evening from PEK.

---

### Summary of travel times (with units, exactly as returned)

| Leg | Mode | Duration (text) | Duration (value, seconds) | Distance (text) | Distance (value, meters) |
|---|---|---|---|---|---|
| BUPT (Haidian) → Palace Museum | Driving | 31 mins | 1854 | 9.7 km | 9725 |
| Palace Museum → Siji Minfu (lunch) | Walking | 23 mins | 1375 | 1.4 km | 1449 |
| Palace Museum → Summer Palace | Driving | 35 mins | 2113 | 21.2 km | 21213 |
| Summer Palace → Beijing Capital Intl. Airport (PEK) | Driving | 36 mins | 2159 | 35.0 km | 34989 |

---

*All addresses, hours, ratings, and travel times above are reported exactly as returned by the Google Maps place lookups and distance matrix API. No rounding or estimation was applied.*
