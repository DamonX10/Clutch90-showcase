<div align="center">

# CLUTCH 90

### A better home for your league.

League tables · Fixtures · Results · Player achievements

**Created by [DamonX10](https://github.com/DamonX10)**

Working prototype · Private source · Public project showcase

</div>

---

## The idea

A sporting competition deserves more than a basic spreadsheet. Clutch 90 brings standings, match results, and player statistics into a clear, modern dashboard, so organizers and fans can follow the story of a season.

The long-term vision is to support many kinds of sporting competitions. The current prototype provides a configurable league format, with football statistics as a central feature.

## Built into the prototype

| Feature | What it brings to a league |
| --- | --- |
| **Automatic league tables** | Points, wins, draws, losses, score difference, and recent form update as results are entered. |
| **Top 10 goalscorers** | A dedicated ranking for the players finding the net. |
| **Top 10 assist providers** | Recognition for the players creating the chances. |
| **Team clean sheets** | Automatic credit for every completed match without conceding a goal. A 0–0 gives both teams a clean sheet. |
| **Fixtures and results** | Create a single round-robin schedule, enter scores, and correct results when needed. |
| **Custom competitions** | Set up 2–32 teams, name the season, and choose win/draw/loss points. |
| **Team views** | Explore individual results and compare overall, home, and away performances. |
| **Saved progress** | Competitions persist between visits, with checks to protect newer results from stale edits. |

## Designed for the season

A navy and lime visual identity, responsive layouts, and dedicated statistics views keep the table and its standout performers easy to find. Fictional sample competitions demonstrate the app without presenting sample results as real sporting data.

## Project status

Clutch 90 is a working prototype under active development. Match results and player contributions are entered by an organizer. Leaderboards display up to ten eligible players as statistics become available.

The current scoring model supports configurable points and score-difference rankings. More specialized sporting rules and a live results feed are future possibilities, rather than completed features.

## Behind the build

Built with **React, TypeScript, Tailwind CSS, and Cloudflare D1**. The league calculations are covered by 18 passing automated tests, including result corrections, goals and assists, and team clean sheets. The application has also passed type checking, a production build, and local API checks.

The product idea and direction are by **DamonX10**, with AI-assisted development.

## About this repository

This public repository introduces the project and its features. The full application source and hosted development preview are private.

Follow the creator: **[github.com/DamonX10](https://github.com/DamonX10)**
