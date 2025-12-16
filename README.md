🛡️ CompliQuest - Gamified Compliance Platform

CompliQuest is an interactive employee interface that turns mandatory compliance training into an engaging RPG (Role-Playing Game).

Instead of boring checklists, employees complete "Missions" to earn XP, unlock Badges, and climb the Leaderboard. This tool demonstrates how Gamification Mechanics can increase policy adherence and reduce organizational risk.
✨ Key Features

    RPG Progression: Employees earn XP (Experience Points) for every policy read or quiz passed, leveling up from "Associate" to "Compliance Hero."

    Mission System: Breaks down daunting tasks (e.g., "Annual GDPR Review") into bite-sized, achievable quests with clear rewards.

    Visual Feedback: Instant gratification through animated XP bars, toast notifications, and confetti celebrations when leveling up.

    Risk Dashboard: Real-time visualization of the user's "Compliance Score" and "Risk Level" based on their activity.

    Micro-Learning: "Daily Rapid Fire" quizzes test knowledge retention in <30 seconds.

🚀 Quick Start

    Download the index.html file.

    Open it in any modern web browser (Chrome, Edge, Safari).

    Start the Demo:

        Click "Start Daily Quiz" on the Dashboard.

        Navigate to the Missions tab.

        Click "Start" on a task (e.g., IT Security Setup).

        Watch your XP bar grow and unlock badges in the Badges tab.

🎮 The Gamification Logic

The core engine revolves around the userStats object and the tasks array.
XP & Leveling
XPnew​=XPcurrent​+TaskValue

When XPnew​≥XPthreshold​, the user levels up, and the threshold increases by 50% (threshold * 1.5), making higher levels progressively harder to reach.
Badge Logic

Badges are unlocked based on specific triggers in the code:

    First Steps: Unlocks on 1st task completion.

    Secure Hero: Unlocks at Level 5.

    Phish Proof: Unlocks specifically after the "Phishing Simulation" task.

⚙️ Configuration

You can customize the tasks and rewards by editing the data arrays in the <script> section:
JavaScript
