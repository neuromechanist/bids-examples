# EMG combined invasive and surface EMG

This dataset demonstrates simualtaneous iEMG and sEMG recordings:
- Heterogeneous electrodes
- High-desnity invasive EMG
- Custom electrodes

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
        ├── sub-01_task-XX_channels.tsv
        ├── sub-01_task-XX_emg.edf
        └── sub-01_task-XX_emg.json
```

## Recording Details

- **Electrode Setup**: A custom HDiEMG thin-filament electrode is inserted into the tibialis anterior muscle, while a HDsEMG array records from the body surface (on top of the same muscle)
- **Task**: Isometric ramp-and-hold contractions
- **Custom HDiEMG thin filament electrode**:
  - Thin film structure: U-shaped structure with a length of 70 mm, widths of 0.65 mm (electrode filament) and 0.15 mm (guiding filament) and a thickness of 0.015 mm 
