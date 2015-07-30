# eyeglass-image-dimensions
An eyeglass module aimed at providing sass the same image dimensions functionality found in ruby compass.

Setup:

Right now there isn't an npm package so you'll need to manually download and add it to your project's node_modules folder then run npm install to bring down dependancies.
Then add the following to your sass file/s:

```
@import 'eyeglass-image-dimensions';
```

## Usage

### image-width
returns the width of the image in pixels.

```
width: image-width($image);
```

### image-height
returns the height of the image in pixels.

```
height: image-height($image);
```
