# Spotify Ads MCP Starter Kit — Manage Spotify Advertising with AI

[![MCP Compatible](https://img.shields.io/badge/MCP-compatible-blue)](https://modelcontextprotocol.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform: Spotify Ads](https://img.shields.io/badge/Platform-Spotify%20Ads-1DB954)](https://ads.spotify.com)

**Reach listeners during their most personal moments — commutes, workouts, cooking, studying.** Open this repo in Amp, Cursor, or VS Code and manage Spotify ad campaigns with AI — target by music genre, mood, podcast category, and listening context.

---

## Why Spotify Ads + AI?

Spotify has 640 million users, including 250 million on the ad-supported free tier. These listeners spend 2+ hours per day on the platform — during moments when they can't look at a screen but are deeply engaged with audio.

Audio advertising is fundamentally different from visual ads. There's no "scrolling past" a 30-second audio ad between songs. Completion rates are 95%+ (vs 30% for video ads). And because Spotify knows what people listen to, it can infer mood, activity, and context — "running playlist" means workout mode, "lo-fi beats" means study mode, "dinner jazz" means cooking.

This contextual intelligence makes Spotify uniquely powerful for brand awareness. You're not interrupting — you're reaching people in a receptive, personal moment.

**Best for:** Brand awareness, CPG products, app installs, event promotion, reaching younger demographics (18-34), podcast audiences, reaching people during screen-free moments.

---

## Quick Start (30 Seconds)

### Amp / Cursor / VS Code (Copilot)

1. **Get a free API key** at [syntermedia.ai/developer](https://syntermedia.ai/developer)
2. **Set the key:**
   ```bash
   export SYNTER_API_KEY=syn_your_key_here
   ```
3. **Open this repo** in your editor
4. **Start chatting** — MCP tools are pre-configured in `.mcp.json`

### Claude Desktop

Copy `claude_desktop_config.json` to your Claude config directory and replace the API key:

- **macOS:** `~/Library/Application Support/Claude/claude_desktop_config.json`
- **Windows:** `%APPDATA%\Claude\claude_desktop_config.json`

---

## What You Can Do

| Capability | Example |
|-----------|---------|
| **Audio Ad Campaigns** | "Create a 30-second audio ad campaign targeting workout playlist listeners" |
| **Podcast Ads** | "Run pre-roll ads on tech and business podcasts" |
| **Genre Targeting** | "Target fans of hip-hop, pop, and electronic music aged 18-30" |
| **Mood Targeting** | "Reach people listening to 'chill' and 'focus' mood playlists" |
| **Context Targeting** | "Show ads to people during their morning commute" |
| **Display Companion** | "Create a companion display ad that appears during my audio spot" |
| **Campaign Reports** | "What's my ad completion rate and cost per completed listen?" |
| **Budget Management** | "Adjust my podcast campaign budget to $2,000/month" |
| **Audience Building** | "Target people who listen to true crime podcasts and live in major US cities" |
| **Frequency Control** | "Cap exposure to 4 audio ads per listener per week" |

---

## Example Conversations

### 1. First Audio Ad Campaign

> **You:** I run a meditation app. I want to try Spotify Ads. Budget is $3,000/month.
>
> **Agent:** Spotify is perfect for a meditation app — you're reaching people who are already in a listening mindset. Here's my plan:
>
> **Campaign structure:**
>
> **Ad Group 1: Mood targeting ($1,500/month)**
> - Target: "Chill," "Focus," "Sleep" mood playlists
> - These listeners are already seeking calm — your meditation app is a natural fit
> - Format: 30-second audio spot + companion display banner
>
> **Ad Group 2: Podcast targeting ($1,000/month)**
> - Target: Health & Wellness, Mental Health, Self-Improvement podcast categories
> - Format: 15-second pre-roll ("Before we start, a quick word from...")
> - Podcast listeners are highly engaged and trust audio recommendations
>
> **Ad Group 3: Activity targeting ($500/month)**
> - Target: Listeners during "Wind Down" and "Evening" listening sessions
> - This is when people are open to mindfulness content
>
> **Creative tips for your audio ad:**
> - Start with a calming sound (chime, nature sound) — not a loud "HEY!"
> - Speak slowly and calmly — match the listener's mood
> - CTA: "Download [App] — your first 7 days are free. Just say 'Hey Spotify, remind me'"
> - Keep it 30 seconds max. Audio ads can't be skipped, so respect the listener's time.
>
> **Expected results:** 95%+ completion rate, $8-15 CPM, ~250,000 completed listens/month.

### 2. Podcast Advertising Strategy

> **You:** I want to advertise on specific podcasts, not just categories. Can I do that?
>
> **Agent:** Yes — Spotify offers both category-level and show-level podcast targeting (subject to inventory). Here's the difference:
>
> **Category targeting (broad reach):**
> - Target all podcasts in "Technology," "Business," or "True Crime"
> - Larger audience, lower CPM ($8-12)
> - Less control over which specific shows
>
> **Show-level targeting (precision):**
> - Target specific popular podcasts (subject to availability)
> - Smaller audience, higher CPM ($15-25)
> - Your ad appears in shows your ideal customer actually listens to
>
> For your B2B SaaS product, I'd recommend:
>
> **Tier 1 (show-level, $20 CPM):**
> - Tech/startup podcasts with business-professional audiences
> - Business news/analysis podcasts
>
> **Tier 2 (category, $10 CPM):**
> - "Technology" and "Business" categories
> - "Entrepreneurship" and "Career" categories
>
> **Pro tip:** Podcast ads have a 4.4x brand recall rate compared to display ads. Listeners feel a parasocial relationship with podcast hosts, and that trust transfers to advertisers. A host-read ad (if available) outperforms pre-produced spots 3x.

### 3. Contextual Targeting Deep Dive

> **You:** What does "context targeting" mean on Spotify? How is it different from genre targeting?
>
> **Agent:** Context targeting on Spotify is genuinely unique. It targets based on *what the listener is doing*, not just what they're listening to.
>
> **Genre targeting:** Targets musical preference (hip-hop fans, classical music listeners)
>
> **Context targeting:** Targets the listening moment:
>
> | Context | What Listener Is Doing | Best For |
> |---|---|---|
> | Morning Commute | Driving/transit, 6-9 AM | Coffee brands, news apps, podcasts |
> | Workout | High-energy playlists | Fitness apps, sports drinks, athleisure |
> | Focus/Study | Lo-fi, ambient, classical | Productivity tools, nootropics, education |
> | Cooking/Dinner | Dinner party playlists | Food delivery, kitchen gadgets, wine |
> | Party/Social | Upbeat, dance playlists | Alcohol, events, nightlife |
> | Sleep/Wind Down | Calm, sleep playlists | Sleep apps, mattresses, tea, meditation |
> | Running | Running-tempo playlists | Running shoes, sports watches, fitness apps |
>
> **Example for your meditation app:**
> Instead of targeting "ambient music fans" (genre), I'd target "Sleep/Wind Down" and "Focus" contexts. These listeners are in the *exact mental state* where your product is most relevant.
>
> The conversion psychology: You're not interrupting them with an unrelated ad — you're offering something that matches their current need.

### 4. Audio Creative Best Practices

> **You:** I've never made an audio ad. What makes a good one?
>
> **Agent:** Audio ads are a different beast from visual ads. Here's a framework:
>
> **The 30-second formula:**
>
> | Section | Duration | Purpose |
> |---|---|---|
> | Hook | 0-5 sec | Catch attention with a sound, question, or bold statement |
> | Problem | 5-12 sec | State the problem your product solves |
> | Solution | 12-22 sec | Introduce your product as the answer |
> | CTA | 22-30 sec | Clear, simple next step |
>
> **Good example (meditation app):**
> > *[Gentle chime]* "Feeling overwhelmed? You're not alone — 40% of adults report daily stress. Breathly is a meditation app that guides you through 5-minute sessions designed by psychologists. Download Breathly free — your first week is on us."
>
> **Bad example:**
> > *[Loud jingle]* "BREATHLY! THE BEST MEDITATION APP! DOWNLOAD NOW! BREATHLY DOT COM! FIVE STARS ON THE APP STORE!"
>
> **Key rules:**
> - **Match the listener's energy.** If they're on a chill playlist, don't yell.
> - **One CTA only.** "Download the app" not "Visit our website, follow us on Instagram, and download the app."
> - **Use sound design.** A 2-second ambient sound at the start signals "this is an ad" without being jarring.
> - **Keep it to 30 seconds.** You can run 15-second spots, but 30 seconds is the sweet spot for storytelling.
> - **Companion banner matters.** 60% of free Spotify users glance at the screen during audio ads. Include a display companion.

### 5. Measuring Audio Ad Effectiveness

> **You:** How do I know if my Spotify Ads are working? People can't click an audio ad.
>
> **Agent:** Great question — audio measurement is different from digital display. Here's what to track:
>
> **Primary metrics:**
> | Metric | What It Means | Benchmark |
> |---|---|---|
> | Completion Rate | % who heard the full ad | 95%+ (audio ads can't be skipped) |
> | Companion Click Rate | % who tapped the display banner | 0.3-0.8% |
> | Cost per Completed Listen | What you paid for a full listen | $0.015-0.025 |
> | Reach | Unique listeners exposed | Varies by budget |
> | Frequency | Avg listens per unique user | Target 3-5 per week |
>
> **Secondary metrics (off-platform):**
> - **Branded search lift:** Did Google searches for your brand increase after the campaign?
> - **Direct traffic lift:** Did website direct visits increase?
> - **App installs:** Spotify can pass attribution data to mobile measurement partners
> - **Foot traffic:** For physical stores, measure store visit lift
>
> Let me pull your current campaign data...
>
> Your completion rate is 97.2% (excellent), companion click rate is 0.6% (above average), and cost per completed listen is $0.018. Google Trends shows a 23% increase in branded searches since the campaign started — strong evidence of awareness lift.

---

## Spotify Ads Tips from the Pros

1. **30-second audio with clear CTA.** Keep your spot to 30 seconds. One message, one CTA. Audio listeners have excellent recall for simple, clear messages.
2. **Match the listener's mood.** Your ad tone should match what they're listening to. A calm ad between lo-fi tracks; an energetic ad between workout songs.
3. **Podcast ads have 4.4x recall.** Podcast listeners are more attentive than music listeners. Allocate 30-40% of your Spotify budget to podcast targeting.
4. **Companion banners aren't optional.** 60% of free-tier users see the screen during audio ads. The companion display doubles as your visual CTA.
5. **Target by context, not just genre.** "Workout mode" is more actionable than "hip-hop fan." Context tells you what someone is doing, which predicts what they need.
6. **Frequency cap at 4-5 per week.** Audio ads have high completion rates, so listeners hear every single exposure. More than 5x/week becomes annoying.
7. **Audio ads can't be A/B tested in-platform.** Create 2-3 different audio spots with different hooks and rotate them to find winners manually.

---

## FAQ

### Is there an MCP for Spotify Ads?
Yes — this repo. It pre-configures the Synter MCP server for Spotify Ads management. Works with Amp, Cursor, VS Code, and Claude Desktop.

### What types of ads can I run on Spotify?
Audio ads (15/30 seconds between songs), podcast ads (pre/mid/post-roll), display banners (companion to audio ads), and video ads (in-app video for mobile users).

### How much do Spotify Ads cost?
Spotify Ads Manager has a $250 minimum campaign spend. CPMs range from $8-25 depending on targeting. Podcast ads are more expensive ($15-25 CPM) but have higher engagement.

### Can I target specific playlists?
You can target playlist categories (workout, chill, focus, party) and mood types, but not specific playlists by name. Genre, context, and demographic targeting are the primary levers.

### Do Spotify Ads work for B2B?
Podcast targeting makes Spotify viable for B2B. Target business, technology, and entrepreneurship podcast categories to reach professionals. Audio ads between music are better suited for B2C.

---

## Related Repos

- [trade-desk-agent](https://github.com/Synter-Media-AI/trade-desk-agent) — Programmatic audio + CTV + display
- [meta-ads-agent](https://github.com/Synter-Media-AI/meta-ads-agent) — Visual ads on Facebook/Instagram
- [cross-platform-ads-agent](https://github.com/Synter-Media-AI/cross-platform-ads-agent) — Multi-channel management
- [ai-creative-agent](https://github.com/Synter-Media-AI/ai-creative-agent) — Generate ad creative
- [audience-sync-agent](https://github.com/Synter-Media-AI/audience-sync-agent) — Sync audiences across platforms
- [slack-ads-agent](https://github.com/Synter-Media-AI/slack-ads-agent) — Get campaign alerts in Slack

---

## License

MIT — see [LICENSE](LICENSE) for details.

Built by [Synter](https://syntermedia.ai) · [Get API Key](https://syntermedia.ai/developer) · [Documentation](https://syntermedia.ai/docs)
