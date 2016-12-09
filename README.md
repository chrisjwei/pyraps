###15-388 Final Project

Group Members:
    * Stephen Chung (spchung)
    * Vincent Liu (vincentl)
    * Chris Wei (cjwei)

To run our code, make sure you have lyrics.pickle in the project directory. Also, if you want to run our code that actually makes calls to the Musixmatch api, you have to create a file called secrets.json that has a key-value pair of your api key that you get from registering on MusixMatch. Be sure to uncomment the portion of code that does make these calls.
    
Your secrets.json should look like:

{ 
    "musixApiKey" : "{key}"
}

NBViewer link: http://nbviewer.jupyter.org/github/chrisjwei/pyraps/blob/master/pyraps.ipynb

Links to the larger files: https://drive.google.com/open?id=0By3ZIyMOGGqwaE1FdG5QRldFaWc
    - Just put all these files in the same directory as the notebook.

References:

* https://developer.musixmatch.com/documentation/
    Api usage referenced from the Musixmatch api documentation. Song lyrics generated from making calls to the Musixmatch api.

* https://github.com/fchollet/keras/blob/master/examples/cifar10_cnn.py
    Our neural network implementation was based off of this example.

* https://keras.io/getting-started/sequential-model-guide/
    Used the Keras documentation to help us with creating our convolutional neural network.
