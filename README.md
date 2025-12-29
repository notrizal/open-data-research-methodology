# A Comparative Analysis of Technical Security Features and User Perception in ChatGPT and Gemini

This repository contains the primary research artifacts, datasets, and evaluation frameworks for a comparative study between **OpenAI's ChatGPT** and **Google's Gemini**. The research focuses on the "Security-Visibility Gap" the disconnect between objective technical security implementations and subjective user trust.

This project was developed as part of the **Research Methodology in Computer Science** course at **Bina Nusantara (BINUS) University**.

## Research Overview

The rapid adoption of Large Language Models (LLMs) has introduced complex security challenges. This study investigates the divergence between technical security implementations and user perceptions in flagship platforms.

### Key Findings:

-   **Invisible Security:** ChatGPT exhibits robust technical defenses (e.g., strict data retention) that fail to alleviate user anxiety, resulting in a significant negative trust gap.
-   **User Overconfidence:** Gemini displays a "Halo Effect," where users perceive the platform as secure despite documented vulnerabilities to adversarial prompt injection attacks.
-   **Statistical Uniformity:** Wilcoxon Signed-Rank Test results ($p=0.535$) confirm that users cannot distinguish between a technically hardened system and a vulnerable one based on interaction alone.

## Repository Structure

The folders in this repository correspond to the five core dimensions used in our evaluation process:

| Folder                               | Contents & Research Dimension                                                                     |
| :----------------------------------- | :------------------------------------------------------------------------------------------------ |
| `Enkripsi & Keamanan Data Transmisi` | Analysis of TLS 1.3, SSL Grades, and End-to-End Encryption (E2EE).                                |
| `Hasil Survey (Subjektif)`           | Raw and normalized data from the User Perception Survey ($N=30$).                                 |
| `Manajemen Data & Kontrol Pengguna`  | Evidence regarding history deletion, data export (JSON), and retention policies.                  |
| `Otentikasi & Manajemen Sesi`        | Technical audits of 2FA support and session timeout policies.                                     |
| `Robustness Model`                   | Documentation of Adversarial Red Teaming using "DAN" jailbreak prompts.                           |
| `Scorecard Penilaian (Objektif)`     | The standardized scoring rubric (0-2 scale) used to establish the technical baseline ($S_{obj}$). |
| `Transparansi & Kebijakan`           | Evaluation of Privacy Hubs and the readability of privacy documentation.                          |

## Methodology

This research followed a two-phase sequential design:

1. **Phase 1 (Technical Audit):** Conducted using automated scanning (Qualys SSL Labs), manual functionality testing, and Adversarial Red Teaming.
2. **Phase 2 (User Perception):** Data collected via snowball sampling using a 5-point Likert scale survey.
3. **Data Analysis:** Min-Max Normalization was applied to both datasets to calculate a comparable Security Index ($SI$) between 0 and 100.

## Research Team

**Computer Science Department, School of Computer Science** **Bina Nusantara University, Jakarta, Indonesia**

-   **Felixan Lamhot Geraldo:** Conceptualization and Introduction.
-   **Muhammad Zeldy Nasution:** Literature Review and Results Analysis.
-   **Rico Bryan Caesario:** Conclusion and Review.
-   **Rizal Ramadhan:** Research Methodology and Data Visualization Scripts.
-   **Zahra Nabila Izdihar:** Study Supervision and Verification.
-   **Said Achmad:** Study Supervision and Administration.

## Citation

If you utilize this dataset or research framework, please cite the original paper:

> F. L. Geraldo, M. Z. Nasution, R. B. Caesario, and R. Ramadhan, "A Comparative Analysis of Technical Security Features and User Perception in ChatGPT and Gemini," _Research Methodology in Computer Science_, Bina Nusantara University, 2025.
