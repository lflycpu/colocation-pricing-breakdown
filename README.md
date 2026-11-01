# colocation hosting: real prices from $35 a month, what's actually bundled, and how to pick between five data centers

Colocation hosting means you own the server, ship it to a provider's data center, and pay monthly for the space, power, cooling, and bandwidth it consumes. The provider keeps the building running; you keep the hardware and everything on it. It sits somewhere between renting a dedicated server and running your own machine room, and for a specific group of buyers — people who already own hardware, or who need physical control of it — it's usually the cheapest serious option on the menu.

Sharktech is one of the providers making that option unusually cheap right now. The company has been around since 2003, runs its own network (AS46844), and operates five data center locations: Los Angeles, Las Vegas, Denver, Chicago, and Amsterdam, housed in facilities from Equinix, CoreSite, H5 Data Centers, and Crown Castle. Its 1U colocation starts at $35/month in Chicago, and every tier ships with DDoS protection bundled in rather than sold as an add-on.

> **Quick take:** If you just need a single server or a small footprint online, Sharktech's 1–6U plans are the sensible entry point — $35/month in Chicago, $65 in Las Vegas or Denver, $99 in Los Angeles or Amsterdam, all with 10Gbps–100Gbps ports, at least 300TB of transfer, 200–1200W of power, and free setup. 👉 [check current colocation pricing across all five locations](https://bit.ly/SharKtech) before deciding, since availability and final configuration depend on the site you pick.

## What colocation actually costs at Sharktech

Sharktech sells space in two standard sizes at each location, plus custom builds in between. Here's the full picture as currently published — all prices are monthly, in USD, and are "starting at" figures because power and bandwidth scale with the package you configure:

| Location | 1–6U footprint | 10–42U footprint | Power range | Buy |
| --- | --- | --- | --- | --- |
| Chicago | from **$35/mo** | from $280/mo | 200–1200W (small) / 1600–5500W (large) | [ Order Chicago colocation](https://bit.ly/SharKtech) |
| Las Vegas | from $65/mo | from $520/mo | 200–1200W / 1600–5500W | [ Order Las Vegas colocation](https://bit.ly/SharKtech) |
| Denver | from **$35/mo** | from $280/mo (premium tier $520) | 200–1200W / 1600–5500W | [ Order Denver colocation](https://bit.ly/SharKtech) |
| Los Angeles | from $99/mo | from $792/mo | 200–1200W / 1600–5500W | [ Order Los Angeles colocation](https://bit.ly/SharKtech) |
| Amsterdam | from $99/mo | from $792/mo | 200–1200W / 1600–5500W | [ Order Amsterdam colocation](https://bit.ly/SharKtech) |

Three things to know about these numbers before you plan around them:

- They're entry prices for the space tier. Your actual bill depends on the power draw and port speed you configure in the customer portal, and Sharktech shows installation and remote-hands charges there before you commit.
- Anything between 6U and a full rack — or a private cage — gets a custom quote from the sales team rather than a fixed price. If your needs fall in that gap, you'll be talking to a human either way.
- Setup is free on the standard plans. There's no separate non-recurring installation fee to budget for, which matters more than it sounds because some providers charge several hundred dollars to rack your gear.

If you need something bigger than 6U but aren't sure a full 42U rack makes sense yet, it's worth getting the custom quote — over-buying a rack for two or three machines is money that could sit in better hardware instead. 👉 [request a colocation quote or start configuring](https://bit.ly/SharKtech) and you'll see the per-site options before anything ships.

## What's actually included (and why the DDoS line item matters)

Every Sharktech colocation plan, from 1U up to full racks and cages, includes DDoS protection at no extra charge — 40Gbps of mitigation by default, upgradeable to 100Gbps. The company's network is built around this capability; its standard protection runs at 60Gbps across the product line and can scale to 1Tbps for high-risk environments.

This is worth pausing on, because in the broader market DDoS protection is frequently a paid add-on, often around $50/month or more for meaningful capacity. When your monthly bill is $35, a mandatory $50 security add-on would double it. Here it's part of the base price.

The rest of the standard package:

- **Network**: 10Gbps to 100Gbps ports on a multi-100-Gigabit redundant backbone, with at least 300TB of monthly transfer on the standard tiers. Intelligent routing monitors jitter, packet loss, and latency, and shifts traffic to the best path in real time.
- **Power**: 200–1200W on the small tier, 1600–5500W on rack plans, with fully redundant power in all facilities.
- **Support**: 24/7 on-site technical staff. The scope of remote-hands work (reboots, visual checks, hands-on interventions) is agreed with the team, and per-incident charges are visible in the portal before you order.
- **Uptime target**: 99.99%.

For context on where these prices sit against the market: industry benchmarking from QuoteColo puts typical US 1U colocation at $120–$140/month in Chicago, roughly $120–$240 in Los Angeles and Ashburn, and $50–$100 even in cheaper secondary markets like Phoenix. Against those ranges, $35 in Chicago or Denver and $65 in Las Vegas are well below what the same footprint costs elsewhere, and the $99 tier in LA, Chicago, and Amsterdam lands at the bottom of those markets' usual bands.

There's a macro reason for the gap. CBRE reported the average US colocation rate at $195.94/kW/month for the second half of 2025, closer to $250/kW once power delivery and cooling are included, and North American data center vacancy hit a record low of 1.4% at the end of 2025. Supply is tight and prices are climbing across the industry. That makes the low end of Sharktech's range look like a deliberate land grab — and also a reason not to assume it lasts forever.

## Which location should you pick?

The five sites aren't interchangeable, and the price differences reflect real network geography rather than arbitrary tiers.

**Chicago ($35/mo)** is the budget pick for US-central deployments. If price is your main constraint and your users are spread across North America, this is the default answer.

**Denver ($35/mo, $65 mid-tier)** shares the lowest price bracket and sits in a geographically stable region with low natural-disaster risk, which makes it a common pairing site for disaster recovery — your primary in one metro, your DR node in Denver.

**Las Vegas ($65/mo)** splits the difference and covers the Southwest well.

**Los Angeles ($99/mo)** is close to One Wilshire, one of the most interconnected buildings on the West Coast. If your traffic is Asia–US, or you're running CDN edge nodes and latency-sensitive cross-Pacific applications, the extra $64/month over Chicago buys you network proximity you can't get inland.

**Amsterdam ($99/mo)** serves EU/EMEA traffic, European peering, and GDPR-adjacent data residency needs. European users on US-hosted infrastructure notice the difference immediately.

A practical rule: pick by where your users and your network peers are, then let price break ties. Picking by price alone and then routing European users to a Chicago box is a false economy at 100ms of added latency.

## How ordering works, and where people slip up

The deployment process has a specific sequence, and skipping a step is how hardware ends up on a truck with nowhere to land:

1. **Choose a location** based on users, partners, and network requirements.
2. **Specify your footprint** — rack units, power draw, port speed, and expected growth. Growth matters; ordering 1U when you know a second server is coming in six months means a second setup conversation later.
3. **Configure in the customer portal.** Space, power, and connectivity are selected there, and the portal shows installation fees and remote-hands rates before checkout.
4. **Coordinate shipping.** This is the step people forget: you arrange shipment and installation requirements with Sharktech *before* sending equipment, so the rack space, power, and ports are ready when the box arrives.

The portal-first approach also protects you from the most common billing surprise. Remote-hands interventions beyond the agreed scope are charged per incident — industry-wide, that typically runs $2–$4 per minute — so checking the rate schedule before you need a 3 a.m. hands-on visit is five minutes well spent.

One more thing worth knowing before you buy: Sharktech's Trustpilot rating sits at 3.5/5 across 13 reviews. The complaints that show up tend to concern early support hiccups and the no-refund policy rather than uptime or DDoS performance — so treat the first invoice as final and size your commitment accordingly. On the other side of the ledger, a LowEndTalk user ran a year-long series of DDoS tests and reported that "Sharktech successfully stopped every attack thrown at them," and Dingdian Network, a game server company, states that despite repeated 3–8Gbit attacks their servers "never skip a beat."

## When colocation is the wrong answer

Honest assessment time, because colocation isn't for everyone and the upfront reality filters people out fast.

You need hardware you already own or are prepared to buy. Colocation gives you a home for your equipment — it doesn't provide the server. If you're starting from zero and just need compute, buying hardware plus colocation usually only beats renting when you're running it for years or need dozens of machines. An Intel Xeon E3-1270v5 with 16GB RAM and 2TB of storage, the kind of box that anchors Sharktech's own $99/month dedicated server promos, costs several hundred dollars up front — capital you skip entirely if you rent instead.

You need time and skills to manage it. The provider handles the building; you handle the operating system, the applications, hardware failures, and spares. If nobody on your team can swap a failed DIMM or troubleshoot a NIC, factor in travel or remote-hands costs for every physical intervention.

If either of those describes you, renting is the better path, and Sharktech covers that too. Its dedicated bare-metal servers include free setup, a /29 IPv4 allocation, free IPv6, and the same DDoS-protected network, with in-stock configurations from $189/month and promotional single-CPU servers at $99/month. Its cloud hosting starts around $39/month for a small instance with hourly and monthly billing, and the company offers a cloud cost calculator that breaks compute, storage, and transfer estimates per plan. There's no link to the cloud calculators here because the point is simpler: if you don't need to own the metal, don't pay to house it.

One gap to flag for hardware owners: Sharktech's published colocation plans start at the 1U tier. If you need a few rack units of cabinet space with custom power and multi-site redundancy, that's a sales conversation, not a cart checkout — fine for most, slower if you wanted instant provisioning.

## Frequently asked questions

**What's the cheapest 1U colocation in the US right now?** Sharktech's Chicago and Denver plans start at $35/month with 10Gbps–100Gbps connectivity, 300TB+ of transfer, and free setup. That undercuts the typical Chicago market range of $120–$140/month reported by QuoteColo, and even undercuts the $50–$100 range of traditionally cheap secondary markets.

**Is DDoS protection included with colocation?** Yes. Every tier includes 40Gbps of DDoS mitigation at no extra charge, upgradeable to 100Gbps. Given that comparable protection is often a $50/month add-on elsewhere, this is the single biggest line-item difference versus competitors.

**Do I need to provide my own server?** Yes. Colocation means you own the hardware and rent the space, power, cooling, and network around it. If you want the provider to supply hardware, dedicated servers or cloud plans are the relevant products instead.

**Can I get a half rack or a private cage?** Full racks (10–42U) are listed at $280–$792/month depending on location. Anything in between 6U and a full rack, or a private cage, requires a custom quote — Sharktech quotes these builds individually rather than forcing intermediate needs into a fixed tier.

**What's the uptime commitment?** Sharktech targets 99.99% uptime on its colocation plans, backed by fully redundant power, cooling, and network in all five facilities.

## Choosing at a glance

Still on the fence? Match your situation to the price:

- **Single server, budget priority** → 1–6U in Chicago or Denver at $35/month. This is the strongest price-to-included-features ratio in the lineup.
- **Single server, West Coast or Asia–Pacific traffic** → Los Angeles at $99/month, justified by proximity to One Wilshire.
- **EU users or data residency requirements** → Amsterdam at $99/month.
- **Disaster recovery node** → Denver at $35/month, paired with your primary in another metro.
- **Rack-scale deployment** → 10–42U from $280/month in Chicago or Denver; $792 in LA or Amsterdam.
- **No hardware yet** → skip colocation and rent a dedicated server or cloud instance instead.

Whichever camp you're in, the sensible last step is the same: 👉 [compare the current colocation configurations for all five locations](https://bit.ly/SharKtech), confirm power and port options for your hardware in the portal, and check the remote-hands rates before your equipment ships — that's the whole list of things to verify, and it takes less time than buying the server did.
