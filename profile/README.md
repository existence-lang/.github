# Existence Lang

A composable ontology framework for AI agents and human systems.

## What is an Existence Kernel?

An existence kernel is a minimal set of universal terms that ground all context — from the broadest scope (Existence itself) to the narrowest (a single project). It bridges philosophy with systems thinking, giving AI agents and humans a shared vocabulary for scoping, context, and resolution.

## The 14-Term Kernel

| Term | Definition |
|------|-----------|
| **Existence** | Everything that 'is'; the universal set containing all entities |
| **Entity** | Any information in Existence — abstractions, persons, systems, objects |
| **Abstraction** | A concept modeling something else without its complexity |
| **Scope** | Breadth, depth, or reach of a perspective; bounds what's relevant |
| **Context** | Scope applied to abstractions; limits information needed for coherent systems |
| **Resolution** | Level of detail and granularity; zoom in/out to observe patterns |
| **Pattern** | Elements that repeat in a predictable manner; transferable across domains |
| **System** | An entity viewed from an internalized perspective; a whole of relationships |
| **Domain** | A bounded system of interest with associated language |
| **Focus** | Finite attention applied to a scope; enables efficient energy use |
| **Perspective** | A viewpoint on a system; influences reality; all entities have one |
| **Consciousness** | An entity's ability to interpret relevant signals; being present |
| **Evolution** | How an entity alters in response to context; the universal pattern of change |
| **Story** | A sequence of events holding state that creates context |

## Architecture

**Three concentric rings — 114 terms total:**

- **Ring 0: Kernel** — 14 universal terms, always loaded. The existential scope.
- **Ring 1: Software** — 17 terms bridging the kernel to DDD and software domains.
- **Ring 2: Extended** — 83 philosophical and cross-domain terms. Referenced on demand.

Higher rings assume all lower rings. Each project can add **domain overlays** — project-specific terms that extend the kernel with scoped context.

## Projects

| Repo | Description |
|------|-------------|
| [ontology](https://github.com/existence-lang/ontology) | Reference existential ontology — 114 terms across 3 rings |
| [existence](https://github.com/existence-lang/existence) | CLI tool for ontology management, validation, and composable scoping |
| [spec](https://github.com/existence-lang/spec) | Node format specification and templates |
| [.github](https://github.com/existence-lang/.github) | Organization profile and meta |

## Composable Scoping

The kernel scopes from universal to specific:

```
Existence → Domain → Project → Focus
```

Each level inherits from above and adds domain-specific terms. An AI agent reads the relevant scope, applies the terms, and maintains coherence across sessions.

## Philosophical Lineage

The kernel synthesizes four traditions:

- **Process philosophy** (Whitehead) — evolution, systems, relationships
- **Phenomenology** (Husserl) — focus, perspective, consciousness, context
- **Information-theoretic ontology** — entity as information, resolution, patterns
- **Existentialism** (Heidegger, Sartre) — project, story, consciousness as situated

## Contributing

The existence kernel is a living system. Contributions welcome — whether refining definitions, adding nodes, or building domain overlays.

## License

Apache-2.0
