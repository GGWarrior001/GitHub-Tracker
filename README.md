# gitnetic · Modern GitHub Tracker

A clean, real-time dashboard for tracking GitHub profiles. Enter any GitHub username to see key stats, language distribution, recent activity, and a detailed repository list — all presented with a modern glass‑morphism UI.


## ✨ Features

- **User Profile Overview** – avatar, bio, followers/following, public repos.
- **Key Metrics** – total stars, forks, and repository count at a glance.
- **Language Breakdown** – top 5 languages with percentage bars.
- **Recent Activity** – latest events (pushes, stars, forks, PRs, issues) with timestamps.
- **Repository Explorer** – sort by stars, show description, stars, forks, and last update.
- **Fully Responsive** – works on desktop, tablet, and mobile.
- **Instant Search** – type a username and hit Enter or click "Track".

## 🚀 How to Use

1. **Clone or download** this repository.
2. Open `index.html` in any modern web browser (no build step needed).
3. Enter a GitHub username (e.g., `octocat`, `torvalds`) and press **Track**.
4. Explore the dashboard – all data is fetched live from the GitHub API.

> **Note:** Unauthenticated API requests are limited to 60 per hour per IP. For heavier usage, you can add a [GitHub personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) by modifying the fetch headers.

## 🛠️ Built With

- **HTML5 / CSS3** – custom layout, glass‑morphism effects, grid/flexbox.
- **JavaScript (ES6+)** – async fetch, dynamic DOM updates.
- **GitHub REST API** – public endpoints for user, repositories, and events.
- **Font Awesome 6** – icons for visual clarity.
- **Google Fonts (Inter)** – modern typography.

