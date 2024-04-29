List of ip addresses from various ASN
=====================================

This repository contains lists of ip addresses in text format unloaded from various ASN (like Microsoft, Meta, etc.).

That txt list is very helpful for configuration routers or firewalls, when needed support custom routing or access/deny to that ASN.

Simple Linux console command for get list of nets from specific ASN:

For IPv4:

    # echo '-i origin AS32934' | nc whois.radb.net 43  | grep '^route:'

For IPv6:

    # echo '-i origin AS32934' | nc whois.radb.net 43  | grep '^route6:'

