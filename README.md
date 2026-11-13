# Unmetered Bandwidth VPS: What the Label Hides, Which Port Speed You Need, and What It Costs (Full Plan Table + 6-Point Checklist)

Unmetered bandwidth on a VPS means the provider does not meter your monthly transfer and does not bill you for going over. It does not mean unlimited throughput. Every plan still has a port speed ceiling, and on most plans that ceiling decides whether the server is usable for your workload.

JustHost is unusual in printing the ceiling next to the price: 10 Mbps on the $1.99 plan, 100 Mbps from $3.05, up to 750 Mbps on the top tiers, every one labelled fair-share. That makes its lineup a good place to learn how to read the label. Below you get the full plan list with prices, the arithmetic that turns port speed into monthly terabytes, and six questions that separate a genuinely unmetered plan from a marketing one.

> **Quick picks from the JustHost lineup**
> - **One small site, a VPN node, an uptime checker:** 1 core / 1 GB RAM / 20 GB NVMe / 300 Mbps fair-share, from **$2.25/mo on a 12-month term** (listed as Sirius Special; the same spec appears as Sirius on the all-tariffs page at $3.88 on 12 months).
> - **Several sites or a few containers:** 2 cores / 4 GB / 80 GB NVMe / 500 Mbps, from **$6.23/mo on 12 months** (Vega Special; Vega itself lists at $10.75).
> - **File or media delivery:** 4 cores / 8 GB / 200 GB NVMe / 750 Mbps, from **$12.96/mo on 12 months** (Yildun Special).
> - **Skip the $1.99 Promo plan** unless roughly 4 TB of monthly transfer at 10 Mbps is genuinely all you need.
>
> 👉 Check the current JustHost VPS tariffs and port speeds

## What does "unmetered bandwidth" actually mean on a VPS?

It means three different things depending on who is selling it, and only one of them is close to what most buyers assume.

OVHcloud states the definition plainly: the volume of data transferred is not measured and has no limit, so your monthly cost is fixed. The same page also states that network speed is capped by the plan you bought, between 250 Mbps and 2 Gbps on its international lineup, and its UK page lists 500 Mbps on VPS-1 rising to 3 Gbps on VPS-4. OVHcloud even carves out a regional exception: VPS instances in Mumbai, Singapore and Sydney carry a set monthly quota, and past it bandwidth drops to 10 Mbps. Unlimited volume, capped rate, and a geographic asterisk, all in one product.

Cloudfanatic uses a softer phrase, "unmetered fair share network", and says the point is no overage charges and no suspension for exceeding an allocation. SBServers splits the two numbers apart entirely: "25Gbps unmetered ports with 1Gbps - 2Gbps guaranteed". That wording tells you the port can burst far above what you are guaranteed to receive at a busy moment.

Three questions follow from those three examples, and they apply to any provider: is the traffic metered, what is the port speed, and is there a guaranteed rate or a fair-use clause behind the word "unmetered".

## JustHost unmetered VPS plans and prices

Every plan below runs KVM, includes IPv4 + IPv6, and carries an "unmetered port" that JustHost labels fair-share. Prices are in USD. The monthly figure is the headline rate; the second price applies when you pay for 12 months.

| Plan | vCPU / RAM / NVMe | Unmetered port (fair-share) | Monthly | 12-month term | Order |
| --- | --- | --- | --- | --- | --- |
| VPS Promo | 1 / 512 MB / 5 GB | 10 Mbps (~4+ TB/mo) | $1.99 | — | [ Order VPS Promo](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 / 1 GB / 10 GB | 100 Mbps (~31+ TB/mo) | $3.81 | $3.05 | [ Order New Star](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Sirius | 1 / 1 GB / 20 GB | 300 Mbps (~93+ TB/mo) | $4.85 | $3.88 | [ Order Sirius](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 / 2 GB / 30 GB | 300 Mbps (~93+ TB/mo) | $6.92 | $5.53 | [ Order Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Double Star | 2 / 2 GB / 20 GB | 200 Mbps (~62+ TB/mo) | $7.08 | $5.67 | [ Order Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Alpha Centauri | 2 / 2 GB / 40 GB | 400 Mbps (~124+ TB/mo) | $8.99 | $7.19 | [ Order Alpha Centauri](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Bright Star | 4 / 4 GB / 30 GB | 300 Mbps (~93+ TB/mo) | $9.80 | $7.84 | [ Order Bright Star](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Vega | 2 / 4 GB / 80 GB | 500 Mbps (~155+ TB/mo) | $13.44 | $10.75 | [ Order Vega](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 / 4 GB / 120 GB | 750 Mbps (~232+ TB/mo) | $18.30 | $14.64 | [ Order Capella](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |

The 12-month column reflects the 20% discount JustHost shows on the pricing page. New Star, Double Star and Bright Star carry an extra condition: that rate is available when you order three months or more.

The VPS landing page lists a second, cheaper set of plans under "Special offers". Where the specs match a tariff from the table above, the Special price is lower.

| Special offer | vCPU / RAM / NVMe | Unmetered port (fair-share) | Monthly | 12-month term | Order |
| --- | --- | --- | --- | --- | --- |
| Sirius Special | 1 / 1 GB / 20 GB | 300 Mbps | $2.81 | $2.25 | [ Order Sirius Special](https://justhost.asia/?ref=196392) |
| Arcturus Special | 1 / 2 GB / 30 GB | 300 Mbps | $4.01 | $3.21 | [ Order Arcturus Special](https://justhost.asia/?ref=196392) |
| Vega Special | 2 / 4 GB / 80 GB | 500 Mbps | $7.79 | $6.23 | [ Order Vega Special](https://justhost.asia/?ref=196392) |
| Yildun Special | 4 / 8 GB / 200 GB | 750 Mbps | $16.20 | $12.96 | [ Order Yildun Special](https://justhost.asia/?ref=196392) |
| Betelgeuse Special | 6 / 12 GB / 400 GB | 750 Mbps | $26.40 | $21.12 | [ Order Betelgeuse Special](https://justhost.asia/?ref=196392) |
| Altair Special | 8 / 24 GB / 600 GB | 750 Mbps | $47.40 | $37.92 | [ Order Altair Special](https://justhost.asia/?ref=196392) |

Two pages, two prices, same configuration in at least one case: Sirius is $4.85 monthly on the all-tariffs page and Sirius Special is $2.81 on the landing page. Treat the Special block as promotional pricing and confirm which number the order form shows before you pay.

The same landing page also sells a configurable line with HDD, SSD or NVMe storage from $2.60/mo on a 12-month term. That listing does not state a port speed, so ask support whether unmetered applies before you assume it does.

👉 Open the JustHost VPS page with the Special offer pricing

## Port speed is the number that decides whether a plan fits

JustHost converts each port into a monthly figure, and the arithmetic is worth internalising: 10 Mbps saturated for 30 days moves a little over 3 TB, which is why the Promo plan is described as "4+ TB". Scale from there. 100 Mbps is about 31 TB, 500 Mbps about 155 TB, 750 Mbps about 232 TB.

Now compare that to what a normal site uses. Fifty thousand pageviews at 1 MB per page is 50 GB, or roughly 1.5% of what a 100 Mbps port can move in a month. For blogs, small shops and APIs, bandwidth stopped being the constraint years ago, and buying a bigger port changes nothing.

Port speed starts to matter in four cases: video or audio streaming, large file downloads, backup and replication targets, and VPN or proxy endpoints serving many users. If you are in one of those, you also need to check the CPU and disk, because a fast port attached to a weak server delivers nothing. Cloudfanatic makes the point on its own product page: a 10 Gbps pipe is meaningless if the CPU cannot keep up. SBServers demonstrates the mismatch from the other direction, pairing a 25 Gbps port with 1 vCPU and 1 GB of RAM on its £4 plan.

JustHost's ladder is more balanced, with port speed generally rising alongside cores and RAM. The exception is worth knowing: Bright Star gives you 4 cores and a 300 Mbps port for $9.80, while Vega gives you 2 cores and 500 Mbps for $13.44. Buy Bright Star for compute and Vega for throughput, and don't pay for 750 Mbps unless you are actually pushing files.

## Six questions to ask before you buy an unmetered bandwidth VPS

| Question | Why it changes the decision | What providers actually do |
| --- | --- | --- |
| What is the port speed? | Unmetered covers volume, not rate. The port is your ceiling. | JustHost publishes 10 to 750 Mbps by plan. OVHcloud publishes 500 Mbps to 3 Gbps on its UK lineup. |
| Is any of that speed guaranteed? | A shared 25 Gbps port can deliver less at peak than a guaranteed 1 Gbps. | SBServers sells 25 Gbps ports with 1 to 2 Gbps guaranteed. Cloudfanatic sells "fair share". |
| What does the fair-use clause allow? | Sustained saturation is the usual trigger for throttling. | JustHost and Cloudfanatic both label their ports fair-share, which means shared capacity rather than a dedicated pipe. |
| Does the region carry a quota? | Some plans are only unmetered in certain datacentres. | OVHcloud's Mumbai, Singapore and Sydney VPS carry a monthly quota, then a 10 Mbps cap. |
| Is DDoS filtering included? | It is the feature most often quoted as a paid extra. | OVHcloud includes it on every VPS. Space Hosting includes it by default. SBServers still lists it as coming soon. |
| Past the limit, throttle or invoice? | Sets your worst-case bill. | OVHcloud's regional quota throttles to 10 Mbps. Cloudfanatic states no overage charges and no suspension. |

On the DDoS question, JustHost's VPS page says servers are protected against "the main types of DDoS attacks" without publishing which layers or what attack size is covered. If you expect to be a target, get that in writing from support before ordering.

## What unmetered VPS costs elsewhere

Two verified reference points, both in GBP, and neither is JustHost.

OVHcloud's UK VPS range runs £3.31 ex VAT (£3.97 incl. VAT) for VPS-1 with 2 vCores, 4 GB RAM, 40 GB NVMe and a 500 Mbps port; £6.29 (£7.55) for VPS-2 with 4 vCores, 8 GB, 75 GB and 1 Gbps; £9.01 (£10.81) for VPS-3 with 6 vCores, 12 GB, 100 GB and 2 Gbps; £17.34 (£20.81) for VPS-4 with 8 vCores, 24 GB, 200 GB and 3 Gbps. All four advertise unlimited traffic, a daily backup of the previous 24 hours, a 99.9% SLA and anti-DDoS included.

SBServers sells KVM VPS in Romania, Italy, Austria, Germany and the Netherlands from £4/mo for 1 vCPU, 1 GB RAM and 50 GB NVMe, up to £32/mo for 6 vCPU, 8 GB and 400 GB, all on 25 Gbps unmetered ports with 1 to 2 Gbps guaranteed.

Put next to those, JustHost's floor is lower. The $2.25 to $2.81 entry pricing undercuts OVHcloud's cheapest UK plan, but OVHcloud's entry plan brings 4 GB of RAM and a 500 Mbps port at that price. Specs per unit of currency favour OVHcloud at the bottom of the range; absolute entry cost favours JustHost. Converting GBP to USD before comparing matters, and OVHcloud is one of the few providers that shows both ex-VAT and incl-VAT prices, which makes the tax comparison possible at all.

## How to check the bandwidth you actually got

Do not use speedtest.net on a VPS. SBServers points out that its test nodes frequently have under 1 Gbps of capacity, so results say more about the test server than your port.

Use iperf3 against a public endpoint instead:


iperf3 -c ping.online.net -p 5201 -P 30


Run it outbound from the VPS, several times across different hours. A fair-share port will not hit its ceiling at peak, and that is normal rather than a fault. If throughput looks bad, check disk speed before blaming the network; a saturated NVMe array and a slow one produce very different results when you are serving files.

👉 Pick a JustHost plan with the port speed you actually need

## A note on JustHost reviews

Search for JustHost reviews and you will find detailed write-ups describing shared hosting plans called Basic, Plus and Choice Plus, a $19.99 VPS and a 30-day money-back guarantee. None of those plan names appear in the justhost.asia catalogue, which sells Promo, New Star, Sirius, Vega and the rest. Those reviews describe a different product line, so don't map their uptime figures or refund terms onto the VPS plans here. Ask support directly about the refund window and the billing terms that apply to your order.

## Which plan fits your workload

Match the port to your traffic type first, then buy the smallest CPU and RAM that runs your stack.

- **A single low-traffic site or a VPN node:** 300 Mbps is plenty. Sirius Special at $2.25 to $2.81, or Sirius at $3.88 to $4.85 if the Special is unavailable.
- **A dozen small sites, Docker containers, a staging box:** Vega Special at $6.23 to $7.79 buys 2 cores, 4 GB RAM, 80 GB NVMe and 500 Mbps.
- **Media, mirrors, backup targets:** Yildun Special at $12.96 to $16.20 for 750 Mbps and 200 GB of disk. Capella at $14.64 to $18.30 is the equivalent on the standard tariff.
- **Compute-heavy work with modest traffic:** Bright Star or Arcturus. Paying for 750 Mbps when your bottleneck is CPU is money spent on a number you will never see.

Before you pay, confirm two things: which price list the checkout applies (the Special block or the all-tariffs page), and whether the discounted rate requires the 12-month commitment. Both change what you actually pay.

👉 Compare JustHost's unmetered VPS plans and current prices
