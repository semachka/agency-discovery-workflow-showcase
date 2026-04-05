# Agency Discovery & Qualification Workflow for Outreach

A sourcing and enrichment workflow designed to identify agencies and service businesses that may be a strong fit for outbound outreach.

## What it does

This system helps:

- collect relevant agency and service-business leads
- extract contact details
- surface practical fit signals
- support better outreach prioritization

Instead of producing a raw list, the workflow is designed to help decide **who is actually worth contacting first**.

## Example output

Typical output can include:

- company name
- contact email
- service context
- fit reasoning for outreach

Example fit signals:

- booking or quote request flows
- emergency or same-day service patterns
- multi-service intake potential
- clear signs that structured request handling would be valuable

## Workflow structure

The system is built as a reusable scraping and enrichment workflow rather than a one-off list-building script.

Core components include:

- adapters for site-specific parsing
- reusable extractors
- enrichment and validation layers
- storage and export support
- transport modes for HTTP and browser-based crawling

## Use case

This workflow is useful for finding outreach targets that are more likely to benefit from:

- client intake systems
- request-handling workflows
- booking flows
- lead routing and admin-side handling

## Notes

This project is presented as a workflow system and technical showcase of sourcing, enrichment, and qualification logic.
