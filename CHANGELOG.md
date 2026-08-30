# Changelog

All notable changes to this project will be documented in this file.

## v0.1.0 - Initial Public Draft

### Added

- Initial MiniMax H3 Reference-to-Video prompt guide
- GPT instructions for structured R2V prompt generation
- Master instructions for prompt conversion rules
- Reference writing guide
- Basic R2V example
- Motion Context continuation example
- Multi-subject consistency example
- Six-section output format:
  - `subject_definitions`
  - `summary`
  - `retention_analysis`
  - `detailed_description`
  - `overall_soundscape`
  - `non_diegetic_music`

### Validated Behaviors

- Japanese input to English prompt conversion
- Japanese dialogue preservation
- Explicit preserve / change / remove instructions
- Motion Context continuity without replaying completed dialogue
- Scene transitions while preserving subject identity
- Multiple subject identity separation
- Reference-image role separation
- Conservative completion of missing scene details
- No extra preamble outside the six required output sections

### Status

This is the first validated draft intended for further testing and refinement before a stable v1.0 release.
