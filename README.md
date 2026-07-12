# frontend-architecture-patterns

> A curated collection of real-world frontend architecture & patterns — not just theory. Every entry comes with sample code, trade-offs, and a concrete use case pulled from `ai-workspace` and `commerce-platform`.

## 🎯 Why this repo exists

This repo is aimed at Tech Leads / Solution Architects — a place to demonstrate architectural thinking rather than just product features. Content is written from actually building the two flagship products, not copied from tutorials.

## 📁 Structure

```
frontend-architecture-patterns/
├── architecture/          # Overall architecture
│   ├── folder-structure.md
│   ├── clean-architecture.md
│   ├── state-management.md
│   ├── network-layer.md
│   ├── error-handling.md
│   ├── offline-strategy.md
│   ├── ci-cd.md
│   ├── monitoring.md
│   ├── feature-flags.md
│   ├── modularization.md
│   └── performance.md
├── patterns/               # Reusable business patterns
│   ├── authentication/
│   ├── infinite-scroll/
│   ├── pagination/
│   ├── search/
│   ├── upload-download/
│   ├── polling/
│   ├── retry/
│   ├── permission/
│   ├── realtime/
│   ├── optimistic-update/
│   ├── cache/
│   ├── offline-queue/
│   └── multi-step-form/
└── README.md
```

Each pattern under `patterns/` has this sub-structure:
```
patterns/infinite-scroll/
├── README.md          # Problem, solution, trade-offs
├── react/              # React sample code
└── react-native/       # React Native sample code (if applicable)
```

## ✅ Content checklist

### Architecture
| Topic | Status |
|---|---|
| Folder Structure | ⬜ |
| Clean Architecture | ⬜ |
| State Management | ⬜ |
| Network Layer | ⬜ |
| Error Handling | ⬜ |
| Offline Strategy | ⬜ |
| CI/CD | ⬜ |
| Monitoring | ⬜ |
| Feature Flags | ⬜ |
| Modularization | ⬜ |
| Performance | ⬜ |

### Patterns
| Pattern | Status |
|---|---|
| Authentication Flow | ⬜ |
| Infinite Scroll | ⬜ |
| Pagination | ⬜ |
| Search | ⬜ |
| Upload/Download | ⬜ |
| Polling | ⬜ |
| Retry | ⬜ |
| Permission | ⬜ |
| Realtime | ⬜ |
| Optimistic Update | ⬜ |
| Cache | ⬜ |
| Offline Queue | ⬜ |
| Multi-step Form | ⬜ |

## 📝 Doc convention (for AI agent)

Each pattern/architecture topic → one `.md` file using this template:

```markdown
# [Pattern/architecture name]

## Problem
The real situation encountered while building ai-workspace/commerce-platform.

## Solution
The approach, with minimal sample code to convey the idea.

## Trade-offs
Comparison with 1-2 alternative approaches — why this one was chosen.

## When NOT to use this
Limitations/risks of this pattern.

## Source
Which module in ai-workspace/commerce-platform this was pulled from (link to the related file/PR).
```

Suggested prompt:
> "I just implemented infinite scroll for the product list in commerce-platform (code at `modules/product/ProductList.tsx`). Write `patterns/infinite-scroll/README.md` following the template, comparing trade-offs with traditional pagination."

## 🔗 Related repos

- [`ai-workspace`](../ai-workspace), [`commerce-platform`](../commerce-platform) — the real-world source of these patterns
