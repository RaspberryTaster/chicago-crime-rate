# Chicago Crime Predictor

## Overview

This project applies a machine learning model to predict crime trends in Chicago, leveraging data from the Chicago Police Department's CLEAR system.

## Data Description

The dataset, covering 2001-2017, comprises:

- `ID`: Record unique identifier.
- `Case Number`: Incident-specific RD Number.
- `Date`: Incident date.
- `Block`: Incident location.
- `IUCR`: Crime reporting code.
- `Primary Type`: Main IUCR code description.
- `Description`: IUCR subcategory.

## Prerequisites

- Python 3.7.16
- Jupyter Notebook

## Setup Instructions

1. Install Python 3.7.16.
2. Install Jupyter Notebook (`pip install notebook`).
3. Clone the repository.

## How to Use

1. Open the terminal.
2. Run `jupyter notebook`.
3. Navigate to and open the notebook file.

## Screenshots

![Two Year Prediction](/TwoYearPrediction.png)

*Fig 1: Prediction model output.*

![Crime Types and Counts](/TypeOfCrimeAndCount.png)

*Fig 2: Overview of crime types and their counts.*

![Annual Crime Data](/CrimesPerYear.png)

*Fig 3: Yearly crime data visualization.*

## Contributing

Fork the repo and submit pull requests for improvements.

## License

[MIT License](LICENSE.md)
