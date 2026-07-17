---
topic: chromatography
section: common-misconceptions
status: draft
version: 1.0
last_reviewed: 2026-07-17
confidence: high
primary_sources: 2
secondary_sources: 8
updated_by: codex
---

# Chromatography — Common Misconceptions

## CHR-M001

Misconception: Longer retention time automatically guarantees higher resolution between two peaks.

Correction: Retention time $t_R$ increases retention factor $k$, but resolution $R_s$ depends on selectivity $\alpha$ and plate number $N$. If $\alpha = 1.0$ (identical thermodynamic affinity), increasing retention time broadens peaks without achieving separation.

Evidence: CHR-001; CHR-002; CHR-004

Status: Verified

## CHR-M002

Misconception: Increasing flow rate $u$ always decreases efficiency and resolution.

Correction: The Van Deemter equation ($H = A + B/u + C u$) shows that at low flow rates ($u < u_{opt}$), longitudinal diffusion ($B/u$) dominates and degrades efficiency. Increasing flow rate toward $u_{opt}$ *improves* efficiency.

Evidence: CHR-002; CHR-005

Status: Verified

## CHR-M003

Misconception: Void volume / dead time ($t_0$) can be ignored when comparing peak retention times.

Correction: Raw retention time $t_R$ includes column hold-up time $t_0$. Using raw $t_R$ instead of adjusted retention factor $k = (t_R - t_0)/t_0$ causes severe errors when comparing columns of different lengths or flow rates.

Evidence: CHR-002; CHR-003

Status: Verified

## CHR-M004

Misconception: Ultra-high plate count ($N$) can compensate for zero chemical selectivity ($alpha = 1.0$).

Correction: When $\alpha = 1.0$, $\frac{\alpha - 1}{\alpha} = 0$, making resolution $R_s = 0$ regardless of how large $N$ becomes. Selectivity $\alpha$ is the single most powerful factor driving separation.

Evidence: CHR-002; CHR-004; CHR-005

Status: Verified
