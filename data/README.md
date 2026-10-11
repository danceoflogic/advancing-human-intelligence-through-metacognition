# Data and schemas

No experimental observations have been collected for this project. The CSV files in `templates/` contain **column headings only**, not participant data.

Fields in the session log:

- `participant_code`: pseudonymous identifier; never a real name or email.
- `session_date`: `YYYY-MM-DD`.
- `task_id` and `task_version`: stable versioned task identifiers.
- `condition`: baseline, strategy, active control, etc., as defined by the protocol.
- `domain`: predeclared task category.
- `accuracy_score`: score using a defined rubric.
- `duration_seconds`: task duration.
- `confidence_probability`: a number from 0 to 1 when applicable; otherwise blank.
- `notes`: non-identifying contextual observations only.

Never commit private participant information, health records, contact details, recordings, or unconsented data to a public repository. Prefer aggregate or clearly labelled synthetic examples; document missing values and score ranges.
