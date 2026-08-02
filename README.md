# Boatsetter

Boatsetter is a peer-to-peer boat rental marketplace connecting boat owners with renters and
USCG-licensed captains. Founded in 2012 and headquartered in Miami, the platform lists 50,000+
boats across 600-700 locations worldwide, bookable bareboat or with a captain, with insurance,
payments, messaging and owner tooling layered on top of owner-supplied inventory. In December
2025 Boatsetter and Getmyboat announced a merger forming a combined marketplace expected to
process roughly $500M in bookings across 50 countries; both platforms continue to operate.

- Website: https://www.boatsetter.com
- Support: https://support.boatsetter.com/
- Blog: https://www.boatsetter.com/boating-resources

## API surface

**Boatsetter publishes no public API.** As of 2026-08-02 there is no developer portal, no API
documentation, no OpenAPI/Swagger definition, no GraphQL endpoint, no MCP server, no A2A agent
card, no SDK, and no CLI. Every discovery path was probed against every known Boatsetter host —
see [`contract-discovery.yml`](contract-discovery.yml) for the full evidence table with HTTP
status codes. The only public GitHub repository is an archived 2015 fork of
`jquery.serializeJSON`. Third-party surfaces are consumer partnerships (Airbnb) and a
link-based affiliate program, not an API.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `contract-discovery.yml` | contract discovery evidence | probed |
| `well-known/boatsetter-well-known.yml` | WellKnown probe record (0 found) | probed |
| `security/boatsetter-domain-security.yml` | DomainSecurity | probed |
| `llms/boatsetter-llms.txt` | LLMsTxt | generated |
