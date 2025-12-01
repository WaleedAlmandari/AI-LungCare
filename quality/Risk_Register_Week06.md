# Risk Register (Week 06)

## Risk Categories
- **Technical risks:** Model accuracy problems, API errors, dataset issues.
- **Schedule risks:** Training delays, slow progress, team members unavailable.
- **Cost risks:** GPU usage cost increases, extra cloud hours needed.
- **Resource risks:** Limited hardware, slow internet, weak laptop performance.
- **Stakeholder risks:** Miscommunication, unclear requirements, low team engagement.

## Risk Table

| Risk ID | Description                                    | Category    | L | I | Score | Response        |
|---------|------------------------------------------------|-------------|---|---|-------|-----------------|
| R1      | Dataset is too small or unbalanced             | Technical   | 3 | 4 | 12    | Mitigate        |
| R2      | Team member unavailable during model training  | Schedule    | 2 | 3 | 6     | Transfer        |
| R3      | GPU cloud costs become too high                | Cost        | 4 | 4 | 16    | Reduce          |
| R4      | Miscommunication between team members          | Stakeholder | 3 | 2 | 6     | Improve comms   |
| R5      | API prediction becomes too slow                | Technical   | 3 | 3 | 9     | Optimize system |
| R6      | Laptop/PC crashes during model training        | Resource    | 2 | 4 | 8     | Backup & cloud  |


## Top 3 Priority Risks

1. **R3 – GPU cloud costs become too high (Score 16)**  
   This is our most serious risk because model training takes time and GPU usage can quickly increase the project cost. If the cost goes too high, we might not be able to finish the model training properly.

2. **R1 – Dataset too small or unbalanced (Score 12)**  
   If the dataset is not good, the model accuracy will drop. This affects the whole quality of the system, so fixing the dataset early is very important.

3. **R5 – API prediction becomes too slow (Score 9)**  
   A slow API makes the system hard to use. The dashboard needs fast results, so if the prediction time is long, users will not be satisfied.

## Team Communication Note
<img width="575" height="118" alt="Screenshot 2025-12-01 120322" src="https://github.com/user-attachments/assets/5498d727-47cb-4f83-b5fb-95c323cca5de" />
