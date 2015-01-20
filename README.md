# catch_bus

Mobile App that helps on the process of getting to a 
stop/station, waiting and boarding.

Hi

First of all we are more than happy to  improve this app I even if that means 
the entire idea does not work or there is already a solution for this, we do not 
want to re invent the wheel ), if you have any other solution, please do not 
hesitate to share with us

---

This is a POC of a mobile app (for Android and iOS systems) to help the users of
public transportation on the procees of getting to a stop/station, waiting and 
boarding: 

        -> Did I miss the bus[1]? 
        -> How much time do I have to wait on this stop? 
        -> And some other questions when we use public transportation

Workflow: 

The main idea is to track the position of the bus and show it to the users. The 
base idea of this app is the "check-in" , why ? well because there we can not 
force the companies to always install GPS's on their systems :) 

1) Each user install the app on their smarthphones
2) The app has official stops and schedule (where and when the bus should stop)
3) The users subscribe to the route he/she wants to follow
4) User asign the stop he will use ( i.e. morning stop to go the office)
5) The first user to pick the bus do the check in[2]: 
        *) The user open the app
        *) The app ask you if you want to do a check in or just track:
                You choose check in
        *) The app (with data and gps conection) shows the current stop and ask
           if the user want to do a check in ( one click to do the check in )
        *) User keep with the regular trip :)
6)Next user open the app and check the status of the buss: 
        *) The user open the app 
        *) The app ask you if you want to do a check in or just track:
                You choose track
        *) The app (with data and gps conection) shows the current stop in a map
        with the rest of stops as: 
                *) Arrived: Someone has done a check in on that stop or on 
                another stop ahead of this
                        The app shows the time someone has done a check in
                        or the estimated time the bus should have arrived there 
                        ( calculated by the last check in and google trafic )
                *) Waiting: No one has done a check in on that stop or on 
                another stop ahead of this. If 
                        The app shows the estimated time the bus should arrive
                        there (calculated by the last check in and google 
                        trafic )
                
7) We all enjoy the trip


TODO:

        -> Encourage the community!!!:
                Talk to companies to encourage people to do the check in with 
                gifts ie: 
                        every 100 check ins go for the rafle of a tablet,
                                 well ...
                        lets say a nice usb ok ? :) 
        
        -> Make it smart (we try to solve problem in [2])!!!
                In a close future the user might have the option to do check ins
                using: 
                        -> traffic layer:
                                https://developers.google.com/maps/
                                documentation/javascript/examples/layer-traffic
                        -> geolocation: 
                                https://developers.google.com/maps/
                                documentation/business/geolocation/
                                
                        -> Collaborating :) 
        -> Have fun :) 

                        
[1] Asumming bus for this example
[2] Yes you are right, if you are the first one to catch the bus you might be 
wondering why this crapy app did not thinking in you, hold we are working on it
