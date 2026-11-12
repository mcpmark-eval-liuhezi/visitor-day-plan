# Visitor Day Plan — Professor Visit (BuPT → Forbidden City → Summer Palace → PEK)

Prepared for the visiting professor (Guizhou side, single-day visit). All venue facts, addresses, hours, ratings, and travel times below are reported exactly as returned by the Google Maps lookups. No rounding or guessing.

---

## GitHub Actions log cleanup

**Finding: No workflow runs exist to clean up.**

The GitHub account `HeziLiu` has 2 repositories:

| Repository | Workflow runs |
|---|---|
| HeziLiu/Little-rookie | 0 workflows (list_workflows returned total_count: 0) |
| HeziLiu/Big-Buzzard | 0 workflows (list_workflows returned total_count: 0) |

Both repositories were checked via the GitHub Actions workflows API (`GET /repos/{owner}/{repo}/actions/workflows`). Neither repository has any workflows defined, and therefore no workflow runs (completed or otherwise) exist to delete logs from. No `github_delete_workflow_run_logs` call was made, as there is no run ID to target. The accumulated log files the user described are not attributable to any workflow runs under this account's repositories at this time.

---

## Itinerary

### Morning — Start at BUPT Main Campus (Haidian)

**Beijing University of Posts and Telecommunications**
- Address: 10 Xi Tu Cheng Lu, Beitaipingzhuang, Hai Dian Qu, Bei Jing Shi, China, 100088
- Rating: 4.6
- Place ID: ChIJU3FRAZpT8DURlAfz62QnuAw

She begins the morning here, then travels to the Palace Museum.

**Travel: BUPT (10 Xi Tu Cheng Lu, Beitaipingzhuang, Hai Dian Qu, Bei Jing Shi, China, 100088) → The Palace Museum (4 Jing Shan Qian Jie, Dong Cheng Qu, Bei Jing Shi, China, 100009) — driving**
- Duration: 33 mins (value: 1953 seconds)
- Distance: 10.2 km (value: 10206 meters)

### Mid-Morning — The Palace Museum (Forbidden City)

**The Palace Museum**
- Address: 4 Jing Shan Qian Jie, Dong Cheng Qu, Bei Jing Shi, China, 100009
- Rating: 4.6
- Phone: 400 950 1925
- Website: https://www.dpm.org.cn/Home.html
- Open now: true
- Opening hours (as returned):
  - Monday: Closed
  - Tuesday: 8:30 AM – 4:30 PM
  - Wednesday: 8:30 AM – 4:30 PM
  - Thursday: 8:30 AM – 4:30 PM
  - Friday: 8:30 AM – 4:30 PM
  - Saturday: 8:30 AM – 4:30 PM
  - Sunday: 8:30 AM – 4:30 PM
- Note from recent reviews: tickets sell out quickly (daily cap of 40,000 visitors); passport is strictly required for entry; site is closed on Mondays; visit in the morning to avoid crowds; comfortable shoes and water recommended.

### Lunch — Wangfujing Side

**Xinjiang Flavor Yidecun Stretched Noodle Restaurant**
- Address: 7 Wang Fu Jing Xi Jie, Wangfujing, Dong Cheng Qu, Bei Jing Shi, China, 100006
- Rating: 4.9
- Place ID: ChIJgdyudc9S8DURWJXVHglQ6IE
- Note: well-reviewed (4.9) and within walking distance of the museum on the Wangfujing side.

**Travel: The Palace Museum (4 Jing Shan Qian Jie, Dong Cheng Qu, Bei Jing Shi, China, 100009) → Xinjiang Flavor Yidecun Stretched Noodle Restaurant (7 Wang Fu Jing Xi Jie, Wangfujing, Dong Cheng Qu, Bei Jing Shi, China, 100006) — walking**
- Duration: 22 mins (value: 1301 seconds)
- Distance: 1.4 km (value: 1357 meters)

### Afternoon — Summer Palace

**Summer Palace**
- Address: Haidian District, China, 100091
- Rating: 4.6
- Phone: 010 6288 1144
- Website: https://www.summerpalace.net.cn/
- Open now: true
- Opening hours (as returned):
  - Monday: 6:30 AM – 7:00 PM
  - Tuesday: 6:30 AM – 7:00 PM
  - Wednesday: 6:30 AM – 7:00 PM
  - Thursday: 6:30 AM – 7:00 PM
  - Friday: 6:00 AM – 8:00 PM
  - Saturday: 6:00 AM – 8:00 PM
  - Sunday: 6:30 AM – 7:00 PM
- Note from recent reviews: arrive early to beat crowds; UNESCO World Heritage imperial garden; Kunming Lake, Long Corridor (728 meters of painted beams), and Tower of Buddhist Incense on Longevity Hill are highlights; subway Line 4 to Beigongmen (North Gate), exit D.

**Travel: The Palace Museum (4 Jing Shan Qian Jie, Dong Cheng Qu, Bei Jing Shi, China, 100009) → Summer Palace (Haidian District, China, 100091) — driving**
- Duration: 35 mins (value: 2113 seconds)
- Distance: 21.2 km (value: 21213 meters)

### Evening — Transfer to Beijing Capital International Airport (PEK)

**Beijing Capital International Airport**
- Address: 3JH3+W6X, Shunyi District, Beijing, China (formatted as returned: "3JH3+W6X, Shunyi District, Beijing, China"; resolved destination address in lookup: "3JH3+W6X Beijing Capital International Airport (PEK), Shun Yi Qu, Bei Jing Shi, China")
- Rating: 3.8
- Place ID: ChIJGyBw9t0F8TURVL4jTjr1fEk

**Travel: Summer Palace (Haidian District, China, 100091) → Beijing Capital International Airport (3JH3+W6X, Shunyi District, Beijing, China) — driving**
- Duration: 36 mins (value: 2159 seconds)
- Distance: 35.0 km (value: 34989 meters)

---

### Summary of all travel times (as returned, no rounding)

| Leg | Mode | Duration (text / value) | Distance (text / value) |
|---|---|---|---|
| BUPT → Palace Museum | driving | 33 mins (1953 s) | 10.2 km (10206 m) |
| Palace Museum → Lunch restaurant (Wangfujing) | walking | 22 mins (1301 s) | 1.4 km (1357 m) |
| Palace Museum → Summer Palace | driving | 35 mins (2113 s) | 21.2 km (21213 m) |
| Summer Palace → PEK | driving | 36 mins (2159 s) | 35.0 km (34989 m) |

---

*All addresses, opening hours, ratings, and travel durations/values are reported exactly as returned by the Google Maps place details and distance matrix lookups. Repositories checked: HeziLiu/Little-rookie and HeziLiu/Big-Buzzard (both with 0 workflows).*
