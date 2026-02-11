A total of 7 requirements are found to be incongruent. Any updates or progress made will be known by all team members via github.

| Affected Requirement | Verifiability | Reason for Incongruence | IRC Category |
|---|---|---|---|
| BOR2-L1.1 (Event Notification Management) | Testable | Combines notification trigger timing, delivery channels, and user preference behaviour within a single clause, obscuring operational bounds. | Ambiguous |
| BOR2-L1.2 (Hours Completion Alerts) | Testable with clarification | Specifies notification purpose but lacks enforceable limits on frequency and suppression conditions. | Suspected Incompleteness |
| BOR3-L1.1 (Track Event Participation) | Testable with clarification | Does not clearly distinguish between system-automated tracking and administrative validation of attendance. | Ambiguous |
| BOR3-L1.2 (Display Event History) | Issues with verification | Event history display is specified without explicit linkage to validated attendance states. | Suspected Incompleteness |
| TR1-L1.1 (System Classification), TR1-L1.3 (Assess Model), TR1-L1.4 (Architectural Model) | Not Testable | Technical constraints risk redefining BOR-defined operational behaviour. | Inconsistent with another requirement |
