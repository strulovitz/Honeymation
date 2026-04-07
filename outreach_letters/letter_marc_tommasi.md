# Letter for Prof. Marc Tommasi — INRIA Lille / University of Lille (Magnet team, federated learning)

## Contact
- Email: marc.tommasi@univ-lille.fr (also marc.tommasi@inria.fr)
- Position: Professor of CS, University of Lille. Leads Magnet team at INRIA Lille.
- Research: Federated learning, heterogeneous data, healthcare AI, grammatical inference

## Why him
- FLamby benchmark — THE standard for federated learning in healthcare
- CNIL-funded federated learning in French hospital networks
- Core problem: heterogeneity (non-IID data across hospitals)
- Leads the team Bellet used to be in

## The Arrow
His federated learning = private TRAINING (data stays in each hospital). Our system = private INFERENCE (tasks distributed, data stays local). Combined = end-to-end privacy in both training and inference.

## Key angles
1. Private training (his) + private inference (ours) = complete privacy pipeline
2. Medical imaging hive: vision models (Qwen3-VL, GLM 4.5V, Gemma 4) cut X-ray/CT into grid, each worker analyzes a section, coordinator combines findings. Patient data never leaves hospital.
3. Heterogeneity in inference: different workers run different quality models — how to weigh confident answers from strong models vs uncertain answers from weak models? His non-IID techniques applied to inference outputs.

## Status: SENT / NOT SENT
