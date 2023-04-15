# Global Methane Emissions Analysis
Brief exploration into world methane emissions, and it's breakdown by type, segment, and country.

## Data
The data for this analysis was obtained from Kaggle, found [here](https://www.kaggle.com/datasets/ashishraut64/global-methane-emissions).
- The license for this data is [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/).

The raw data consists of the following columns:
1. __region__ - Divides countries into larger groups.
2. __country__ - Country of emission.
3. __emissions__ - Methane emissions in kt.
4. __type__ - Sector from which emissions occur.
5. __segment__- Sub-sector from which emissions occur.
6. __reason__ - The reason for emission.
7. __baseYear__ - Base year for the tracking of emissions.
8. __notes__ - The source of data.

Upon first exploration of the data, I decided to drop the notes column. I determined that while the information contained is valuable, it is not relevant to the analysis. In addition, only 671 of the 1548 available rows (43.3%) were populated with useful data.

## Analysis
Provide a summary of the analysis performed, including any key insights or findings.

## Requirements
I relied on many tools in this project, namely Jupyter Notebook, Kaggle, and Python. Within Python, I employed several libraries:
* Pandas
* NumPy
* Plotly.express
* Matplotlib

## Files
List the files included in the project and briefly describe their contents.

## Usage
Provide instructions on how to run the code and reproduce the analysis.

## Credits
List any resources used in the analysis or referenced in the project.

## Authors
List the authors of the project and provide contact information.

## Acknowledgments
Thank any contributors or organizations that helped with the project.
