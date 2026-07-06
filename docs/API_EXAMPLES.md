# API Examples

This repository is an architecture showcase. The examples describe public-safe review artifacts and conceptual interface contracts, not a public mainnet API.

## Public Artifact Requests

README request:

```bash
curl -L "https://raw.githubusercontent.com/0xChrisSKR/cchain-system-showcase/master/README.md"
```

Architecture document request:

```bash
curl -L "https://raw.githubusercontent.com/0xChrisSKR/cchain-system-showcase/master/docs/ARCHITECTURE.md"
```

Career mapping request:

```bash
curl -L "https://raw.githubusercontent.com/0xChrisSKR/cchain-system-showcase/master/docs/CAREER_MAPPING.md"
```

Representative response shape:

```json
{
  "repository": "cchain-system-showcase",
  "artifact": "public engineering showcase",
  "source": "https://github.com/0xChrisSKR/cchain-system-showcase",
  "claimBoundary": "verifiable public material only"
}
```


## Design Contract Example

Request:

```bash
curl -X POST "https://example.invalid/transaction/prepare" \
  -H "Content-Type: application/json" \
  -d '{"action":"prepare-transfer","network":"private-experimental"}'
```

Response shape:

```json
{
  "status": "requires-wallet-signature",
  "signingBoundary": "user-wallet",
  "receiptExpected": true,
  "publicMainnetClaim": false
}
```

This is a public-safe interface example, not a public chain endpoint.
