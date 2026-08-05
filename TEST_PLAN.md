# Test plan

- Verify archive traversal, unsafe symlinks, checksum/provenance mismatches, and credential redaction across the supported happy-path states and canonical fixtures.
- Verify archive traversal, unsafe symlinks, checksum/provenance mismatches, and credential redaction under retries, interruption, concurrency, offline operation, or partial failure.
- Verify archive traversal, unsafe symlinks, checksum/provenance mismatches, and credential redaction preserves authorization, idempotency, integrity, observability, and actionable failure classification.

## Classification

- product regression
- blocked dependency
- harness regression
