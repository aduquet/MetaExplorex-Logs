# Logs-v1

This folder contains logs and transformed inputs for metamorphic testing using the MetaExploreX tool.

## Contents

- `MR_input_transformation/`: This subfolder contains the inputs generated and the transformations for each of the six Metamorphic Rules (MRs) that we are working with.
- `SUT_outputs/`: This subfolder contains 50 files - 25 in JSON format and 25 in CSV format. These files represent the outputs of 25 different methods used as a System Under Test (SUT). The inputs for all these methods are the same and can be found in the `MR_input_transformation` subfolder.
- `cleaned_output/`: This subfolder contains the MR status, i.e., whether the SUT violates or not the MRs, for each of the 25 methods tested. There are 25 CSV files in this subfolder, one for each method.

## Usage

This folder is intended to be used with the MetaExploreX tool for visualizing and exploring the outcomes of metamorphic testing.

