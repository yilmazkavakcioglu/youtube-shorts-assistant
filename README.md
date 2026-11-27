# YouTube Shorts Assistant 🎬

A **YouTube Shorts team lead for Claude**: 4 Claude skills that run your Shorts channels from ideas and scripts to policy checks and weekly reports.

## What's inside

| Skill | What it does |
| --- | --- |
| `youtube-assistant` | The team lead. Runs the weekly production cycle, routes work to the other skills, reports the top 5 / bottom 5. |
| `shorts-channel-strategy` | Niche selection, channel setup, 90-day plan, reading YouTube Studio analytics. |
| `shorts-script` | 3 hook options, second-by-second scripts, titles, descriptions, Reels/TikTok versions. |
| `shorts-policy-check` | Pre-publish risk review against YouTube's monetization policies. |

## What it's built on

Research from November 2026:

- The YouTube Partner Program changes taking effect February 1, 2027 (20M Shorts views to join, an ongoing 10M threshold for Shorts ad revenue)
- The "inauthentic / repetitive content" and reused content policies
- How the Shorts algorithm works: viewed vs swiped away, percentage viewed, loops
- What top Shorts creators do: one-second hooks, writing the hook and last line first, foreshadowing, hard endings, content buckets, top 5 / bottom 5 reviews
- Shorts SEO, revenue reality (RPM, country differences), gear priorities

> ⚠️ Numbers and policies change. The assistant is written to check current information before money or policy decisions. Not legal or financial advice.

## Install

**Claude Code:**

```bash
git clone https://github.com/yilmazkavakcioglu/youtube-shorts-assistant.git
cp -r youtube-shorts-assistant/skills/* ~/.claude/skills/
```

**Claude app (claude.ai):** Zip each folder inside `skills/` separately and upload them in the Skills section of Claude's settings.

## Usage

Tell Claude:

- "YouTube assistant, I'm starting a new channel"
- "Give me 8 Shorts ideas for this week"
- "Write a script about …"
- "Run a policy check on this Short before I publish it"
- "Here's this week's Studio data: … give me the report"

In the first conversation the assistant asks how many channels you run, in which languages and niches, and at what pace. It replies in your language.

## Contributing

Issues and pull requests are welcome, especially updates when YouTube changes its policies or thresholds.

## Author

Made by **Yılmaz Kavakçıoğlu**: designer and digital marketer with 6–7 years in brand identity, advertising and digital marketing.

- GitHub: [@yilmazkavakcioglu](https://github.com/yilmazkavakcioglu)
- LinkedIn: [yilmazkavakcioglu](https://www.linkedin.com/in/yilmazkavakcioglu/)
- Instagram: [@yilmazcreativee](https://www.instagram.com/yilmazcreativee/)

If this helps you, a ⭐ on the repo helps others find it.

## License

MIT
