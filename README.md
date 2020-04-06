# Millicast-Audio-Video-Multiple-Users

This project requires a MIllicas.com account. 
https://millicast.com/

1. In your Millicast portal(+) Add a new token M
Make sure to select Usw ANY name!!!!!!

With these files.
1. Open the JS/Publisher.js file.
2. Open the JS/viewer.js file.
EDIT THE FOLLOWING

   // hard code it here, or enter it at runtime on the field.
   let params = new URLSearchParams(document.location.search.substring(1));
   let accountId = 'YOURID'; //let accountId ADD YOUR ACCOUNT ID HERE
   let streamName = params.get('id');
   let token ="YOUR_TOKEN";
   console.log('Millicast Viewer Stream: ', streamName);

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

   let player1 = "https://viewer.millicast.com/v2?streamId=YOURID/live1";
   let player2 = "https://viewer.millicast.com/v2?streamId=YOURID/live2";
   let player3 = "https://viewer.millicast.com/v2?streamId=YOURID/live3";
   let player4 = "https://viewer.millicast.com/v2?streamId=YOURID/live4";

 Your ready to stream and customize your way.  
