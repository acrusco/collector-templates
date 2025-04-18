# Trellix REST Collector

This collector template allows you to collect threat details from the Trellix API.

# Installation

1) Copy the contents of breaker.json
2) Navigate to Event Breaker Rules under Processing -> Knowledge
3) Create a new breaker ruleset
4) Edit as JSON and paste the previously copied JSON into place; save
5) Copy the contents of collector.json
6) Navigate to Data -> Sources -> REST Collectors
7) Add Collector
8) Configure as JSON tab (at the top of the window)
9) Paste the JSON from collector into the screen and save
10) Commit and Deploy

## Configuring

The collector is scheduled to run every minute and to retrieve either the past minute or else the  'state.latestTime' value retrieved from state tracking.

### Event Breaker

Import the provided event breaker and configure the REST Collector to use the `trellix` event breaker rule set.

## Authors
Brian Rampley - brampley@cribl.io
Michael Buehler -- mbuehler@cribl.io

