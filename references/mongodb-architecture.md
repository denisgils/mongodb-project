# MongoDB architecture checklist

- Workload: reads, writes, shapes, volume, growth, latency, regions.
- Model: access patterns first; embed or reference with measured trade-offs.
- Indexes: cover critical queries; confirm with `explain` and write cost.
- Topology: size for peak load; isolate analytics; shard only with a sound key.
- Safety: least privilege, encryption, network controls, backups, restore tests.
- Operations: alerts, profiling, capacity thresholds, failure drills, runbooks.
- Delivery: migration steps, rollback, compatibility, data validation, acceptance tests.
