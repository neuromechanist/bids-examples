# EMG Concentric Needl Example

This dataset demonstrates documentation of a concentric needle EMG recording:
- Invasive EMG
- Single channel (bipolar) concentric needle

## Dataset Structure

The dataset includes a single subject with a custom bipolar EMG setup:

```
emg_concentricNeedle/
├── dataset_description.json
├── participants.json
├── participants.tsv
├── README.md
└── sub-01/
    └── emg/
        ├── sub-01_task-psaExamination_channels.tsv
        ├── sub-01_task-psaExamination_emg.edf
        └── sub-01_task-psaExamination_emg.json
```

## Recording Details

- **Electrode Setup**: Concentric needle EMG recording from the abductor digiti minimi (ADM)
- **Task**: Sponatneous muscle acivity screening
