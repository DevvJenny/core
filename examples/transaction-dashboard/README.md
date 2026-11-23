# transaction-dashboard

Multi-framework responsive transaction dashboard examples demonstrating real-time transaction history, status monitoring, and fee analytics using `sorokit-core`.

## Files

- `react-dashboard.example.tsx`: React dashboard implementation with accessible status timeline, filters, and transaction details.
- `vue-dashboard.example.vue`: Vue 3 equivalent component utilizing reactive composition and `sorokit-core` account streams.

## Patterns Covered

- Querying transaction history via `client.transaction.getHistory`
- Real-time transaction confirmation polling and status timeline
- Highlighting fee surge alerts and network congestion
- Framework-agnostic error handling using `SorokitResult`

## Setup & Running

From the workspace root:

```bash
# Typecheck
npx tsc --noEmit examples/transaction-dashboard/react-dashboard.example.tsx
```
