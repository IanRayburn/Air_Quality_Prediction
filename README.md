# Air Quality Prediction
## About The Project

This project compares two types of time series forecast models. These models predict the amount of PM10 in the air. PM10 are particles that are less than or equal to 10 micrometers ([For more info click this link](https://www.epa.gov/pm-pollution/particulate-matter-pm-basics)). This is important to predict because these particles can be inhaled and if there are a lot of these particles in the air, it can be damaging to your health. This project compares a Prophet model and an Autoregression model. Prophet is a procedure for predicting time series data developed by Facebook’s Core Data Science team ([Prophet’s Website](https://facebook.github.io/prophet/)). Prophet is available as a package for both python and R. 


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/IanRayburn/Air_Quality_Prediction
   ```
2. Setup your env
  ```sh
  conda env create -f requirements.yml
  ```


## Results
 | Method                          | Accuracy | RMSE | MAE |
|---------------------------------|----------|------|-----|
| **Prophet** | **72%**  | **10.0212** | **8.749145** |
| Auto Regression | 66% | 11.0108 | 9.3131 |


## Usage

Use this space to show useful examples of how a project can be used. For course projects, include which file to execute and the format of any input variables.

Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_


<!-- Authors -->
## Authors

Your Name - [IanRayburn](https://github.com/IanRayburn) - ianrayburn5@gmail.com

Project Link: [https://github.com/IanRayburn/Air_Quality_Prediction](https://github.com/IanRayburn/Air_Quality_Prediction)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

You can acknowledge any individual, group, institution or service.
* [Catia Silva](https://faculty.eng.ufl.edu/catia-silva/)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)