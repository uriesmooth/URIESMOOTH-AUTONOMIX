                    URIESMOOTH-AUTONOMIX
                             │
                 ┌───────────┴───────────┐
                 │   ORCHESTRATION CORE   │
                 └───────────┬───────────┘
                             │
          ┌──────────────────┼──────────────────┐
          ▼                  ▼                  ▼
      PLANNING           EXECUTION          GOVERNANCE
          │                  │                  │
       Planner           Worktrees          Policies
       Architect         Sandbox            Approvals
       Task Graph        Commands            Risk
          │                  │                  │
          └──────────────────┼──────────────────┘
                             ▼
                    SPECIALIST AGENTS
                             │
       ┌────────┬────────┬───┴───┬────────┬────────┐
       ▼        ▼        ▼       ▼        ▼        ▼
     Code     Test    Security  Perf     Docs    Release
       │        │        │       │        │        │
       └────────┴────────┴───┬───┴────────┴────────┘
                             ▼
                       EVALUATION
                             │
                    ┌────────┴────────┐
                    ▼                 ▼
                 PASS             FAILURE
                    │                 │
                    ▼                 ▼
                 MERGE           DIAGNOSE
                                      │
                                      ▼
                                   REPAIR
                                      │
                                      ▼
                                  RE-TEST
                                      │
                             ┌────────┴────────┐
                             ▼                 ▼
                           PASS              FAIL
                             │                 │
                             ▼                 ▼
                          RELEASE          ESCALATE