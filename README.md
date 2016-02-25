# Igloo
Project IGLOo provides **I**P **G**eo **Lo**cation data files for personal and commercial use under the terms and conditions of Apache Software License.

At present it includes IPv4, IPv6 and ASN to Country Code ([ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)) mapping. The data is in CSV files, and is periodically kept up to date. The data can be imported to Relational and NOSQL databases for faster lookup.

## Format
The format of all files is:
```csv
(asn|ipv4|ipv6) start,range,country code
```
