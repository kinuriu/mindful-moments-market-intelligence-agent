# README

# Mindful Moments: Market Intelligence Agent

An AI-powered market research agent built in **Amazon QuickSuite**, created as a Udacity project. It analyzes the meditation and mindfulness app market to inform go-to-market decisions for **Mindful Moments**, a mental wellness app I’m designing for a UI/UX internship.

## The Business Question

Should Mindful Moments enter the meditation/mindfulness app market, and if so, how should it price and position itself against established players like Calm and Headspace?

## How It Works

1. **Dataset -** the Google Play Store Apps dataset (~10,800 apps + 64,000 user reviews) was uploaded to a QuickSuite Space as an internal knowledge source.
2. **Agent** - a Chat agent (“Market Intelligence Agent – Mindful Moments”) was configured to analyze the dataset and distinguish internal, data-driven findings from external research.
3. **Quick Research** - used to gather external signals on market size, competitor pricing, and growth trends.
4. **Market Analysis** - the agent synthesized both sources into 5 key insights with supporting evidence.
5. **Reliability Evaluation** - each insight was scored for confidence (High/Medium/Low) based on source quality, consistency, and timeliness.
6. **Market Intelligence Brief** - a final executive-ready brief summarizing findings, confidence levels, limitations, and strategic implications.

## What’s in This Repo

| Folder | Contents |
| --- | --- |
| `/data` | The Google Play Store datasets used as the internal knowledge source |
| `/research` | Quick Research output on the competitive landscape |
| `/reliability-evaluation` | Per-insight reliability evaluation (evidence source, gaps, confidence, limitations) |
| `/market-intelligence-brief` | The final Market Intelligence Brief |
| `/screenshots` | Agent setup, Quick Research, and Space screenshots |

## Key Insights (Summary)

1. The meditation/mindfulness app market is large and still growing fast (~$2.2B → $7-10B by the early 2030s).
2. Calm and Headspace dominate downloads and revenue, but the broader market is highly fragmented.
3. Annual subscription pricing has converged to a $60-70/year norm across leading apps.
4. Insight Timer’s free-tier scale shows freemium is a viable path to install growth.
5. User sentiment in the category rewards reliability and simplicity over content volume.

See the full Brief for evidence, confidence ratings, and strategic implications.

## Tools Used

- Amazon QuickSuite (Chat agent, Quick Research)
- Kaggle’s Google Play Store Apps dataset

## Note

This is a portfolio project built on a business scenario for Mindful Moments, which is an app concept I’m designing independently.
