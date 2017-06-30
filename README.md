# CinemaNet
Cinematic Shot type data set with data, labels, conversion scripts for Tensorflow to TFRecord format.

Early stages of a data set of neural network classification of various cinematic shot type / taxonomies.

### Requirements: 
* Tensorflow 1.1 or better
* Python
* Automator on OS X for image conversion because im lazy and it just works™

If you add photos, or labels, run the automator script on your 'original photos' (containing sub folders for your label category). It will produce a 'converted_photos' folder with JPG images sized/cropped for 244x244 in hopes to be used for MobileNet training. 

### Contribution

Hit me up with ideas, images, or notify me of mis-labels please.

Currently exploring taxonomies for Framing, Shot Type, and Shot Angle. I want to stay away from too specific taxonomies and would rather explore more generally useful taxonomies. This is not intended to be a perfect taxonomy fit for everyone, but generally useful and an exploratory first start.

So far, I have data for Framing, need more data for Type, and have yet to delve into Angle. Current Taxonomy breakdown as follows: 

### Framing
* Close Up
* Extreme Close Up
* Extreme Long Shot
* Long Shot
* Medium

## Type
* Master
* Two Up
* Over the Shoulder

## Angle
* Aerial
* High
* Low
* Tilted


### Found Footage data sets:

Currently grabbing data from the web - citing fair use for building models. If you see your a frame you dont want me to use, tell me, and i' might not tell you to fuck off.
