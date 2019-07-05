# OpenFace_By_TadasBaltrusaitis

  

## Ubuntu18.04    mini

https://github.com/TadasBaltrusaitis/OpenFace/wiki/Unix-Installation    


### download the release version[ 2.1.0]

[OpenFace 2.1.0](https://github.com/TadasBaltrusaitis/OpenFace/releases)


### donwload models

```
./download_models.sh
```

### build


```
install.sh
```
### test

*   Test it with

    *   for videos:

        `./bin/FaceLandmarkVid -f "../samples/changeLighting.wmv" -f "../samples/2015-10-15-15-14.avi"`

    *   for images:

        `./bin/FaceLandmarkImg -fdir "../samples/" -wild`

    *   for multiple faces in videos:

        `./bin/FaceLandmarkVidMulti -f ../samples/multi_face.avi`

    *   for feature extraction (facial landmarks, head pose, AUs, gaze and HOG and similarity aligned faces):

        `./bin/FeatureExtraction -verbose -f "../samples/default.wmv"`






-----

## Windows   

https://github.com/TadasBaltrusaitis/OpenFace/wiki/Windows-Installation 
