# EV_charging_station_car_detection

Project's goal is to detect if there is a car charging or not at the moment.

Charging station location: Elektrenu EV 2, A1 45,86km
Source: https://eismoinfo.lt/#!/vkr/4044

EV_charging_station_car_detection_load_model.ipynb - main file for scrapping one image, loading and predicting.
Scrapper is used to take latest photo from the source.

Then model is loaded and prediction is set.
Trained model - CNN model with 4 layers.

Best results achieved at:
image_size = (128, 128)
epochs = 20
batch_size = 32
threshold = 0.5

After prediction - image is printed and prediction is stated on the image.
