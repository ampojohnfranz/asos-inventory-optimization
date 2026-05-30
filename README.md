# Identifying $500k+ in Phantom Revenue for ASOS

## The Business Problem
ASOS experiences constant stockouts across major brands, but lacks visibility into the exact financial impact. When high-demand items run out of specific sizes, the company loses "Phantom Revenue" (unrealized sales).

## The Solution
I built a Python script to audit the ASOS supply chain from the outside. By analyzing 18,000+ live product listings, I calculated the exact lost revenue tied to stockouts and identified which brands require immediate inventory budget reallocation.

## Key Findings
* **Total Exposure:** Identified over $600,000 in missed revenue across core brands.
* **The Biggest Bleeder:** `ASOS Design` accounts for $371,485 in lost revenue, severely underperforming in inventory availability despite having 4,209 listings.
* **High-Value Misses:** `Topshop` items average $47.61 but lose $90,720 due to stockouts, indicating high customer demand that the supply chain is failing to meet.

## Recommendations
1. Reallocate procurement budget away from low-performing, high-inventory brands.
2. Implement automated alerts when `ASOS Design` and `Topshop` inventory drops below a 15% size-availability threshold.
