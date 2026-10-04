# decodo review: Real Pricing, the Refund and Trial Catch, and a Cheaper Pay-Per-IP Option for Scraping

People searching "decodo review" usually aren't looking for a company history. They have a scraper, a rank tracker, or a batch of accounts that keeps getting blocked. Decodo showed up on some comparison list, and now they want three things: what it actually costs, whether it holds up on real targets, and whether there's a cheaper way to get the same job done.

That's what this covers. Decodo's current numbers, the two policy details that decide whether the trial is worth taking, and a second provider (9Proxy) that bills on a completely different basis. That last part matters more than it sounds, because Decodo's model and 9Proxy's model get expensive in opposite situations.

## What Decodo is now, in one paragraph

Decodo is the rebranded Smartproxy. Same company, same proxy pool, new name and a wider product range. That rebrand is why so much search traffic still lands on stale information: plenty of comparison sites and older reviews still list Smartproxy-era rates, including a $12.50-per-gigabyte figure that hasn't reflected the actual pricing page in a long time. If a review quotes residential at $12.50/GB, you're reading an old page.

The current pitch is 125M+ IPs across 195+ locations, covering residential, ISP (static residential), mobile, and datacenter proxies, plus a Site Unblocker and per-request scraping APIs. The company is registered in Lithuania, publishes GDPR-facing privacy documentation, holds an ISO/IEC 27001:2022 certificate, and is a member of the Ethical Web Data Collection Initiative, which is the part PCMag interviewed them about at length. Residential IPs come from opted-in users through partner apps rather than from scraped or compromised devices.

For anything you point at a hardened target, the sourcing question is not academic. It's the difference between a pool that passes IP reputation checks and one that gets flagged on request three.

## What Decodo actually costs

The pricing page splits into six product lines, and only one of them is the one most people searching for a review care about. All figures are in USD and exclude VAT.

### Residential proxies: the tiers most buyers click

| Package | Rate | Monthly cost |
| --- | --- | --- |
| Pay as you go | $4.00/GB | per gigabyte, no commitment |
| 3 GB | $3.75/GB | $11.25 |
| 10 GB | $3.50/GB | $35.00 |
| 25 GB | $3.25/GB | $81.25 |
| 50 GB | $3.00/GB | $150.00 |
| 100 GB | $2.75/GB | $275.00 |
| Enterprise 250 GB | $2.50/GB | $625.00 |
| Enterprise 1 TB | $2.00/GB | $2,000.00 |

The headline "from $2/GB" on the residential page is the Enterprise rate. The smallest card a normal buyer can click is 3 GB for $11.25, which is $3.75 per gigabyte. That gap is normal in this category, but budget from the table, not the banner.

Targeting at city, ZIP code, and ASN level is included on every residential plan rather than sold as an upgrade, which is genuinely useful for ad verification and local SERP checks.

### The other product lines

- **Static residential (ISP):** from $0.27 per IP, though that figure reflects traffic-based access. Dedicated ISP addresses, which is what most buyers actually want for long-lived sessions, run roughly $2.70 to $3.33 per IP at smaller bundle sizes.
- **Mobile:** from $2.25/GB across the carrier pool.
- **Datacenter:** from $0.02 per IP or around $0.45/GB for shared. Cheap by any standard.
- **Site Unblocker:** from $0.95 per 1,000 requests, handling rotation and CAPTCHA handling for you.
- **Web Scraping API and Fast Search API:** billed per 1,000 requests, with a free tier that doesn't require a card.

## Two details the pricing page doesn't lead with

**The trial and the money-back guarantee are effectively either/or.** Decodo offers a three-day trial with 100MB of traffic, and a 14-day money-back guarantee on paid plans. Decodo's own refund terms list "you haven't used a 3-day free trial" as a condition, so taking the free 100MB gives up your refund window. The trial also requires a payment method and auto-activates whichever plan you selected unless you cancel first.

The refund itself carries more conditions on top: first purchase only, request inside 14 days, and under 20% of traffic used on a regular plan. Worth reading before you click, not after.

**Bandwidth is tied to the billing cycle.** Subscription gigabytes don't sit in your account waiting for a quiet month. If your workload is lumpy, a project-based test, or seasonal, that's a real cost. Don't assume otherwise for any subscription-priced proxy provider.

## Where Decodo earns the praise it gets

Two things are consistently true across independent testing.

AIMultiple benchmarked per-GB proxy pricing from 10 GB to 10 TB and found Decodo the cost-efficiency leader at every volume tested, and rated its residential product's success rate near the top of the field. Proxyway has given it a Best Value nod five years running, and G2 handed it a Best Usability award. TechRadar's updated review describes the residential pool's uptime and speed as excellent and calls the dashboard straightforward enough to set up without hair-pulling.

The honest counterpoints from the same tests: Decodo's response times are competitive rather than fastest, datacenter performance is respectable but not category-leading, and social scraping on Facebook and Instagram lags the specialised scraping providers. PCMag noted the pay-as-you-go mechanics are a little confusing, since the wallet tops up in whole dollars and you end up paying $4 rather than the $3.50 the page lists for a single gigabyte.

## Where Decodo stops making sense

The pool and the platform are the reasons to choose Decodo. Price per gigabyte at low volume is the reason not to.

A solo project moving a few gigabytes a month pays $3.75+ per gigabyte on Decodo. A team burning hundreds of gigabytes through a single long-lived IP is paying for traffic it doesn't need to meter at all, and Decodo's per-gigabyte model has no answer for that workload. Mobile is the same story at $2.25/GB entry, well above what per-IP billing gives you when bandwidth, not IP count, is the constraint.

So if your workflow is "a modest number of sticky IPs doing heavy, unpredictable traffic," the pricing structure you want is pay-per-IP with unlimited bandwidth. Which is exactly the structure 9Proxy sells.

## The alternative worth pricing against Decodo: 9Proxy

9Proxy runs a residential pool of 20M+ IPs across 90+ countries. Smaller than Decodo's advertised 125M, and it has no scraped-API layer or Site Unblocker equivalent. What it does differently is billing, and the two models are the source of the savings.

**Residential by IPs.** You buy a block of IPs, you get unlimited bandwidth through each of them, and unused IPs never expire. Each IP lives naturally from a few hours up to about 24 hours. There's no automatic rotation built in; rotation is handled through an Auto Rotation Proxy that switches IPs at intervals you set on selected ports. This model needs the 9Proxy desktop app, which forwards local ports to the pool.

**Residential by GB.** You buy traffic instead of IPs, generate unlimited proxy endpoints, and rotate per request or hold sticky sessions. Authentication is username/password or IP whitelisting, and it all runs from the dashboard with no app. Purchased traffic is valid for 180 days rather than a single month, which is the practical difference from a monthly subscription if your usage arrives in bursts.

Both models support HTTP/HTTPS and SOCKS5, targeting by country, state, city, ZIP, and ISP, and city/state-level geo-matching. The pool is a frequent pairing with antidetect browsers, which is where most of its reviews come from.

[👉 See 9Proxy's residential packages and current per-IP rates](https://bit.ly/9-Proxy)

## 9Proxy pricing: every package on the rate card

These are the published tiers in USD. The company adjusted residential pricing once, so verify against the live page before you commit. Everything below was reached through the link in this article, which carries a referral code.

### Residential by IPs (unlimited bandwidth, IPs don't expire)

| Package | Price | Rate per IP | Get it |
| --- | --- | --- | --- |
| 100 IPs | $24 | $0.24/IP | [ 100 IP package](https://bit.ly/9-Proxy) |
| 500 IPs | $72 | $0.144/IP | [ 500 IP package](https://bit.ly/9-Proxy) |
| 1,000 IPs (+500 bonus) | $126 | $0.084/IP | [ 1,500 IP package](https://bit.ly/9-Proxy) |
| 2,500 IPs | $210 | $0.084/IP | [ 2,500 IP package](https://bit.ly/9-Proxy) |
| 5,000 IPs | $360 | $0.072/IP | [ 5,000 IP package](https://bit.ly/9-Proxy) |
| 15,000 IPs | $720 | $0.048/IP | [ 15,000 IP package](https://bit.ly/9-Proxy) |
| 25,000 IPs | $863 | $0.035/IP | [ 25,000 IP package](https://bit.ly/9-Proxy) |
| 50,000 IPs | $1,438 | $0.029/IP | [ 50,000 IP package](https://bit.ly/9-Proxy) |
| 100,000 IPs | $2,300 | $0.023/IP | [ 100,000 IP package](https://bit.ly/9-Proxy) |
| 500,000 IPs | $8,625 | $0.018/IP | [ 500,000 IP package](https://bit.ly/9-Proxy) |

### Residential by GB (180-day validity, unlimited endpoints)

| Package | Price | Rate per GB | Get it |
| --- | --- | --- | --- |
| 5 GB | $15 | $3.00/GB | [ 5 GB plan](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $105 | $2.10/GB | [ 55 GB plan](https://bit.ly/9-Proxy) |
| 100 GB | $150 | $1.50/GB | [ 100 GB plan](https://bit.ly/9-Proxy) |
| 200 GB | $200 | $1.00/GB | [ 200 GB plan](https://bit.ly/9-Proxy) |
| 1,000 GB | $800 | $0.80/GB | [ 1,000 GB plan](https://bit.ly/9-Proxy) |
| 2,000 GB | $1,500 | $0.75/GB | [ 2,000 GB plan](https://bit.ly/9-Proxy) |
| 10,000 GB | top volume rate | $0.68/GB | [ 10,000 GB plan](https://bit.ly/9-Proxy) |

### Bundles and Enterprise

| Package | Price | What's included | Get it |
| --- | --- | --- | --- |
| Starter bundle | $30 | 100 IPs + 5 GB | [ Starter bundle](https://bit.ly/9-Proxy) |
| Popular bundle | $180 | 1,500 IPs + 50 GB | [ Popular bundle](https://bit.ly/9-Proxy) |
| Pro bundle | $720 | 5,000 IPs + 500 GB | [ Pro bundle](https://bit.ly/9-Proxy) |
| Enterprise | custom pricing | Unlimited traffic validity, 1 owner + up to 5 members, per-member traffic controls, full activity logs, dedicated support | [ Enterprise plan](https://bit.ly/9-Proxy) |

Two things stand out in that card. The 100 GB GB-tier at $150 works out to $1.50 per gigabyte, where Decodo charges $275 for the same 100 GB. And the entry IP package, 100 IPs for $24 with unlimited traffic, has no equivalent on Decodo at all.

## How the two billing models actually differ

|  | Decodo | 9Proxy |
| --- | --- | --- |
| Pool | 125M+ IPs, 195+ locations | 20M+ IPs, 90+ countries |
| Residential billing | Per GB, monthly | Per IP (unlimited bandwidth) or per GB |
| Unused balance | Tied to the monthly cycle | IPs never expire; GB plans valid 180 days |
| Targeting | Country, state, city, ZIP, ASN | Country, state, city, ZIP, ISP |
| Protocols | HTTP(S), SOCKS5 | HTTP(S), SOCKS5 |
| Extras | Site Unblocker, scraping APIs, browser extensions, proxy checker | Desktop app, Proxy2Web, ProxyHub, public API |
| Free trial | 3 days / 100MB (voids the refund) | Limited trials subject to availability, no standard self-serve option |
| Refunds | 14-day money-back, conditions apply | Instant credit for proxies that fail inside roughly 60 seconds |

Read that as a division of labour rather than a ranking. Decodo wins when you need the largest possible pool, the widest geography, static ISP addresses at scale, or a managed scraping API so you don't have to build your own block handling. 9Proxy wins when bandwidth is the variable that keeps breaking your budget, when you want residential traffic cheaper per gigabyte, or when you'd rather buy IPs once and not watch an expiry date.

A concrete example of the split: a price-monitoring pipeline running 5,000 IPs with heavy page loads runs $360 on 9Proxy's IP tier, because traffic is unmetered. The same workload metered at Decodo's 100 GB rate is $275 for 100 GB, and the moment you're pulling a few hundred gigabytes of JavaScript-heavy pages a month, the metered side of that comparison gets ugly fast. Flip it around and someone who needs 50 GB of traffic and 10 IPs is better served by Decodo's $150 tier than by buying 100 IPs to get the same traffic.

## Before you buy either one

**For Decodo,** decide up front whether you want the trial or the guarantee, because you can't have both. Testing whether proxies connect and authenticate is a job the free 100MB covers comfortably. Testing whether the pool survives a real hardened target is not, and that's better judged through the refund window on the 3 GB plan.

**For 9Proxy,** the policy worth understanding is the refund mechanism. It's an instant credit for proxies that fail within about 60 seconds, which is narrow by design: it covers a dead proxy, not a plan that turned out to be wrong for your workload. There's also no standard self-serve free trial on the website; the company has said in community posts that limited trials exist for new users subject to availability, which is a different thing from a trial button.

The per-IP model has its own expectation to set. Residential IPs drop naturally after a few hours up to around 24, so plan for replacements rather than assuming a permanent address. Auto-refresh detects and swaps offline IPs within about 60 seconds, and the Today List lets you reuse any IP from the previous 24 hours at no extra cost, which is where the vendor's 20 to 30 percent savings claim comes from on repeated tasks. Independent testing of the network put success rates in the mid-to-high 90s against Cloudflare-protected targets, though that's one reviewer's methodology, not a guarantee for your target list. Note too that 9Proxy's terms restrict high-abuse use cases such as sneaker copping and gaming.

[👉 Create a 9Proxy account and check the current package list](https://bit.ly/9-Proxy)

## Common questions about decodo review searches

**Is Decodo the same as Smartproxy?**
Yes. Decodo is the new brand name for Smartproxy, same Lithuanian company and the same proxy infrastructure. Reviews published under smartproxy.com URLs describe the same service, but any pricing in them predates the current rates.

**Is Decodo cheap?**
At scale, yes. AIMultiple rated it the cost-efficiency leader from 10 GB to 10 TB. At a few gigabytes a month, no, the entry rate is $3.75 per gigabyte, and per-IP providers are usually cheaper for that shape of workload.

**Does Decodo have a free trial?**
Yes, 100MB over three days on most eligible products, with a payment method required and automatic activation of your chosen plan when it ends. Using it removes your eligibility for the 14-day money-back guarantee.

**What's the cheaper alternative to Decodo for residential proxies?**
On a per-gigabyte basis at mid volumes, 9Proxy: 100 GB at $150 against Decodo's $275 for the same 100 GB. On raw pool size and product breadth, nothing here beats Decodo. Pick based on whether your constraint is IP coverage or bandwidth.

**Can I use 9Proxy without the desktop app?**
Yes, on the GB-based residential plans. Those work straight from the dashboard with username/password or IP whitelisting. The per-IP model requires the desktop app for local port forwarding.

## The short version

Decodo is a well-built platform with a big pool, honest benchmarking behind its reputation, and a pricing structure that rewards volume. If you're running an enterprise-scale data operation or you need 195 locations and managed scraping, it's a defensible choice and the refund window lets you validate it properly.

If what you actually need is residential traffic without a meter running, or IPs that don't expire at the end of the month, compare it against 9Proxy before you buy. The 100 GB tier comparison alone is worth the five minutes.

[👉 Compare 9Proxy's per-IP and per-GB plans here](https://bit.ly/9-Proxy)
