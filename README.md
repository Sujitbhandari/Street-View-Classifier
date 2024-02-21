# Street-View-Classifier

This applies deep learning to identify the location of an image taken at a random location in a city using the Google StreetView API.

This project is based on the game GeoGuessr, where the player's goal is to guess where they are based on a Google StreetView photograph from a random location in the world.

It retrieves an updated list of the biggest US cities first, and then it uses a Google Maps StreetView API query to download pictures from randomly selected locations inside the biggest n cities. It discovers what important attributes set the cities apart using a pretrained deep learning picture categorization model.

It attempts to categorize from an image of a random location in a city after seeing it.
