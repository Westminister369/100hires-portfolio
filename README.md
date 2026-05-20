# 100Hires Portfolio Project

## Topic Chosen
**AI-Powered SEO Content Production**

Chosen because of my direct experience in SEO content publishing, 
AI training, and Rank Math optimization — this topic sits at the 
intersection of everything I actively practice.

---

## Tools Installed
- **Cursor IDE** — AI-powered code editor
- **Claude Code Extension** — AI coding assistant inside Cursor
- **Codex Extension** — AI assistant inside Cursor
- **GitHub Desktop** — Version control and pushing commits
- **Google Colab** — Python environment for transcript extraction

---

## Repository Structure

100hires-portfolio/
├── research/
│   ├── linkedin-posts/      # 10 expert LinkedIn posts
│   ├── youtube-transcripts/ # 10 expert transcripts
│   ├── other/
│   └── sources.md           # All 10 experts with links & annotations
└── README.md

---

## Expert Sources
10 genuine practitioners in AI-powered SEO — not just bloggers 
but people actively building, testing, and shipping in this space.

| # | Name | Platform |
|---|------|----------|
| 1 | Aleyda Solis | LinkedIn + YouTube |
| 2 | Kevin Indig | LinkedIn + YouTube |
| 3 | Lily Ray | LinkedIn + YouTube |
| 4 | Kyle Roof | YouTube |
| 5 | Cyrus Shepard | LinkedIn |
| 6 | Brendan Hufford | LinkedIn |
| 7 | Eli Schwartz | LinkedIn |
| 8 | Gael Breton | YouTube |
| 9 | Koray Tuğberk GÜBÜR | LinkedIn + YouTube |
| 10 | Ryan Law | LinkedIn |

Full details with links and annotations → `/research/sources.md`

---

## LinkedIn Posts Collection
- Collected **2 recent posts per expert** across all 10 profiles
- Focused on posts specifically about AI + SEO
- Organized by author inside `/research/linkedin-posts/`
- Each file follows consistent naming: `firstname-lastname-posts.md`

---

## YouTube Transcript Collection
- **7 experts** have their own active YouTube channels
- **3 experts** (Cyrus Shepard, Brendan Hufford, Eli Schwartz) 
  do not have YouTube channels but appeared as **guests** on 
  other channels — those guest video transcripts were tracked 
  down and included
- Result: **All 10 experts have transcript coverage** ✅
- Organized inside `/research/youtube-transcripts/`

### Custom Transcript Tool Built on Google Colab
To automate transcript extraction I built a custom Python-based 
transcriber using `youtube-transcript-api` that takes any 
YouTube video ID and outputs a clean formatted transcript.

🔗 **Colab Transcriber:** https://colab.research.google.com/drive/1Iw1FO9E2WErsWnCbO57OI5eCSTTpMjj0?usp=sharing

---

## Issues Encountered & How I Solved Them
- **Git not pre-installed** → Installed manually from git-scm.com
- **Cursor Agent usage limit exceeded** → Switched to Google Colab 
  for Python automation — kept workflow moving without interruption
- **`YouTubeTranscriptApi.get_transcript()` deprecated** → 
  Debugged the AttributeError, discovered updated syntax using 
  `ytt.fetch()` and resolved independently
- **Claude Code login not prompted** → Researched and confirmed 
  normal behavior when already authenticated
- **3 experts had no YouTube channel** → Found their guest 
 appearances on other channels and extracted those transcripts

---

## Commit History
All changes committed progressively — not in one giant commit:
- Initial setup and README
- Research folder structure
- sources.md with all 10 experts
- LinkedIn posts per expert (individual commits)
- YouTube transcripts per expert (individual commits)
- Final README update

---

## About Me
Bhupender Singh — AI, Content, Marketing & Growth Operations.
Link to Porfolio - https://westminister369.github.io/Portfolio/
