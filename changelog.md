# PointBank Update Log

All notable changes to PointBank will be documented in this file.

---

# Version 1.2 – Daily Streak System

Release Date: 2026

## Added

### Daily Streak System

Users now build streaks by claiming `/daily` rewards consecutively.

If users claim `/daily` multiple days in a row, they earn streak bonuses.

---

### Streak Milestones

| Streak | Bonus |
|------|------|
| 3 Days | Bonus points |
| 5 Days | Increased bonus |
| 15 Days | Large bonus |
| 30 Days | Major reward |

---

### Streak Reset

If a user does not claim `/daily` within **48 hours**, the streak resets.

---

## Added Commands

`/weekly`  
Users can now claim a weekly reward with a higher payout.

`/leaderboard`  
Displays the top users in the server ranked by total points.

---

## Improvements

• Improved reward tracking  
• Better database handling  
• Leaderboard now displays user mentions

---

# Version 1.1 – Initial Release

## Features

• Daily rewards system  
• Point tracking  
• SQLite database  
• Slash command support

## Added

### Community Jackpot System 🎰

A new community jackpot pool has been implemented.

The jackpot grows through:

• Points lost during games (such as coinflip)  
• Points from inactive users leaving the server  
• Community contributions

---

### Monthly Jackpot Lottery

A jackpot drawing occurs every **30 days**.

Users can purchase tickets using their points.

The winner receives the **entire jackpot pool**.

If no tickets are purchased during the cycle, the jackpot **rolls over** to the next month.