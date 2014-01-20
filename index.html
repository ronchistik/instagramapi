<!-- Created by Ron Chistik
     Example: Instagram API feed call using JSONP
     Version 1.0
 -->

<!DOCTYPE html>
<html lang="en">
    <head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
    <title>Instagram API</title>

        <script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.2/jquery.min.js"></script>
        <script>
            $(document).ready(function(){


                //Insert your instagram access_token here
                var access_token = "";

                //This will be your search query
                var search_term = "cats";

                //This is the URL that is being called in instagramCall()
                var apiPoint = "https://api.instagram.com/v1/tags/" + search_term + "/media/recent?access_token=" + access_token + "&callback=callbackFunction";

                //Calling Function
                instagramCall();

                //AJAX call, fetching images     
                function instagramCall() {
                    $.ajax({
                        url: (apiPoint),
                        dataType: 'jsonp',
                        success: function(dataWeGotViaJsonp){

                            //Declaring variables
                            var testimage;                                
                            var imageurl = "";
                            var text = '';
                            var len = dataWeGotViaJsonp.data.length;

                            //Looping through all images on individual page
                            for(var i=0;i<len;i++){
                                instagramEntry = dataWeGotViaJsonp.data[i];

                                imageurl = instagramEntry.images.thumbnail.url;
                                testimage=document.createElement("img");
                                testimage.src = imageurl;

                                //Appending images to #instagramFeed div
                                $("#instagramFeed").append(testimage);
                                                        
                            }
                                    
                        }
                    });
                }     
            })
             
        </script>
    </head>
    <body>
        <div id ="instagramFeed"></div>
    </body>         	
</html>