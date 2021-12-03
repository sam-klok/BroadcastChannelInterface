If we need to communicate between browser tabs, 
let's use BroadcastChannel API 

Based on example:
https://www.digitalocean.com/community/tutorials/js-broadcastchannel-api

Links to read:
https://developers.google.com/web/updates/2016/09/broadcastchannel
https://developer.mozilla.org/en-US/docs/Web/API/Broadcast_Channel_API

Using JavaScript Anonymous Closure
https://stackoverflow.com/questions/16032840/javascript-anonymous-closure


    function hello() {
        alert("Hello");
    }

    hello()

same as:

    (() {
        alert("Hello");
    })()