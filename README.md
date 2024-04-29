# SMART Model

Source code to fit SMART model to the data for the paper `Quantifying the hierarchical scales of scientists' mobility`.

To run the code, please follow the steps below:
- Download the data from the following link: https://drive.google.com/file/d/1vHE3JhLxSj3xIo-Hs6pIrSnOoIPR4TW-/view?usp=share_link. 
- Unzip the data and place it in the `data` folder.
- Run the `estimate_attractiveness.ipynb` notebook to fit the model and obtain the attractiveness of each city, country, and continent in the `data/attractiveness_cities.xlsx``, `data/attractiveness_countries.xlsx` and `data/attractiveness_continents.csv` files.
- Run the `estimate_p(d).ipynb` notebook to fit the model and obtain the probability of traveling for a certain level distance in the `data/level_distance.xlsx` file.
- You could also run other ipynb files to obtain data visualization and other results.