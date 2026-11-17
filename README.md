# RackNerd locations: LA DC-02 or DC-03, which city fits your users, and which plan to buy (full location and price table)

The data center you pick at checkout is locked to that server for its whole life. There is no button that moves a live VPS from Amsterdam to Los Angeles, so the location decision has to happen before you pay, not after.

RackNerd runs roughly **20 data centers across 19 regions** in North America, Europe, and Asia, a figure the company gives for its own network in a November 2026 industry report. Its promotional KVM VPS tiers start at **$11.29/year** on deal listings, with dedicated servers from **$64.95/month**. The rest of this page is about picking the right city in that dropdown, because that choice affects your page speed more than the plan size does.

> **Quick pick**
> - Most of your visitors in mainland China, Japan, or Korea: **Los Angeles DC-02**, the Asia-optimized facility.
> - Western or Central Europe: **Amsterdam** first, **Frankfurt** if you specifically want DE-CIX peering.
> - Ireland, the UK, or transatlantic traffic: **Dublin** or **London**.
> - US East Coast: **New York, New Jersey, or Ashburn**. The gap between them is small enough that it rarely decides anything.
> - Unsure between two nearby cities: run a Looking Glass test before you order, not after.

👉 [Check current RackNerd VPS specials and choose your location](https://bit.ly/RacKnerd)

## The plans you're actually choosing between

These are the promotional KVM VPS tiers that show up on deal listings. Core counts for the 4 GB and 6 GB tiers differ between sources, so they're left out here and you should confirm them on the order form.

| Plan | RAM | Storage | Monthly transfer | Price (annual) | Order |
| --- | --- | --- | --- | --- | --- |
| KVM VPS 1 GB | 1 GB | 24 GB SSD | 2,000 GB | $11.29/yr | [ Order this plan](https://bit.ly/RacKnerd) |
| KVM VPS 2 GB | 2 GB | 40 GB SSD | 3,500 GB | $18.29/yr | [ Order this plan](https://bit.ly/RacKnerd) |
| KVM VPS 3.5 GB | 3.5 GB | 65 GB SSD | 7,000 GB | $32.49/yr | [ Order this plan](https://bit.ly/RacKnerd) |
| KVM VPS 4 GB | 4 GB | 105 GB SSD | 9,000 GB | $43.88/yr | [ Order this plan](https://bit.ly/RacKnerd) |
| KVM VPS 6 GB | 6 GB | 140 GB SSD | 12,000 GB | $59.99/yr | [ Order this plan](https://bit.ly/RacKnerd) |

Every tier includes a 1 Gbps port, full root access, one dedicated IPv4, KVM virtualization, and the ctrl control panel. VPS provisioning is instant, usually finished within 5 to 15 minutes of payment, and you can request a custom ISO through a support ticket if the stock templates don't cover what you need.

Worth knowing: these are the specials, not the standard catalogue. RackNerd's own ordering guide lists a 512 MB entry plan at $26.99/year, so treat the table above as the cheap end of the lineup and confirm the live number on the order form. Prices here reflect promotional listings and the checkout page is what actually applies.

Dedicated servers are a separate purchase and are built by hand:

| Server | CPU | RAM | Storage | Network | Location | Price |
| --- | --- | --- | --- | --- | --- | --- |
| Intel Xeon E3-1240 v3 | 4×3.40 GHz (8 threads) | 32 GB | 1 TB SSD + 3 TB HDD | Unmetered 1 Gbps | New York | $64.95/mo |
| AMD Ryzen 5 7600 | 6×3.80 GHz (12 threads) | 64 GB | 1 TB NVMe | Unmetered 1 Gbps | Utah | $109.95/mo |
| Dual Intel Xeon E5-2683 v4 | 32×2.10 GHz (64 threads) | 256 GB | 2×2 TB SSD | Unmetered 1 Gbps | New York | $209.00/mo |

Dedicated delivery takes **24 to 72 hours**, since someone has to rack and configure the hardware.

## Two Los Angeles facilities, two different jobs

This is the part most location lists blur together. RackNerd has two Los Angeles data centers and they are not interchangeable.

**LA DC-03** is the newer one, at 1200 W 7th St. in Downtown LA. It runs on Cogent and Arelion transit, has true 24/7 on-site staffing, and holds SOC2 and SSAE16 certifications. KVM VPS has been deployable there since March 2025, alongside colocation and bare metal. RackNerd positions it for computation-heavy work: AI inference, model training, and LLM deployments. Its Looking Glass endpoint is at lg-lax03.racknerd.com.

**LA DC-02** is the facility that gets described as Asia-optimized, with China Telecom, China Unicom, and ChinaNet in the network mix. Note that this is a third-party description, not an official spec sheet, and it is a blended budget route rather than a dedicated premium China line. For a $11.29/year VPS, though, it's the only cheap option in this catalogue where someone has clearly thought about latency into mainland China.

Practical split: if 80% of your visitors are in China, Japan, or Korea, DC-02's routing is the one difference on this list actually worth paying for. If you're hosting a US West Coast app, a build server, or anything compute-bound, DC-03's newer infrastructure and staffing matter more than the Asia blend.

👉 [See which Los Angeles facility the current KVM specials deploy to](https://bit.ly/RacKnerd)

## Choosing by where your users are

**United States.** West Coast goes to Los Angeles (either one, per the split above) or San Jose. Central US goes to Dallas or Chicago, and the difference between those two is small enough to pick on availability. East Coast is New York, New Jersey, or Ashburn, and Ashburn is the one with the best peering because it's the biggest exchange point on the eastern seaboard. Southeast and Latin American traffic leans Tampa, Miami, or Atlanta.

**Canada.** Montreal covers eastern Canada, Toronto covers the center. Toronto is a newer addition, so confirm your plan deploys there rather than assuming it.

**Europe.** Amsterdam sits inside Equinix AM5 and carries the strongest pan-European peering in the set, which makes it the default. Frankfurt has DE-CIX access if you need German exchange connectivity or a German legal footprint. Strasbourg is on the main European fiber backbone, useful if your users are spread across France, Germany, and Switzerland. London covers the UK. Dublin handles Ireland and transatlantic routes.

**Asia-Pacific.** Singapore is the only RackNerd location in Asia, so it's the obvious answer for Southeast Asian audiences. VPS availability there depends on the plan, and third-party lists treat Singapore as primarily a dedicated and shared hosting location, so check the dropdown before you assume. If Singapore isn't offered for the tier you want, LA DC-02 is the fallback for Asian traffic, though it adds a Pacific hop.

## Dublin: worth it if your traffic is Irish, British, or crossing the Atlantic

Dublin runs out of Digital Realty's DUB10 facility at Blanchardstown Corporate Park, Unit 9, Dublin 15. The building spans 11,100 sqm (119,479 sq ft) over two floors and connects to ten subsea cables, which is the reason it exists as a European edge point rather than just another EU city.

KVM VPS, bare metal, disaster recovery, and private cloud are all available from Dublin now. CEO Dustin B. Cisneros framed it as a connectivity play: "This location serves as an ideal connectivity hub for businesses requiring premium access to major markets across the United Kingdom, Western Europe, and trans-Atlantic routes to North America."

Pick Dublin if your users are in Ireland, if you want an English-speaking EU jurisdiction, or if your traffic pattern runs between Europe and the US east coast. Don't pick it over Amsterdam purely because it sounds newer. Amsterdam still wins on continental peering.

## Before you pay: three checks

**1. Test the actual route.** RackNerd publishes a Looking Glass at lg-lax03.racknerd.com, which lets you run ping and traceroute tests from their network outward and compare locations. Test IP and test files per facility are on each data center page. Ten minutes here beats a support ticket later.

**2. Confirm your city is in the dropdown.** The location selector only shows places where that specific plan can deploy. If you don't see Strasbourg or Singapore for the tier you picked, that plan isn't available there. It isn't a broken form.

**3. Understand what a mistake costs.** RackNerd's knowledge base states it does not offer refunds or a money-back guarantee. Combined with the no-migration rule, choosing the wrong city means buying a second server and moving your data by hand. On an $11.29 plan the money is trivial; the evening you spend migrating isn't.

👉 [Start an order and check the location dropdown for your city](https://bit.ly/RacKnerd)

## FAQ

**Can I move my VPS to a different data center later?** Not through the control panel. You deploy a new server in the target location and migrate the data yourself. Some buyers report opening a ticket within a few days of ordering and getting the location changed, but that's an exception, not a policy to plan around.

**Which location is best for users in China?** LA DC-02, because of the China Telecom, China Unicom, and ChinaNet blend. It's a budget routing mix, not a premium China-only line, so expect better latency than a generic US West server rather than a guarantee.

**Is there VPS in Singapore?** Singapore exists as a RackNerd location. Whether your specific plan deploys there depends on the tier, and third-party location guides describe it mainly as a dedicated and shared hosting site. The order form settles it in one click.

**How fast is setup?** VPS is instant, typically 5 to 15 minutes. Dedicated servers take 24 to 72 hours.

**Will the promotional price stay the same at renewal?** RackNerd's own specials page addresses renewal pricing in its FAQ, but the answer that applies to your order is in the checkout terms. Read them before paying rather than relying on a listing.

## Final rules

| Your situation | What to pick |
| --- | --- |
| Cheap site, VPN, or a small self-hosted app | Lowest KVM tier, nearest of LA / New York / Amsterdam |
| Serving mainland China, Japan, or Korea | LA DC-02 |
| AI, ML, or LLM workloads | LA DC-03, or a dedicated server |
| European audience | Amsterdam, then Frankfurt, then Strasbourg |
| Irish, UK, or transatlantic traffic | Dublin or London |
| Southeast Asia | Singapore if your plan offers it, otherwise LA DC-02 |

Two things to confirm at checkout before you click pay: that your city appears in the dropdown for the plan you selected, and that you've read the terms, since there's no refund window to fall back on. Everything else about ordering from RackNerd is straightforward.

👉 [View RackNerd plans and lock in your data center](https://bit.ly/RacKnerd)
