
<!-- ABOUT THE PROJECT -->
## About The Project

This is Team CVP's solution to [NIH NCAT's Bias Detection Tools in HealthCare Challenge]( https://expeditionhacks.com/bias-detection-healthcare/)



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.


### Prerequisites

* Python 3.8
* Requirments are in `scripts\requirements.txt`


### Folder Structure
The script is using the following directory tree structure:
```/
├── scripts/           # This is where `measure_disparity.py` and `mitigate_disparity.py` are
├── input_model/       # Insert input model data here
├── reports/           # Location for the html report generated by the script
├── js/                # javascript for the team submission landing page 
├── css/               # css files for the team submission landing page 
├── assets/            # images for the team submission landing page 
```


### Installation

1. Clone this repo
2. Save a copy of the input in `input_model/` as `input_model.csv`. `input_model.csv` should include one row per individuals with columns below: 
* Model prediction (as a probability)
* Binary outcome (i.e. 0 or 1, where 1 indicates the favorable outcome for the individual being scored)
* Model label
* Sample weights
3. Execute the python file `python scripts\measure_disparity.py`
4. An html report will be generated in `reports\measure_report.html`
5. If the report shows bias, users can mitigate the bias by running `python scripts\mitigate_disparity.py`

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the BSD 3 License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

* Manpreet Khural - manpreetkhural@cvpcorp.com
* Cal Zemelman - calzemelman@cvpcorp.com
* Lauren Winstead - laurenwinstead@cvpcorp.com
* Wei Chien - weichien@cvpcorp.com
* Rose Anderson - roseanderson@cvpcorp.com


Project Link: [https://github.com/cvp-bias-detection-healthcare/](https://github.com/cvp-bias-detection-healthcare/cvp-bias-detection-healthcare.github.io/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
