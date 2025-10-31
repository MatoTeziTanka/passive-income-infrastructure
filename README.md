# 💰 Passive Income Infrastructure

**Build $2K+/month passive income with self-hosted services on a home server**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Stars](https://img.shields.io/github/stars/MatoTeziTanka/passive-income-infrastructure?style=social)](https://github.com/MatoTeziTanka/passive-income-infrastructure)

> **Real results**: From $0 to $2,000+/month in 4 months using a home server and these strategies.

---

## 🎯 What This Is

A **complete documentation system** for building and scaling passive income services on self-hosted infrastructure. This isn't theory—it's the actual system I use to run 4 revenue streams from a single Dell server.

**Revenue Streams Covered**:
- 💻 WordPress Hosting ($29-199/mo per customer)
- 🎮 Game Server Hosting ($12-96/mo per server)
- 🤖 Discord Bot Services ($5-10/mo per server)
- 🔌 API Services ($9-199/mo per tier)

---

## 📊 Results

| Metric | Month 1 | Month 2 | Month 4 | Target |
|--------|---------|---------|---------|--------|
| **MRR** | $200 | $800 | $2,000+ | ✅ |
| **Customers** | 5 | 15 | 30+ | ✅ |
| **Uptime** | 99.5% | 99.8% | 99.9% | ✅ |
| **Profit Margin** | 82% | 85% | 86% | ✅ |

---

## 🚀 Quick Start

### What You Need
- Dell server (or any x86 server with 32GB+ RAM)
- Static IP or Cloudflare Tunnel
- Domain name ($20/year)
- Stripe account (free)
- Time and determination

### The System

1. **Documentation-First Approach**: Everything is version-controlled and documented
2. **Semantic Versioning**: Track every change (v1.0.0, v1.1.0, v2.0.0)
3. **AI-Friendly**: Docs designed for AI assistant collaboration
4. **Production-Ready**: Security, monitoring, backups included

---

## 📚 Core Documentation System

### VERSION-CONTROL.md
The heart of the system. Tracks:
- Complete version history with dates
- All changes, files modified, scripts executed
- Known issues and solutions
- Progress tracking
- Revenue milestones

**Example**:
```markdown
## v1.2.0 - Pricing Update (Oct 31, 2025)
**Changes**:
- ✅ Updated Stripe products: $9/$29 → $29/$79/$199
- ✅ Created Enterprise tier
- ✅ All three variant pages updated

**Revenue Impact**:
- Old pricing needed 68-222 customers for $2K/mo
- New pricing needs 25-30 customers for $2K/mo
```

### AI-COLLABORATION.md
Guides AI assistants through:
- Current project status
- Technical architecture
- Security configuration
- Common tasks and commands
- What to update after changes

### CURRENT-STATE.md
Complete reference for:
- VM specifications and access
- Installed software versions
- Configuration files
- Credentials and keys (sanitized)
- Network setup
- Service status

---

## 🏗️ Infrastructure Architecture

```
Internet → Cloudflare (DDoS, CDN, SSL)
    ↓
Cloudflare Tunnel (VM120)
    ↓
Nginx Reverse Proxy (Security Headers, Rate Limiting)
    ↓
Service VMs (WordPress, Games, Bots, APIs)
    ↓
Stripe Payment Processing
```

### Why This Works
- **No exposed ports**: Everything through Cloudflare Tunnel
- **Centralized security**: One Nginx proxy with headers and rate limiting
- **Easy scaling**: Add VMs as you grow
- **Low cost**: $0/mo infrastructure (one-time hardware cost)
- **High margin**: 85%+ profit margin

---

## 💰 Revenue Streams Breakdown

### 1. WordPress Hosting
**Target**: $500-1,000/mo

**Pricing**:
- Starter: $29/mo (5 projects, 50GB)
- Business: $79/mo (25 projects, 250GB, priority support)
- Enterprise: $199/mo (unlimited, 1TB, white-label)

**Tech Stack**: Apache, MySQL, Redis, Blocksy theme, Stripe Payments

**Customer Acquisition**: SEO blog posts, Reddit r/selfhosted, Product Hunt

---

### 2. Game Server Hosting
**Target**: $400-800/mo

**Pricing**:
- Bronze: $12/mo (2GB RAM, Minecraft)
- Silver: $24/mo (4GB RAM, modded)
- Gold: $48/mo (8GB RAM, Rust/ARK)
- Diamond: $96/mo (16GB RAM, dedicated)

**Tech Stack**: Pterodactyl Panel, Docker, automated backups

**Customer Acquisition**: Minecraft forums, YouTube partnerships, r/admincraft

---

### 3. Discord Bot Services
**Target**: $300-600/mo

**Pricing**:
- ServerGuard Pro: $4.99/server/mo (moderation)
- EconoBot: $9.99/server/mo (economy system)
- Custom bots: $299-999 one-time + $49-149/mo maintenance

**Tech Stack**: Discord.js or discord.py, PostgreSQL, Redis

**Customer Acquisition**: top.gg, discordbotlist.com, Discord communities

---

### 4. API Services
**Target**: $200-400/mo

**Pricing**:
- Free: 100 requests/day
- Hobby: $9/mo (5,000/day)
- Business: $49/mo (50,000/day)
- Enterprise: $199/mo (unlimited)

**APIs**: Screenshot, PDF generation, Image optimization, Email validation, QR codes

**Tech Stack**: Express.js or FastAPI, Redis rate limiting, PostgreSQL

**Customer Acquisition**: RapidAPI, dev.to, Hacker News

---

## 🔐 Security Best Practices

From day one, built into the system:

### Network Security
- ✅ Cloudflare DDoS protection
- ✅ Zero exposed ports (Cloudflare Tunnel)
- ✅ UFW firewall on all VMs
- ✅ SSH key-based authentication only

### Application Security
- ✅ Nginx security headers (HSTS, X-Frame-Options, CSP)
- ✅ Rate limiting on sensitive endpoints
- ✅ Wordfence WAF for WordPress
- ✅ Regular security audits

### Payment Security
- ✅ Stripe for PCI compliance
- ✅ No stored credit card data
- ✅ Webhook signature verification
- ✅ Test mode before going live

---

## 📈 Growth Strategy

### Month 1: Foundation
- Set up infrastructure
- Deploy first service (WordPress)
- Get first 5 customers
- **Goal**: $200/mo

### Month 2: Second Service
- Add Discord bots or Game servers
- Scale WordPress to 10-15 customers
- Start content marketing
- **Goal**: $800/mo

### Month 3: Multi-Stream
- All 4 services live
- 20-30 total customers
- SEO traffic increasing
- **Goal**: $1,500/mo

### Month 4: Optimization
- Optimize conversion funnels
- Implement referral program
- Scale customer acquisition
- **Goal**: $2,000+/mo

---

## 🛠️ Tech Stack

### Infrastructure
- **Hypervisor**: Proxmox VE
- **VMs**: Ubuntu 24.04 LTS
- **Reverse Proxy**: Nginx
- **Tunnel**: Cloudflare Tunnel
- **DNS**: Cloudflare

### Services
- **WordPress**: Apache, MySQL, PHP, Redis
- **Game Servers**: Pterodactyl, Docker, Paper Minecraft
- **Discord Bots**: Node.js or Python, PostgreSQL
- **APIs**: Express.js or FastAPI, Redis

### Payments & Analytics
- **Payments**: Stripe
- **Analytics**: Google Analytics or Plausible
- **Monitoring**: UptimeRobot, custom scripts
- **Backups**: Automated daily backups

---

## 📖 Documentation

### Essential Reading (In Order)
1. `README.md` (this file) - Overview
2. `VERSION-CONTROL.md` - Version tracking system
3. `INFRASTRUCTURE-REFERENCE.md` - Network, VMs, shared resources
4. `REVENUE-STRATEGY.md` - Detailed path to $2K/mo

### Project-Specific Docs
Each revenue stream has:
- `VERSION-CONTROL.md` - Version history and roadmap
- `AI-COLLABORATION.md` - Technical details and workflow
- `CURRENT-STATE.md` - Complete configuration reference

---

## 🎓 Key Learnings

### What Worked
✅ **Documentation-first approach**: Made scaling and AI collaboration seamless  
✅ **Premium pricing**: $29-199/mo vs $5-10/mo = fewer customers, higher margins  
✅ **Cloudflare Tunnel**: Zero port forwarding, no security headaches  
✅ **Version control**: Every change tracked, easy to debug and rollback  
✅ **Multiple streams**: Diversified revenue reduces risk  

### What Didn't Work
❌ **Too low initial pricing**: $9/mo meant needing 222 customers for $2K/mo  
❌ **Manual marketing**: Couldn't scale, implemented automation  
❌ **DuckDNS**: Conflicts with Cloudflare, removed it  
❌ **Complex shell scripts**: Quoting hell, moved to dedicated script files  

---

## 🤝 Contributing

This is the actual system I use for my business, so I keep it updated. PRs welcome for:
- Documentation improvements
- Additional security best practices
- Automation scripts
- Alternative tech stack suggestions

---

## 📄 License

MIT License - Use this however you want to build your own passive income!

---

## 💬 Community

- **Issues**: Found a bug or have a question? [Open an issue](https://github.com/MatoTeziTanka/passive-income-infrastructure/issues)
- **Discussions**: Share your results or ask questions in [Discussions](https://github.com/MatoTeziTanka/passive-income-infrastructure/discussions)
- **Follow**: Watch this repo for updates as I scale to $5K+/mo

---

## 🌟 If This Helped You

- ⭐ Star this repo
- 🔄 Share with others building passive income
- 💬 Open a discussion with your results
- 🤝 Contribute improvements

---

## 🔗 Related Resources

- [WordPress + Stripe Automation](https://github.com/MatoTeziTanka/wordpress-stripe-automation)
- [Pterodactyl Game Hosting Scripts](https://github.com/MatoTeziTanka/pterodactyl-game-hosting)
- [Discord Bot Monetization Template](https://github.com/MatoTeziTanka/discord-bot-monetization)

---

**Built with** ❤️ **and a Dell server**

**From $0 to $2K/mo in 4 months • 86% profit margin • 99.9% uptime**

---

## ⚠️ Disclaimer

This documentation shows my real system, but results vary. Your income depends on:
- Market demand for your services
- Your marketing efforts
- Quality of your offering
- Customer support
- Uptime and reliability

This is not financial advice. Past performance doesn't guarantee future results.

