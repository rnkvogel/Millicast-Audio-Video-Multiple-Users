# Millicast-Audio-Video-Multiple-Users

This project requires a MIllicast.com account. 
https://millicast.com/

1. In your Millicast portal(+) Add a new token M
Make sure to select Use ANY name!

With these files.
1. Open the JS/Publisher.js file.
EDIT THE FOLLOWING

   // hard code it here, or enter it at runtime on the field.
   let params = new URLSearchParams(document.location.search.substring(1));
   let accountId = 'YOURID'; //let accountId ADD YOUR ACCOUNT ID HERE
   let streamName = params.get('id');
   let token ="YOUR_TOKEN";
   console.log('Millicast Viewer Stream: ', streamName);
   
DEMO

You can test this build using you millicast account and token.
https://rnkvogel.github.io/Millicast-Audio-Video-Multiple-Users/

EDIT THE FOLLOWING ON PUBLISHER JS.
1. Open the JS/Publisher.js file.
let token ="YOUR TOKEN GOES HERE";

   
  // hard code it here, or enter it at runtime on the field.
   let params = new URLSearchParams(document.location.search.substring(1));
   let accountId = 'YOURID'; //let accountId ADD YOUR ACCOUNT ID HERE
   let streamName = params.get('id');
   let token ="YOUR_TOKEN";
   console.log('Millicast Viewer Stream: ', streamName);

   let stream1 = "https://YOUR_WEB_SITE.com/multi/pub/?id=live1";
   let stream2 = "https://YOUR_WEB_SITE.com/millicast/multi/pub/?id=live2";
   let stream3 = "https://YOUR_WEB_SITE.com/millicast/multi/pub/?id=live3";
   let stream4 = "https://YOUR_WEB_SITE.com/millicast/multi/pub/?id=live4";



 Your ready to stream and customize your way.  
