# poly-rules

**Build automation that's safe to ship.**

poly-rules is an open-source flow execution engine for teams that need
reliable, auditable automation — without the runtime surprises.

You define workflows as declarative JSON: a graph of operations, conditions,
and HTTP calls. The engine compiles them before execution, catching every type
mismatch, unresolved reference, and structural error ahead of time. If it
compiles, it runs.

---

## Why poly-rules

**Predictable by design.** Flows are validated and type-checked at compile
time — not discovered broken in production.

**Readable by non-engineers.** JSON flow specs are structured enough to be
reviewed, audited, and version-controlled like any other artifact.

**Composable.** Operations are first-class. Flows can call external APIs,
branch on conditions, and transform data through a typed expression language —
all wired together declaratively.

**Built to scale.** The engine separates compilation from execution, so
compiled flows can be cached and reused. A PostgreSQL-backed flow registry
is on the roadmap.

---

## Status

Active development. REST API and CLI available.
Flow registry, UI editor, and batch processing planned.
