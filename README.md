# Social
#### Note: The current library runs on Node/Express server with the possibility of porting to Django in the future. Other Social Media platforms soon to come. Contributions are always welcome.

### Required
1. NodeJS
2. Python 3.0+

### Usage
1. In your terminal, in the "**social**" directory, type: `$ npm install`<br><br>
2. Run the node server through your terminal by using the "share.js" file.<br><br>
3. Import this library in your program by typing:<br>
   ```python
   from social.share import *
   ```
4. Instantiate the social media class name. Eg:- `twitter = Twitter()`<br><br>
5. Authorize the app by accessing the "authorize()" method in social media class. Eg:-
   ```
   facebook = Facebook()
   facebook.authorize()
   ```
6. Use "&lt;social media instance&gt;.postImage(&lt;image path&gt;)" to post images. Eg:- `facbook.postImage("./sample_image.jpg")`<br><br>
7. Use "&lt;social media instance&gt;.postVideo(&lt;video path&gt;)" to post videos. Eg:- `twitter.postVideo("./sample_video.mp4")`

#### Example file "example.py" is included with sample image to experiment.
