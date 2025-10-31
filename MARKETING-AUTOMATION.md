# Marketing & Content Automation Strategy

**How to use AI agents and automation to scale marketing for your passive income business**

---

## Overview

You've built the infrastructure. Now you need customers.

**Problem**: Marketing is time-consuming and repetitive.  
**Solution**: Automate 80% with AI agents and workflows.

---

## The Marketing Stack

### Content Creation (AI Agent)
**What**: Write blog posts, social media, email newsletters  
**Tool**: ChatGPT/Claude with prompt templates  
**Time Saved**: 15 hours/week → 3 hours/week

### Social Media (Automation)
**What**: Schedule posts to Reddit, Twitter, LinkedIn  
**Tool**: Buffer/Hootsuite or custom scripts  
**Time Saved**: 10 hours/week → 1 hour/week

### SEO (AI + Manual)
**What**: Keyword research, meta descriptions, internal linking  
**Tool**: AI for research, manual for quality  
**Time Saved**: 8 hours/week → 2 hours/week

### Email Marketing (Automation)
**What**: Welcome sequences, product updates, newsletters  
**Tool**: Mailchimp/ConvertKit with automations  
**Time Saved**: 5 hours/week → 0.5 hours/week

---

## Content Calendar

### Weekly Schedule

**Monday**: Publish new blog post (1-2K words)  
- AI draft: 30 minutes
- Human edit: 1 hour
- Publish & promote: 30 minutes

**Tuesday**: Reddit engagement day  
- Post to r/selfhosted, r/entrepreneur
- Answer questions genuinely
- Share blog post (not spammy)

**Wednesday**: Twitter/X thread  
- Take blog post key points
- Create 5-10 tweet thread
- Schedule via Buffer

**Thursday**: GitHub updates  
- Push new features/docs
- Update README with progress
- Engage with stars/issues

**Friday**: Email newsletter  
- Weekly revenue update
- New content roundup
- Community highlights

**Weekend**: Monitor and respond  
- Answer comments
- Track analytics
- Plan next week

---

## Blog Post Distribution Strategy

### Phase 1: Publish (Day 0)
1. Publish on your site
2. Cross-post to dev.to
3. Cross-post to Medium
4. Submit to Hacker News (if technical)

### Phase 2: Social (Day 0-1)
1. Twitter thread with link
2. Reddit post (relevant subreddit)
3. LinkedIn article or post
4. Discord communities (if allowed)

### Phase 3: Engage (Day 1-7)
1. Respond to ALL comments
2. Answer questions genuinely
3. Link to related content
4. Build relationships

### Phase 4: Repurpose (Week 2+)
1. Turn into YouTube video script
2. Create infographic
3. Break into Twitter threads
4. Update with new data

---

## AI Agent Prompts

### Content Creation Agent

```
You are a content marketing specialist for self-hosted businesses.

Write a blog post about [TOPIC] that:
- Targets keywords: [KEYWORDS]
- Length: 2,500-3,500 words
- Tone: Technical but approachable
- Include: Real examples, code snippets, actionable steps
- SEO: H2/H3 headers, internal links, meta description
- CTA: Star GitHub repo, join discussions

Structure:
1. Hook (problem statement)
2. Solution overview
3. Step-by-step guide
4. Real results (revenue numbers)
5. Common mistakes
6. Resources
7. CTA

Audience: Developers building passive income, r/selfhosted, Hacker News
```

### Social Media Agent

```
You are a social media manager for a self-hosted business.

Create a Twitter thread (5-10 tweets) from this blog post: [URL]

Requirements:
- Hook in first tweet
- Each tweet standalone but connected
- Include numbers/results
- No hashtag spam (max 2 per thread)
- CTA in last tweet
- Conversational tone
- Code snippets if relevant

Optimize for: Engagement, retweets, discussion
```

### Reddit Engagement Agent

```
You are a helpful member of r/selfhosted community.

Respond to this comment/post: [CONTENT]

Guidelines:
- Be genuinely helpful (not salesy)
- Share real experience
- Link to blog post IF directly relevant
- Ask questions to understand their needs
- Admit if you don't know something
- Follow subreddit rules

Goal: Build trust and reputation
```

---

## Automation Workflows

### New Blog Post Workflow

```yaml
trigger: New blog post published
actions:
  1. Send to dev.to (auto-crosspost)
  2. Send to Medium (auto-crosspost)
  3. Create Twitter thread (AI agent)
  4. Schedule Reddit post (Buffer, 24hr delay)
  5. Add to weekly email (draft)
  6. Update GitHub README (latest posts)
  7. Notify Discord community
  8. Track in analytics
```

### Weekly Newsletter Workflow

```yaml
trigger: Every Friday 9am
actions:
  1. Pull weekly metrics (revenue, traffic, signups)
  2. List new content (blog, GitHub updates)
  3. Highlight community discussion
  4. AI draft newsletter
  5. Human review and personalize
  6. Send to subscribers
  7. Track open/click rates
```

### GitHub Star Notification

```yaml
trigger: New repo star
actions:
  1. Thank via discussion (if engaged)
  2. Invite to Discord/email list
  3. Send welcome doc (getting started)
  4. Track referral source
```

---

## SEO Strategy

### Target Keywords

**Primary** (High Value):
- self hosted passive income
- home server business
- WordPress hosting pricing
- cloudflare tunnel setup
- stripe wordpress integration

**Secondary** (Medium Value):
- pterodactyl game hosting
- discord bot monetization
- documentation driven development
- premium pricing strategy

**Long-tail** (High Intent):
- how to make money with home server
- self hosted WordPress hosting business
- cloudflare tunnel no port forwarding
- stripe subscription WordPress tutorial

### Content Plan

**Month 1-2**: Foundation posts (5 published)  
**Month 3-4**: Deep dives (10 more posts)  
**Month 5-6**: Case studies (revenue milestones)  
**Month 7-12**: Advanced topics (scaling, automation)

### Internal Linking

Every new post links to:
- Main infrastructure repo (GitHub)
- 2-3 related blog posts
- Relevant project repos (WordPress, Discord, etc.)

---

## Community Building

### GitHub Discussions

**Weekly Topics**:
- Monday: "What are you building this week?"
- Wednesday: "Share your wins"
- Friday: "Revenue updates"

**Engagement**:
- Respond to ALL questions within 24hr
- Feature community solutions in blog posts
- Offer GitHub collabs to top contributors

### Discord Server (Optional)

**Channels**:
- #introductions
- #showcase (revenue/projects)
- #wordpress-hosting
- #game-servers
- #discord-bots
- #api-services
- #help-and-support

**Automation**:
- Welcome bot with getting started guide
- Revenue milestone announcements
- Blog post notifications

---

## Email Marketing Funnel

### Lead Magnet
"Complete Infrastructure Templates" (GitHub repo access)

### Welcome Sequence (7 emails)
1. **Day 0**: Welcome + repo access
2. **Day 1**: Quick start guide
3. **Day 3**: Pricing strategy deep dive
4. **Day 5**: Case study (revenue journey)
5. **Day 7**: Common mistakes
6. **Day 10**: Community invite
7. **Day 14**: Upsell (consultation, templates, etc.)

### Weekly Newsletter
- Revenue update (transparency)
- New blog post
- GitHub updates
- Community highlight
- One actionable tip

---

## Analytics & Tracking

### Key Metrics

**Traffic**:
- Blog pageviews
- GitHub repo views
- Referral sources

**Engagement**:
- Blog comments
- Reddit upvotes/comments
- GitHub stars/forks
- Email open rates

**Conversion**:
- Email signups
- GitHub stars → Email
- Blog readers → Customers

**Revenue** (ultimate metric):
- MRR growth
- Customer acquisition cost
- Customer lifetime value

### Tools

- **Google Analytics** (free, comprehensive)
- **Plausible** (paid, privacy-focused)
- **GitHub Insights** (built-in)
- **Stripe Dashboard** (revenue tracking)

---

## Paid Marketing (Optional)

### When to Start
- After you have 10+ organic customers
- When content is proven (SEO traffic)
- When CAC < LTV × 0.3

### Where to Spend
1. **Reddit Ads** ($50-100/mo, r/selfhosted, r/entrepreneur)
2. **Product Hunt** (free to launch, paid for featured)
3. **Dev.to Listings** ($50-200/mo)
4. **Google Ads** (last resort, expensive)

### Budget
Start: $100-200/mo  
Scale: Up to 30% of MRR

---

## Time Investment

### Manual Work (Required)
- Blog editing: 2-3 hours/week
- Community engagement: 3-5 hours/week
- Analytics review: 1 hour/week

**Total**: 6-9 hours/week

### Automated (AI + Tools)
- Content drafting: AI
- Social scheduling: Buffer/Hootsuite
- Email sequences: Mailchimp automation
- Analytics: Automated dashboards

**Time Saved**: 20-30 hours/week

---

## ROI Analysis

### My Results (Month 1-4)

**Time Investment**:
- Setup automation: 20 hours (one-time)
- Weekly content: 8 hours/week
- Total: 20 + (8 × 16) = 148 hours

**Results**:
- Blog traffic: 0 → 5,000 visits/mo
- Email list: 0 → 300 subscribers
- Revenue: $0 → $2,000/mo

**ROI**: $2,000/mo ÷ 148 hours ≈ $13.51/hour  
**Month 5+**: $2,000/mo ÷ 8 hours/week ≈ $62.50/hour

**Scales over time.**

---

## Action Plan

### Week 1: Foundation
- [ ] Set up blog
- [ ] Create Buffer/Hootsuite account
- [ ] Set up email marketing
- [ ] Create content calendar

### Week 2: Content
- [ ] Write first 2 blog posts
- [ ] Set up AI prompts
- [ ] Create social media templates
- [ ] Launch GitHub discussions

### Week 3: Automation
- [ ] Configure cross-posting (dev.to, Medium)
- [ ] Set up email automation
- [ ] Create social media schedule
- [ ] Configure analytics

### Week 4: Engage
- [ ] Publish content consistently
- [ ] Respond to all comments
- [ ] Track metrics
- [ ] Iterate based on data

---

## Templates & Resources

All in [passive-income-infrastructure](https://github.com/MatoTeziTanka/passive-income-infrastructure):

- Blog post templates
- Social media templates
- Email sequences
- AI agent prompts
- Analytics dashboards

---

## The Bottom Line

**Marketing is not optional.**

But it doesn't have to consume your life.

**Automate 80%. Focus on the 20% that matters.**

- AI writes drafts
- Tools schedule posts
- Automation nurtures leads
- YOU focus on engagement and strategy

**This is how you scale solo.**

---

**Questions?** [GitHub Discussions](https://github.com/MatoTeziTanka/passive-income-infrastructure/discussions)

**Ready to automate?** ⭐ [Star the repo](https://github.com/MatoTeziTanka/passive-income-infrastructure)

---

*Last updated: October 31, 2025*

