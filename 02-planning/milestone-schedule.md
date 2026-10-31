# Milestone Schedule and Dependencies

**Simulation baseline | 12-month duration**

| ID | Milestone | Planned date | Predecessor |
|---|---|---|---|
| M1 | Project charter approved | End of Month 1 | — |
| M2 | Vendor mobilized | End of Month 2 | M1 |
| M3 | Future-state design signed off | End of Month 3 | M2 |
| M4 | Core configuration complete | End of Month 5 | M3 |
| M5 | Integrations built | End of Month 6 | M4 |
| M6 | Integration testing complete | End of Month 7 | M5 |
| M7 | Data mapping and cleansing complete | End of Month 7 | M3 |
| M8 | Trial migration complete | End of Month 8 | M6, M7 |
| M9 | User acceptance testing complete | End of Month 9 | M8 |
| M10 | Training complete | End of Month 10 | M9 |
| M11 | Go/no-go decision | End of Month 10 | M9, M10 |
| M12 | Go-live | End of Month 11 | M11 |
| M13 | Hypercare complete | End of Month 12 | M12 |
| M14 | Project closure | End of Month 12 | M13 |

## Critical path

`M1 → M2 → M3 → M4 → M5 → M6 → M8 → M9 → M11 → M12 → M13 → M14`

## Key dependency notes

- Data cleansing can run in parallel with configuration but must complete before trial migration.
- User acceptance testing cannot begin until trial migration and integration testing are complete.
- Training depends on stable configured processes and validated data.
- A vendor delay in configuration or integration is likely to affect the critical path and go-live date.
