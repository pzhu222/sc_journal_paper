# Young children are curious about what others think about them

**Abstract**

Growing up involves learning about ourselves: Who am I, what can I do, and how can I improve? Although social feedback from knowledgeable others (e.g., parents, teachers) serves as a critical source of information for learning about the self, little work has examined children's curiosity about this information. Using both naturalistic information-seeking behaviors and a binary choice measure, the current work investigates whether and when young children (ages three to five) seek information about what others think about them. We find that children are more curious about how an adult evaluated their own drawing compared to a drawing made by an unknown peer, while ruling out possible alternative explanations (Experiments 1–3). Critically, this curiosity was modulated by children's uncertainty about their performance (Experiment 4), suggesting that children's preference for the self reflects genuine information-seeking rather than an overall preference for any self-relevant information or a desire to receive positive feedback. These findings provide evidence for an early-emerging curiosity about what others think about the self.

**This Repository**

`code/`: Scripts used to process, analyze, and visualize data in the paper

`data/`: Data from all four experiments of the paper

### Experiment 1 (`sc_study1_final.csv`)

| Column | Description |
|---|---|
| `id` | SC_Study1_XX |
| `age` | Age (in years) |
| `gender` | M (Male), F (Female), Other, or NA |
| `condition` | 0 (Other condition), or 1 (Self condition) |
| `exclude` | 0 (Include), or 1 (Exclude)|
| `exclude_reason` | Reason for exclusion (in free response) |
| `peeked` | 0 (did not peek) or 1 (peeked) |
| `time` | For children who peeked, time to peek (in seconds); NA if they did not peek (censored at 180 s in analyses) |
| `protocol` | Version_1 or Version_2 (see paper for details) |

### Experiment 2 (`sc_study2_final.csv`)

| Column | Description |
|---|---|
| `id` | SC_Study2_XX |
| `age` | Age (in years) |
| `gender` | M (Male), F (Female), Other, or NA |
| `race` | White, Asian, Black, Hispanic/Latino, Multiracial, Other, or None given |
| `condition` | 0 (Other condition) or 1 (Self condition) |
| `drawing` | Tree or Bird |
| `exclude` | 0 (Include), or 1 (Exclude)|
| `exclude_reason` | Reason for exclusion (in free response) |
| `peek` | 0 (did not peek) or 1 (peeked) |
| `time` | For children who peeked, time to peek (in seconds); NA if they did not peek (censored at 180 s in analyses) |
| `notes` | Notes about participants (only one; who was erroneously excluded) |

### Experiment 3 (`sc_study3_final.csv`)

| Column | Description |
|---|---|
| `id` | SC_Study3_XX |
| `age` | Age (in years) |
| `gender` | M (Male), F (Female), Other, or NA |
| `tracing` | Bird or Tree |
| `side_color` | Left_Yellow (participant tracing was placed in a yellow folder, evaluated first, and placed on the left side of the table), or Right_Green (participant tracing was placed in a green folder, evaluated second, and placed on the right side of the table)|
| `exclude` | 0 (Include), or 1 (Exclude)|
| `exclude_reason` | Reason for exclusion (in free response) |
| `choice` | 0 (Jordan's folder), or 1 (Self folder)|

### Experiment 4 (`sc_study4_final.csv`)

| Column | Description |
|---|---|
| `id` | SC_Study4_XX |
| `age` | Age (in years) |
| `gender` | M (Male), F (Female), Other, or NA |
| `condition` | 0 (Low Uncertainty condition), or 1 (High Uncertainty condition)|
| `color` | Yellow or Green (folder color that children's tracing was placed inside of)|
| `exclude` | 0 (Include), or 1 (Exclude)|
| `exclude_reason` | Reason for exclusion (in free response) |
| `choice` | 0 (Jordan's folder), or 1 (Self folder)|
| `check_question` | 0 (child did not pass any of the four check questions), 1 (child passed at least one of the check questions), or NA (not recorded; the child did not complete the study or there was a tech error) |

`figs/`: Figures from the paper, and plots from the analysis file.

`preregistrations/`: PDFs of the preregistrations for Experiments 2–4 (Experiment 1 was not preregistered)