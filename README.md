# XML Sitemap and Index Validator

[![XML Sitemap Validator](https://img.shields.io/badge/TAVARDT-Sitemap%20XML-5b3cf5.svg)](https://tools.tavardt.com/uk/xml-sitemap-validator/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Technical validation tool for XML sitemaps and sitemap index files, enforcing sitemaps.org protocols, clean namespaces, and crawl integrity.

***

## XML Sitemap Validation Capabilities

* **Protocol Specification Adherence**: Rigorous evaluation of `<urlset>` markup and hierarchical `<sitemapindex>` files.
* **Attribute Integrity Auditing**: Strict validation of `<loc>` formatting, W3C DateTime compliance for `<lastmod>`, and priority weights.
* **URL Hygiene and Scheme Safety**: Detection of insecure HTTP endpoints within secure domains and unescaped entities.
* **Capacity and Quota Governance**: Enforcement of the 50,000 URLs ceiling and 50MB uncompressed file limit.
* **Sitemap Health Rating**: Objective 0 to 100 benchmark highlighting exact technical remediation priorities.

***

## Installation and Execution

Requires Python 3.8 or higher with standard library only.

```bash
git clone https://github.com/TAVARDT-UK/xml-sitemap-validator-uk.git
cd xml-sitemap-validator-uk
python sitemap_validator.py https://example.co.uk/sitemap.xml
```

To output machine-readable JSON:

```bash
python sitemap_validator.py https://example.co.uk/sitemap.xml -json
```

***

## Search Indexing and Crawl Architecture Advisory

For enterprise sitemap architecture, crawl budget optimisation, and alignment with Sitemaps.org Protocol and Search Crawl Guidelines, contact the specialists at **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/uk/
* **Diagnostic Suite:** https://tools.tavardt.com/uk/
* **Technical Contact:** https://ag.tavardt.com/uk/contact/

***

### License
Released under the MIT License.

***

© 2026 TAVARDT. All rights reserved.
