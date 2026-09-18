# Creo Studios Scraper

Production Finds scraper for [Creo Studios](https://www.creo--studios.com/).

- Source: `scraper-creostudios`
- Store: Creo Studios, EN + EUR
- Schedule: `31 5 * * 3` UTC (Wednesdays)
- Currency: EUR
- Gender default: Unisex
- Embeddings: local SigLIP `google/siglip-base-patch16-384`
- Secrets: `SUPABASE_URL`, `SUPABASE_KEY`
- Catalog crawl: store-wide endpoint
- Upsert batch size: 5 with single-row fallback; never sends `embedding_version`