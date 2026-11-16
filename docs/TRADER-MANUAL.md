# OYYO Trade Signals trader manual

## Start with the workspace

1. Choose or create a saved workspace.
2. Add instruments and select the relevant sessions and horizons.
3. Arrange charts, watchlists, scanner, evidence, news, activity, risk and journal panels.
4. Confirm source timestamps and connector health.

## Build a research record

1. State the instrument and horizon.
2. Run or review the relevant specialist analysis.
3. Inspect supporting and opposing evidence.
4. Review uncertainty, limitations, model version and provenance.
5. Save the observation and any strategy assumptions.

## Create an alert

Define the instrument, condition, threshold/context and enabled state. Alerts support monitoring; they can be delayed or unavailable and never remove the need to review current market conditions.

## Paper-test the idea

1. Open a paper ticket from the chart, observation or watchlist.
2. Verify side, quantity, reference price and notional.
3. Pass the configured paper-risk limits.
4. Record the simulated transaction.
5. Review derived position, outcome and journal notes.

## Use a connected mode

1. Confirm the active mode: Manual, Supervised or Automatic.
2. Confirm venue/account, connector health and permissions.
3. Review symbol mapping, price source, order type and quantity.
4. Confirm deterministic limits and kill-switch status.
5. For Manual, submit the exact reviewed ticket.
6. For Supervised, approve the exact prepared intent before expiry.
7. For Automatic, verify strategy scope and fixed limits before enabling.
8. Monitor acknowledgements, fills, rejects, fees and position changes.

## Risk Center checklist

- Maximum trade notional
- Maximum daily loss
- Maximum position/exposure
- Allowed venues, accounts and instruments
- Allowed order types
- Frequency and duplicate protection
- Stale-data threshold
- Connector disconnect behavior
- Authorization expiry
- OYYO kill switch
- Independent venue-level emergency stop

## Journal and review

Record the original evidence, expected scenario, invalidation criteria, chosen mode, actual events and lessons. Compare model/workflow and source versions when reviewing older records.

## Critical disclaimers

OYYO provides informational decision support, not personal investment advice. No signal, chart, agent, alert, paper result, supervised review or automatic strategy guarantees an outcome. Connected modes can lose money rapidly. Connectivity, data, software, model and configuration errors can cause missed, duplicated, delayed or unintended actions. Customers must understand their connectors and limits, supervise systems appropriately and comply with venue and local requirements.
