# Mathematical Modelling of Vehicle Fuel Consumption and Road Trip Costs

**Mathematics and Python – Final Exam Project**

## Project overview

This project uses mathematical modelling and Python to investigate how driving speed may relate to vehicle fuel consumption and how estimated consumption can be used to calculate the fuel cost of a road trip. It compares linear and quadratic regression, examines model errors using leave-one-out cross-validation, and applies the selected model to journey-cost and scenario calculations.

## Important note about the data

The five speed/consumption observations describe a **hypothetical vehicle** and are illustrative values created for this project. They are not measurements from a real car, manufacturer test figures, or data copied from the cited research. The numerical results demonstrate a modelling process and should not be interpreted as verified predictions for a real vehicle.

## Project contents

- `fuel_consumption_project_final_review.ipynb` — the complete Jupyter Notebook, containing Chapters 1–10, calculations, visualisations, model evaluation, conclusion, acknowledgements and references.

## Requirements

- Python 3
- Jupyter Notebook or JupyterLab
- NumPy
- pandas
- Matplotlib

## How to run

1. Download or clone this repository.
2. Open `fuel_consumption_project_final_review.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the notebook from the first cell, in order.

## Scope and assumptions

The model represents one hypothetical compact petrol hatchback and focuses on fuel costs only. It assumes constant-speed observations and simplified conditions. It does not include tolls, vignettes, parking, maintenance, depreciation, traffic variation or changes in road gradient. The notebook discusses these limitations in more detail.

## Sources

- U.S. Department of Energy (2022), [Slow Down to Save Fuel: Fuel Economy Decreases About 27% When Traveling at 80 mph Versus 60 mph](https://www.energy.gov/cmei/vehicles/articles/fotw-1240-may-30-2022-slow-down-save-fuel-fuel-economy-decreases-about-27).
- U.S. Department of Energy (2020), [Light-Duty Vehicles Use More Gas at Speeds Above 50 Miles per Hour](https://www.energy.gov/cmei/vehicles/articles/fotw-1155-october-12-2020-light-duty-vehicles-use-more-gas-speeds-above-50).
- U.S. Environmental Protection Agency, [Your Mileage May Vary](https://www.epa.gov/greenvehicles/your-mileage-may-vary).

These sources provide background information about fuel economy and factors affecting it. They are not the source of the project's five illustrative data points.

## Acknowledgements and use of AI

ChatGPT by OpenAI was used during initial brainstorming to help generate and refine the project idea and research question. It was also used as a supporting tool during project planning, explanations and review of notebook structure and wording. AI-assisted suggestions and material were reviewed and adapted for the submission; the author is responsible for the final content and conclusions.

## Libraries

This project uses [NumPy](https://numpy.org/), [pandas](https://pandas.pydata.org/) and [Matplotlib](https://matplotlib.org/).
