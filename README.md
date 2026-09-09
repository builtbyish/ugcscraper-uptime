# ugcscraper-uptime

External uptime probe for [UGC Scraper](https://ugcscraper.com). Every 5 minutes a GitHub Actions
runner (outside the product's own infrastructure) checks that the public status feed and the
website respond, alerts if they don't, and reports the result to the status page's
"Independent monitor". No product code lives here; the two URLs it checks are public.
