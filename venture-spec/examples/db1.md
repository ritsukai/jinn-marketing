# Default Behavior: Content Creation Workflow

## Context

All content should follow a standard workflow to ensure quality, trackability, and continuous improvement. This workflow aligns with the venture's objectives (maximize impressions, experiment rapidly) and rules (never publish untracked, always cite sources).

## Standard Workflow

**Monitor sources → Draft → Optimize for reach → Add tracking → Distribute → Measure → Iterate**

---

## Follows the Default Behavior

### Example: Blog Post About New Jinn Feature

**1. Monitor sources**
- Daily check of Jinn GitHub commits
- Discovers: New feature "git lineage context" merged to main
- Reads documentation and code to understand feature

**2. Draft**
- Title: "How Jinn's Git Lineage Context Enables Smarter Agent Delegation"
- Content includes:
  - Clear explanation of the feature
  - Code examples from documentation
  - Use cases and benefits
  - Links to source code and docs (citations!)

**3. Optimize for reach**
- Test 3 headlines with different hooks
- Add shareability elements (key takeaways, visual diagram)
- Format for platform (readable on mobile, skimmable)
- Include call-to-action (try Jinn, star on GitHub)

**4. Add tracking**
- Install Google Analytics on blog
- Add UTM parameters: `?utm_source=twitter&utm_medium=social&utm_campaign=git-lineage`
- Set up goal tracking for GitHub link clicks

**5. Distribute**
- Publish to blog
- Share on Twitter with engaging hook
- Post to Hacker News
- Share in relevant Discord/Slack communities

**6. Measure**
- Track impressions: 3,200 views in first 48 hours
- Traffic sources: 60% Twitter, 25% HN, 15% direct
- GitHub clicks: 180 (5.6% conversion rate)
- Engagement: 45 shares on Twitter

**7. Iterate**
- **Learning:** Twitter drove most traffic; HN title didn't resonate
- **Action:** For next post, optimize title for Twitter hooks; test HN title format
- **Scale:** Repurpose content as Twitter thread (reaches different audience)

**Outcome:** 3,200 impressions, 180 GitHub visits, clear data for next iteration.

---

## Violates the Default Behavior

### Example: Rushed Blog Post Without Process

**Scenario:** Agent discovers new Jinn feature and immediately writes a post without following the workflow.

**What happened:**
- ❌ **Skipped monitoring thoroughly:** Misunderstood the feature (incorrect explanation in post)
- ❌ **Skipped optimization:** Title is generic ("Jinn Update"), not compelling
- ❌ **Skipped tracking:** Published without analytics or UTM parameters
- ❌ **Skipped measurement:** No idea how many people read it
- ❌ **Cannot iterate:** No data to inform future content

**Outcome:** Unknown impressions (likely low due to poor title), no learning, wasted effort.

**Why this violates:** Skipped critical steps → poor quality, no measurement, no improvement.

---

## Step-by-Step Breakdown

### 1. Monitor Sources

**Purpose:** Stay current with Jinn developments to identify content opportunities.

**How to do it:**
- Check GitHub commits daily (new features, major changes)
- Review documentation updates
- Monitor GitHub Discussions and Issues
- Track announcements from core team

**What to create content about:**
- ✅ New features (high value)
- ✅ Major improvements or milestones
- ✅ Interesting use cases or demos
- ❌ Minor bug fixes (low interest)
- ❌ Internal refactors (not user-facing)

---

### 2. Draft

**Purpose:** Create clear, accurate content with cited sources.

**How to do it:**
- Start with a compelling hook (why should readers care?)
- Explain the topic clearly (assume readers are smart but unfamiliar with Jinn)
- Include concrete examples (code snippets, demos, use cases)
- Cite sources for technical claims (link to docs, code, or tests)
- End with a call-to-action (try Jinn, star on GitHub, join community)

**Quality bar:**
- Clear and accurate
- Well-structured and skimmable
- Cited sources for all technical claims
- Good enough to ship (don't over-polish)

---

### 3. Optimize for Reach

**Purpose:** Maximize shareability and impressions.

**How to do it:**
- **Headline testing:** Try 3-5 title variations; pick the most compelling
- **Hooks:** Lead with the most interesting insight or benefit
- **Formatting:** Use subheadings, bullet points, code blocks for scannability
- **Visuals:** Add diagrams, screenshots, or demos where helpful
- **Shareability:** Include quotable takeaways, surprising insights
- **Platform fit:** Adjust format for target platform (long-form blog vs. short Twitter thread)

**Optimization checklist:**
- [ ] Headline grabs attention
- [ ] First paragraph hooks readers
- [ ] Content is skimmable
- [ ] Includes shareable elements
- [ ] Formatted for target platform

---

### 4. Add Tracking

**Purpose:** Enable measurement of impressions and optimization (Rule 1).

**How to do it:**
- Install analytics on hosting platform (Google Analytics, Plausible, etc.)
- Add UTM parameters to all shared links
  - `utm_source`: Where you're sharing (twitter, hackernews, reddit, etc.)
  - `utm_medium`: Type of link (social, email, forum, etc.)
  - `utm_campaign`: Content topic (git-lineage, launch-week, etc.)
- Set up goal tracking for key actions (clicks to GitHub, newsletter signups, etc.)
- Verify tracking works before publishing

**Example UTM link:**
```
https://jinn-marketing.com/blog/git-lineage-context?utm_source=twitter&utm_medium=social&utm_campaign=feature-launch
```

---

### 5. Distribute

**Purpose:** Get content in front of target audiences.

**How to do it:**
- Publish to owned channels (blog, website)
- Share on social media (Twitter, LinkedIn, etc.)
- Post to relevant communities (Hacker News, Reddit, Discord, forums)
- Consider timing (weekday mornings often perform better)
- Engage with early responses (reply to comments, answer questions)

**Distribution checklist:**
- [ ] Published to primary platform
- [ ] Shared on 2-3 social channels
- [ ] Posted to 1-2 relevant communities
- [ ] Monitoring for engagement

---

### 6. Measure

**Purpose:** Collect impression and engagement data to inform decisions.

**How to do it:**
- Check analytics dashboard 24 hours after publishing
- Record key metrics:
  - Total impressions (views)
  - Traffic sources (Twitter, HN, direct, etc.)
  - Engagement (time on page, shares, comments)
  - Conversions (GitHub clicks, newsletter signups)
- Compare to previous content
- Identify patterns (what worked, what didn't)

**Metrics to track:**
- **Primary:** Impressions (total views)
- **Secondary:** Engagement (shares, comments, clicks)
- **Tertiary:** Conversions (GitHub visits, signups)

---

### 7. Iterate

**Purpose:** Continuously improve based on data.

**How to do it:**
- Analyze what drove impressions (headline? topic? distribution channel?)
- Identify learnings (what worked, what didn't)
- Apply to next content (double down on winners, fix losers)
- Consider repurposing high-performing content (turn blog post into thread, video, etc.)
- Document insights for other agents

**Iteration checklist:**
- [ ] Identified top-performing element (headline, topic, channel)
- [ ] Documented learning
- [ ] Planned application to next content
- [ ] Considered repurposing/scaling

---

## When Exceptions Apply

**Time-sensitive responses** (e.g., answering a viral question about Jinn):
- May skip optimization step to prioritize speed
- Must still include tracking
- Must still cite sources
- Can iterate after initial response

**Internal documentation** (e.g., team guides):
- May skip distribution and measurement
- Still benefits from drafting and optimization for clarity

**Experiments** (e.g., testing a new format):
- May compress timeline but must include tracking
- Measurement is critical to validate experiment

---

## Relationship to Other Clauses

- **Maximize impressions (obj1):** Optimization and measurement drive reach
- **Experiment rapidly (obj2):** Iteration based on data enables rapid learning
- **Never publish untracked (r1):** Tracking step is mandatory
- **Always cite sources (r2):** Draft step includes source verification
- **Source monitoring pattern (db6):** Monitor sources step identifies content opportunities
