# Letter for Prof. Yves Robert — ENS Lyon (parallel scheduling, fault tolerance)

## Contact
- Email: Yves.Robert@ens-lyon.fr (verified from homepage)
- Position: Professor of Exceptional Class, ENS Lyon. Chair of CS Dept. IEEE Fellow. Babbage Award 2020.
- Research: Scheduling heterogeneous platforms, fault tolerance/checkpointing, green scheduling, parallel algorithms

## Why him
- 40 years of optimal scheduling on heterogeneous machines = exactly our problem
- Babbage Award = lifetime achievement in parallel computing
- Fault tolerance/checkpointing = what happens when workers crash
- Green scheduling (2025) = energy efficiency in distributed systems
- 7 books, 174 journal papers

## The Arrow
Our system IS his scheduling problem: different machines, different speeds, independent subtasks, need to minimize total time. But with a new constraint: migration has a privacy cost (each migration = one more machine sees data).

## Key angles
1. Scheduling: RTX 4090 finishes in 30s, integrated graphics takes 5min — how to distribute subtask SIZES optimally?
2. Privacy-migration tradeoff: can migrate slow tasks BUT each migration = privacy cost. Perfect initial scheduling avoids migration entirely.
3. Fault tolerance: workers aren't supercomputer nodes — they're volunteers who close laptops. Different failure model.
4. Green scheduling: minimize energy across the whole hive.

## Status: SENT / NOT SENT
