# JKYouTubeActivity

JKYouTubeActivity is a simple Android activity to load YouTube videos into a VideoView using their RTSP url. Exception handling could be better, but for not it is what it is.

## Usage

To use JKYouTubeActivity simply include the `com` folder from the `src` folder into your applications `src` folder, then import the class `import com.joshuakendall.youtube.JKYouTubeActivity;` and finally start the activity:

    Intent intent = new Intent(null, Uri.parse("YOUR_VIDEO_ID_HERE"), this, JKYouTubeActivity.class);
    startActivity(intent);
    
## Contribute

I don't claim to be an great Java or Android developer; I figure things out by trying them, so there may be a better way to do something in this Activity. If you have suggestions, changes or bug fixes; fork this repo, make your changes and send me a pull request.