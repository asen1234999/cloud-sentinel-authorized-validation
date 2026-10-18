# Cloud Sentinel authorized synthetic validation fixture

This dedicated repository is for its owner's read-only credential-exposure monitoring acceptance.
All credential-looking strings are locally generated, never issued or registered, and unusable as real credentials.
No production source, databases, private keys or administrator credentials are included.

## Scope
Collection is limited to this repository and its reachable history, with bounded requests and no credential login/probing.
`canary.js` has three synthetic credential categories. A synthetic history-only file is committed then deleted.
The current snapshot and reachable-history acceptance are separate results.

## Limits
This is a real hosted platform with controlled synthetic content, not a naturally discovered leak,
a provider-validated secret, a global search result, a continuous SLA or proof that other channels work.
Do not use these samples to authenticate to any service. No CI/deployment is configured.
