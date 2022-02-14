# Fire-Emergency

Getting co-ordinates : navigator.geolocation.getCurrentPosition(callbackfunction)

Getting location : if (navigator.geolocation) { //check if geolocation is available
                navigator.geolocation.getCurrentPosition(function(position){
                  console.log(position);
                });   
            }
