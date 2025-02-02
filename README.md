# Storywise


Storywise is the simplest analytics tool you've ever seen. Simplicity is at the core of its existence. It's built to be easy to use and easy to host and it's built to be fast and reliable. 

And the best thing is that you can get up and running with Storywise for **FREE** by using the free tiers of your favourite hosting services.

# Resources

- [Website](https://joinstorywise.com)
- [Documentation](https://joinstorywise.com/docs)
- [Demo](https://demo.joinstorywise.com/admin) - user=admin, password=123

# Core design principles

- ✅ **Simple**: It's easy to use and easy to host. It's built to be small, fast, and reliable.
- 🚀 **Fast**: It's built to be fast and reliable.
- 🫴 **Open Source**: It's open source, free to use and free to self-host (for the most part).

# Feature roadmap
- [x] Time range selector (preset for now)
- [x] Unique visitors over time
- [x] General stats (total visitors, total pageviews, views per visitor)
- [x] Unique visitors per page (top 10 + more)
- [x] Pageviews per page (top 10 + more)
- [x] Top referrers (top 10 + more)
- [ ] Top countries (top 10 + more)
- [ ] Top devices - mobile, desktop, tablet
- [ ] Top browsers - chrome, safari, firefox, edge, etc
- [ ] Top OS - windows, mac, linux, ios, android, etc
- [ ] Frontend privacy levels - sever-side only, client-side fingerprint, client-side local storage (current default)
- [ ] Bounce rate
- [ ] UTM tags
- [ ] Custom events
- [ ] Retention analysis

# What you'll need

- **MongoDB** - uses the simplest most popular document database to store data, and yes, it'll be good enough for your needs.
- **Hosting** - you can host it anywhere you want - we have a **container** image for you to use, a kubernetes deployment template, or you can host it on Heroku, or you can host it on your own server. It's up to you.

# Getting started

### 1. Create a MongoDB database

The easiest way to start is to get a free database from MongoDB Atlas. They have a generous free tier which comes with 512MB of storage. And you can get one an overview of their managed services and get started [here](https://www.mongodb.com/pricing).

### 2. Deploy storywise

You can choose from a whole host of options to deploy storywise. Some easy options are:
- [fly.io](https://fly.io/) - free resource allowance which "includes enough usage per month to run a small full-stack app, full-time, for free"
- [render.com](https://render.com/) - free tier which (called "Individual") which comes with enough resources to run various workloads for free
- [railway.app](https://railway.app/) - similar to render.com, free tier which comes with enough resources to run various workloads for free
- Container based - either docker or kubernetes


# License

Storywise is licensed under the GPL-3.0 License. See [LICENSE](LICENSE.md) for the full license text.
