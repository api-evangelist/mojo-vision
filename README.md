# Mojo Vision

Mojo Vision is a Saratoga, California semiconductor and display company building a
"wafers-in, wafers-out" micro-LED platform — a 300mm silicon architecture with
GaN-on-Silicon emitters, proprietary quantum dots and micro-lens arrays. Founded in
2015 to build the display for an AR smart contact lens, it pivoted in 2023 to
micro-LED displays and optical interconnects for XR and AI-enabled glasses,
automotive heads-up displays, large-format displays, and optical I/O for AI
infrastructure.

- https://www.mojo.vision/

## API surface

**None.** Mojo Vision is a hardware and silicon supplier with OEM/design-win
relationships, not a self-serve developer platform. As of 2026-08-01, contract
discovery found no OpenAPI, GraphQL, MCP, AsyncAPI, `llms.txt`, agent card, or any
`/.well-known/` discovery document on the website host or the conventional developer
subdomains (`api.`, `developer.`, `docs.` — no DNS). See
`well-known/mojo-vision-well-known.yml` for the full probe record.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `security/mojo-vision-domain-security.yml` | DomainSecurity | probed |
| `well-known/mojo-vision-well-known.yml` | contract-discovery record | probed |
| `llms/mojo-vision-llms.txt` | LLMsTxt | generated |
