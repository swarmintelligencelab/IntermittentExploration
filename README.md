# Collective intermittent exploration in fish schools is mediated by visual cues

This repository contains the data used for the analysis and modeling of fish collective behavior in the study: "Collective intermittent exploration in fish schools is mediated by visual cues"
by Deze Liu and Daniel Burbano.

#Repository Structure
The repository includes a folder with six subfolders, each corresponding to an experimental condition:

- Singles-Bright: Single fish in a bright environment
- Singles-Dark: Single fish in a dark environment
- Pairs-Bright: Pair of fish in a bright environment
- Pairs-Dark: Pair of fish in a dark environment
- Triads-Bright: Triad of fish in a bright environment
- Triads-Dark: Triad of fish in a dark environment

Each subfolder contains CSV files of the time-series data of the experiments for the respective condition.
The CSV files include the following columns:

Frame: Frame index
Time: Timestamp in seconds
X_Arena0_Ind0: X-coordinate of fish 1 in the arena
Y_Arena0_Ind0: Y-coordinate of fish 1 in the arena
X_Arena0_Ind1: X-coordinate of fish 2 in the arena (for experiments with two or more fish)
Y_Arena0_Ind1: Y-coordinate of fish 2 in the arena (for experiments with two or more fish)
For experiments involving three fish, additional columns are included for the third fish's coordinates.

#Usage
The data is provided for replication of the analysis and modeling described in the study. Please refer to the original paper for detailed methodology and results.

