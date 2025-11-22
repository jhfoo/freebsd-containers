# freebsd-containers
Collection of container configs for easy build and deploy. The intent is to encourage best-practice deployments while balancing complexity.

# Caveat
Still learning what best-practice really means so don't take the collection as gospel truth on how things should be.

# Assumptions
## Home use
This setup is not designed for commercial or production. Decisions are biased towards home setups.

# Best practices
## Store secrets e.g. tokens in KV
1. Ideally in Vault (BACKLOG).
2. Implementation using Consul since this is for home use.
