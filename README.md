# Bama RushTok Brand Index

A public dataset documenting **302 brands** that appear in Bama Rush and RushTok content across TikTok, Instagram, YouTube, and news coverage for the 2026 rush season. 

Compiled by [Jessica Malnik](https://jessicamalnik.com) as part of the *Black Friday in August* documentary investigation.

**Documentary:** [Black Friday in August](https://www.youtube.com/watch?v=2PcT41WpBpM&t=36s)

---

## What is this?

Sorority rush week at the University of Alabama (i.e. known as Bama Rush) became one of the most brand-saturated events in American consumer culture after #BamaRush went viral on TikTok. What started as outfit-of-the-day content became a live, real-time showcase for brands ranging from Van Cleef and Arpels to Shein.

This dataset documents every brand that shows up in that ecosystem: what they sell, which schools they appear at, how they're referenced (organic outfit posts, sponsored activations, OOTD cost breakdowns, local service providers), and whether they're publicly traded.

---

## Dataset columns

| Column | Description |
|---|---|
| brand_name | Brand name |
| brand_website | Official website URL |
| category | Product or service category |
| example_product_or_service | Specific item referenced in rush content |
| evidence_type | How the brand appears: named_in_ootd, sponsored_activation, gifted_content, local-boutique, rush-services, bid-day-supplies |
| school_or_market | School or geographic market where brand appears |
| year | Rush season year |
| source_url | Primary source URL |
| source_description | What the source documents |
| frequency_signal | How often the brand appears in content (1-5 scale) |
| public_or_private | Whether the parent company is publicly traded |
| ticker_if_known | Stock ticker symbol if applicable |
| confidence | Data confidence level: high, medium, or low |

---

## Files

### datasets/

| File | Description | Rows |
|---|---|---|
| `rush-brands-full.csv` | Complete dataset | 302 |
| `rush-brands-luxury.csv` | Luxury and aspirational-luxury brands ($500+ items) | 13 |
| `rush-brands-public-companies.csv` | Publicly traded brands with known ticker symbols | 53 |
| `rush-brands-tuscaloosa-local.csv` | Local Tuscaloosa, AL businesses that service the Bama Rush economy | 19 |

### downloadables/
- `rushtok-brand-economy-guide.md` - Context guide explaining the RushTok phenomenon and how to use this data

### source-ledger/
- `sources.md` - All 160 unique sources used to build the dataset

---

## Categories

| Category | Count |
|---|---|
| Clothing | 81 |
| Beauty | 51 |
| Accessories | 23 |
| Bid-day supplies | 22 |
| Shoes | 18 |
| Rush services | 15 |
| Food and beverage | 15 |
| Tanning | 14 |
| Jewelry | 12 |
| Dorm decor | 11 |
| Local boutiques | 9 |
| Event services | 8 |
| Handbags | 7 |
| Skincare | 5 |
| Media | 5 |

---

## License

- **Data** (`datasets/`): [CC0 1.0 Universal](LICENSE) - public domain, no attribution required
- **Documentation**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) - attribution required

---

## Citation

If you use this dataset, please cite:

> Malnik, Jessica. *Bama RushTok Brand Index*. 2026. https://github.com/jessicamalnik/bama-rushtok-brand-index
