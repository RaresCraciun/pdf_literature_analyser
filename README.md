# pdf_literature_analyser
At the moment this tool automates the detection of hardware (Crazyflie versions, decks, sensors) and software (ROS, Crazyswarm, Simulators) within PDF academic papers using regex-based pattern matching.

This tool can be adapted easily to other topics of interest.

## Features
- **Interactive Validation**: Prompts the user to accept/reject matches based on context.
- **Incremental Progress**: Saves results to CSV after every file to prevent data loss.
- **Styled Reporting**: Generates a formatted Excel report for final analysis.

## Installation
```bash
pip install -r requirements.txt
```
## Citing this code

If you use this software in your research, please cite it as follows:

APA: Crăciun Rareș. (2025). _PDF literature analyser_ (Version 1.0.0) [Computer software]. GitHub. https://github.com/RaresCraciun/pdf_literature_analyser

BibTeX: @software{Craciun_PDF_Literature_Analyser_2025,
  author = {Crăciun, Rareș},
  title = {{PDF literature analyser}},
  month = dec,
  year = {2025},
  publisher = {GitHub},
  version = {1.0.0},
  url = {https://github.com/RaresCraciun/pdf_literature_analyser}
}
