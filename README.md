# Vibrant Home Assistant Add-ons (Gateway OS)

This repository contains **configuration-only** Home Assistant add-ons for Vibrant’s Gateway OS. The actual container images are built from a separate internal repository (`home-assistant-addons-internal`) and pushed to a private Harbor registry; this repo only exposes the add-on metadata and image references.

## Gateway OS and dependent add-ons

The **Gateway OS** add-on is the primary entry point for the system. Installing and configuring Gateway OS will, by design, bring in and rely on the other supporting add-ons (database, API, CoAP broker, event server, and zone manager) as part of the overall Gateway stack.

You will need access to harbor if doing this manually without GatewayOS.
