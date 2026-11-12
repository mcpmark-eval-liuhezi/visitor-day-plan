# Visitor Day Plan

## GitHub Actions log cleanup

**Finding: No workflow runs exist to delete.**

A review of all repositories under the HeziLiu GitHub account returned **zero workflows** defined in each:

- **Repository: Little-rookie** (https://github.com/HeziLiu/Little-rookie, Java, default branch: master) — `list_workflows` returned `total_count: 0`. No GitHub Actions workflows are configured, therefore no workflow runs exist and no logs could be deleted.
- **Repository: Big-Buzzard** (https://github.com/HeziLiu/Big-Buzzard, default branch: master) — `list_workflows` returned `total_count: 0`. No GitHub Actions workflows are configured, therefore no workflow runs exist and no logs could be deleted.
- **Repository: CodingInterviewChinese2** (fork, C++, default branch: master) — `list_workflows` returned `total_count: 0`.
- **Repository: awesome-chatgpt-prompts-zh** (fork, default branch: main) — `list_workflows` returned `total_count: 0`.

**Conclusion:** None of the repositories under the HeziLiu account have any GitHub Actions workflow runs at all. No log deletion was performed, and no run ID is applicable since there are no runs to target. If Actions logs accumulate in the future (e.g., after CI is added), the most recent finished run's logs can be removed via the repository's Actions tab -> run -> "Delete logs" button, or with the `gh run delete-log` CLI command.

---

## Itinerary

**Guest:** Professor visiting from Guizhou (single day, this week)
**Host institution:** Beijing University of Posts and Telecommunications (BUPT), Haidian, Beijing
**Travel origin:** BUPT main campus, 10 Xi Tu Cheng Lu, Beitaipingzhuang, Hai Dian Qu, Bei Jing Shi, China, 100088 (coordinates: 39.962796, 116.358103)

### Morning: Palace Museum (Forbidden City)

- **Venue name:** The Palace Museum (Forbidden City)
- **Street address:** 4 Jing Shan Qian Jie, Dong Cheng Qu, Bei Jing Shi, China, 100009 (coordinates: 39.9163447, 116.3971546)
- **Phone:** 400 950 1925
- **Website:** https://www.dpm.org.cn/Home.html
- **Current rating:** 4.6 (Google Maps)
- **Opening hours (as returned by lookup):**
  - Monday: Closed
  - Tuesday: 8:30 AM – 4:30 PM
  - Wednesday: 8:30 AM – 4:30 PM
  - Thursday: 8:30 AM – 4:30 PM
  - Friday: 8:30 AM – 4:30 PM
  - Saturday: 8:30 AM – 4:30 PM
  - Sunday: 8:30 AM – 4:30 PM
- **Travel from BUPT campus (driving):** 33 mins (value: 1953 seconds), distance 10.2 km (value: 10206 meters). Origin resolved to: 31-10 Xi Tu Cheng Lu, Hai Dian Qu, Bei Jing Shi, China, 100088.
- **Note from recent reviews:** The site is closed on Mondays; tickets should be booked a few days in advance as they sell out quickly due to the daily cap of 40,000 visitors; passport is strictly required for entry; allow several hours to walk through; comfortable shoes and water recommended.

### Lunch: Xinjiang Flavor Yidecun Stretched Noodle Restaurant (Wangfujing)

- **Venue name:** Xinjiang Flavor Yidecun Stretched Noodle Restaurant
- **Address:** 7 Wang Fu Jing Xi Jie, Wangfujing, Dong Cheng Qu, Bei Jing Shi, China, 100006 (coordinates: 39.914207, 116.408908)
- **Rating:** 4.9 (Google Maps) — the highest-rated option returned for the Wangfujing area
- **Walking time from the Palace Museum:** 23 mins (value: 1375 seconds), distance 1.4 km (value: 1449 meters)
- **Extra context from lookup:** Halal restaurant near the Forbidden City and Wangfujing street; generous portions of Lanzhou beef noodles (lamian); reasonable prices (dinner for 2 estimated around RMB 105); complimentary red date and longan tea; staff praised for friendliness.

### Afternoon: Summer Palace

- **Venue name:** Summer Palace
- **Address:** Haidian District, China, 100091 (coordinates: 39.9999823, 116.2754606)
- **Phone:** 010 6288 1144
- **Website:** https://www.summerpalace.net.cn/
- **Rating:** 4.6 (Google Maps)
- **Opening hours (as returned by lookup):**
  - Monday: 6:30 AM – 7:00 PM
  - Tuesday: 6:30 AM – 7:00 PM
  - Wednesday: 6:30 AM – 7:00 PM
  - Thursday: 6:30 AM – 7:00 PM
  - Friday: 6:00 AM – 8:00 PM
  - Saturday: 6:00 AM – 8:00 PM
  - Sunday: 6:30 AM – 7:00 PM
- **Travel time from the Palace Museum area (driving):** 35 mins (value: 2113 seconds), distance 21.2 km (value: 21213 meters). Note: transit routing via the Distance Matrix and Directions APIs returned ZERO_RESULTS for this route; the driving estimate above is the reliable figure.
- **Additional context from lookup:** UNESCO World Heritage imperial garden; arrive early to beat crowds; Subway Line 4 to Beigongmen (North Gate), exit D; tickets approximately 30 CNY in peak season (Apr–Oct); highlights include Kunming Lake, the 728-meter Long Corridor, and the Tower of Buddhist Incense on Longevity Hill.

### Evening: Transfer to Beijing Capital International Airport (PEK)

- **Travel from Summer Palace to Beijing Capital International Airport (PEK), Shunyi, Beijing, China (driving):** 35 mins (value: 2095 seconds), distance 34.4 km (value: 34442 meters).
- **Recommendation:** Allow extra buffer time in the evening for traffic; advise the guest to book a taxi or use subway Line 15/ABQ transfer options, and aim to arrive at the airport at least 2–3 hours before the flight departure time.

### Summary Timeline

| Time | Activity | Location | Travel |
|------|----------|----------|--------|
| Morning | arrival at BUPT + transfer to Palace Museum | Haidian -> Dongcheng | Driving: 33 mins, 10.2 km |
| Late morning | Palace Museum (Forbidden City) visit | 4 Jingshan Front St, Dongcheng | 4.6 rating, 8:30 AM–4:30 PM (Tue–Sun), closed Mondays |
| Midday | Lunch at Xinjiang Flavor Yidecun Stretched Noodle Restaurant | 7 Wangfujing West Street | Walking: 23 mins, 1.4 km; rating 4.9 |
| Afternoon | Summer Palace visit | Haidian District, 100091 | Driving: 35 mins, 21.2 km; 4.6 rating |
| Evening | Transfer to Beijing Capital International Airport (PEK) | Haidian -> Shunyi | Driving: 35 mins, 34.4 km |

---

*All addresses, hours, ratings, and travel times above are reported exactly as returned by the Google Maps lookups. No values have been rounded or estimated beyond what the APIs provided.*

## Gist note

This file was intended to be published as a GitHub gist under the HeziLiu account, but the personal access token in use does not have gist-creation scope (API returned `403 Resource not accessible by personal access token`). The complete plan is instead stored at: https://github.com/mcpmark-eval-liuhezi/visitor-day-plan/blob/main/visitor-day-plan.md
