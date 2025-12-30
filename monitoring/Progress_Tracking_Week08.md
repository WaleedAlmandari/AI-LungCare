## Project Baseline Summary

**Planned duration:**  
Based on our Week 05 baseline schedule, AI-LungCare is planned across **9 project weeks (Week 1 → Week 9)**. The work is arranged in clear phases: we first prepare and verify the dataset, then build and train the CNN model, then integrate the model into a backend API, followed by UI prototype + system testing, and finally documentation and submission.

**Planned budget:**  
From the Week 05 Cost & Resource Plan, the planned total budget is **approximately RM 785**. Most of the cost is concentrated in the technical work (data preparation, model development/training, and backend integration). Documentation and ethics-related tasks are low cost because they mainly require writing and review rather than tools or compute.

**Key milestones:**  
- **Data preparation completed** (verified datasets + cleaned data) — **End of Week 2**  
- **Model design & training finished** (CNN trained and saved as **v1**) — **End of Week 4**  
- **Backend API integration completed** (Flask API working and returning predictions) — **End of Week 6**  
- **Supervisor approval / readiness check** (system stable for demo) — **End of Week 7**  
- **Final submission** (final report, slides, and GitHub release **v1.0**) — **End of Week 9**


## Progress Tracking (Midway Checkpoint)

Assuming the project is midway through execution, the progress is tracked by comparing the planned completion against the actual completion.

| Major Task | Planned Completion (%) | Actual Completion (%) | Status | Notes |
|---|---:|---:|---|---|
| Collect and clean X-ray dataset | 100 | 90 | Behind | Cleaning done but some dataset verification still ongoing |
| Model training and tuning (CNN) | 100 | 80 | Behind | Training started, but tuning/validation still not fully completed |
| Web integration (React + Flask API) | 50 | 30 | Behind | API routes are not fully connected with the UI yet |
| Project supervision & testing | 20 | 10 | Behind | Only basic testing completed, still waiting supervisor feedback |
| Reporting & presentation | 0 | 0 | On track | Not started yet because it is planned for later weeks |

### Tasks behind schedule / over cost (at least 2)
- **Model training and tuning** is behind because tuning and validation take longer than expected, and GPU/compute time may increase cost.
- **Web integration (React + Flask API)** is behind because integration needs debugging between frontend and backend, and it depends on stable model output format.
