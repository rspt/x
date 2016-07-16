# x - os - ios - gps spoofing

On iOS you can spoof your GPS to change your location or follow a predetermined
path.

You need:

*   [XCode](https://developer.apple.com/xcode/)
*   The device you want to spoof

## Procedure

*   Plug your device to your computer with XCode

*   Open XCode and create a new XCode project using `Simple View Application`
    template

*   Run the project on your device

*   Once the project is running on your device, you can simply put in in the
    background

*   Ax the bottom of Xcode, you'll find a direction icon. If you click on it,
    you'll see a list of geolocation you cans poof your device with. You can
    choose one, the icon turn blue and if you go to your map app on your device,
    your location is updated.

*   If you want to follow a path, you can import a `.gpx` file and use it the
    same way you've changed your location before.

## Generating GPX file

*   Generate a path on [Google Maps](https://www.google.ch/maps)

*   Copy the URL from Google Maps

*   Go to [MapsToGPX](https://mapstogpx.com/mobiledev.php) (or
    [here](https://mapstogpx.com/pokemon.php) if you're playing Pokemon Go),
    paste the link, choose the time needed to perform the path and download the
    GPX file
