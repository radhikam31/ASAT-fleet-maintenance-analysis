# ASAT Fleet Maintenance Analysis

Equipment maintenance analysis of a 10-tool ASAT fleet, covering April to July 2026 (July partial, through Jul 13). Built to identify failure patterns, downtime drivers, and prioritized countermeasures.

**Prepared by:** Radhika Mandhanya

## Overview

- **Data period:** Apr - Jul 2026
- **Tools analyzed:** 10 ASAT tools
- **Events analyzed:** 1,549 (excl. preventive maintenance)
- **Total downtime:** 802.9 hours
- **Average MTTR:** 0.52 hr fleet-wide

## Key Findings

- **Downtime escalation:** 76% increase in downtime from April to June (184.5 h -> 325.1 h), driven largely by ASAT08 and ASAT02.
- **Worst performer:** ASAT08 had the most total downtime (131.3 h) and among the worst MTBF (10.5 h).
- **Top failure modes:** Robot alignment issues (237 events, 181.2 h) and spring install faults (148 events, 79.9 h) account for the bulk of downtime.
- **Pareto insight:** Fixing just 2 failure codes (Robot Align, Spr Install Fault) recovers 32.5% of all downtime.
- **Shift gap:** A1 shift has 2.4x slower average repair time (0.92 h) than B2 shift (0.38 h) on the same equipment and failure types.
- **Peak incident window:** 6-10pm daily accounts for 39% of all incidents (614 events).

## Recommendations

1. Fix robot alignment on ASAT08 first (largest single-tool downtime contributor)
2. Standardize spring install process fleet-wide (occurs on all 10 tools)
3. Investigate the A1 shift repair speed gap
4. Add pre-emptive equipment checks before 6:00pm daily
5. Treat ASAT10 as a separate investigation (different failure profile - loader subsystem, not robot faults)

## Files

- `Bloom_Energy__Final.pdf` - Full analysis report with charts (MTTR/MTBF trends, monthly downtime, failure mode breakdown, Pareto analysis, shift analysis, incident hot-spots)
