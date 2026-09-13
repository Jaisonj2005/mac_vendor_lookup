# MAC Address Vendor Lookup 🔌

A lightweight Python GUI utility for Network Operations Center (NOC) technicians to rapidly identify hardware manufacturers from Layer 2 physical addresses.

**Features:**
* Validates and cleans raw MAC address inputs using Regular Expressions (`re`).
* Extracts the standard 24-bit Organizationally Unique Identifier (OUI).
* Dynamically queries the public `macvendors.com` API via Python's native `urllib` module to retrieve official IEEE manufacturer assignments.
* Provides graceful error handling for unassigned, private, or invalid MAC blocks.

*Built as Day 6 of a 30-Day Network Engineering & Security portfolio streak.*
