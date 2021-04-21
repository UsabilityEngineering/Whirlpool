# Phase 2: Interaction Design

## Wireframes

This page contains screenshots of our wireframes. Each screen is represented here, however in the prototype some screens have duplicates to allow for a full interactive experience. We will describe why we chose to include each screen below.

The screen below is the starting page for our mobile app. The bottom navigation bar is how users will traverse the different sections of our app. The "Res" section is used to reserve machines at different laundromats, the "Home" section is where users can add machines and monitor their progress, and the "Stats" section is for users to see different statistics about their laundry habits.

![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/home.png?raw=true)

If a user wants to reserve a machine, they can click on the "Res" section of the navigation bar. The first area of the "Res" section contains a search bar to look for laundromats nearby, it also has a list of previously used laundromats to save the user some time if they go to the laundromat often. The stars next to the store names represent the users favorite stores. Users can toggle their favorites so they will always go to the top of the recents list, making it easy for them to select their most used laundromats.

![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/stores.png?raw=true)

Once the user selects a store, it opens up that specific store's information. Included in this information is a map of the store that will be color coded to show open and occupied machines. We included a map because it adds a level of convience for the user, they do not have to walk around the store to find their machine, we show them right where it is. Below the map is a list of open machines, the user can select which machines they need in order to reserve them. Once they select their machines and click Done, the users machines will be reserved for one hour and they are redirected to the home page. The reservation page is shown below:

![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/reserve.png?raw=true)

If a user has already reserved machines in one store, they will not be allowed to reserve more machines at a different store. They are still able to view the other stores and their availability, however if they go to the reserve page it will not let them reserve more machines, this view is shown below:

![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/no_reserve.png?raw=true)

Users are not required to reserve any machines, however it will ensure that there will be machines ready for them when they get there. Whether the user reserved a machine or not, they will add the machine to their list in the same way. To add a machine, the user must simply press the plus button on the home page and take a picture of a QR code on the machine of their choice. The view of what this looks like is shown below.

![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/pic_screen.png?raw=true)

We decided to do the adding of machines this way because it is simple and easy. From our user research data, we learned that some of our previous features were seen as too complicated and confusing to use. Our users said they would prefer starting their laundry to be quick and easy rather than complicated with extra features, so that is what we went with here. Along with that, our personas helped us realize that not everyone who uses this app will be very tech savvy, so taking a picture of a QR code and letting the computer do the work is the best way to avoid any human errors.

Once a machine's QR code has been scanned, it will be added to the home page to track its progress. From our user research, we learned that over half of our research participants use a timer to keep track of their laundry. That inspired us to create this progress chart which tells the user how close their laundry is to being complete. This view is shown below:

![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/washer_home.png?raw=true)

If something happens and the user needs to stop their laundry, they can click the minus button to stop their machine at any time. If the users need more than one machine, they can simply press the plus button again and scan another machine. If this user required a drier as well, this is what it would look like after scanning the driers QR code:

![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/washer_prenotif.png?raw=true)

We decided to average out the progress of each machine for the progress chart rather than having separate charts for each machine. We believe this makes the design more simple and gives a better overarching view of when all the laundry will be complete.

Typically, the big red circle that says "Simulate Notification" will not be there. This is there in order to simulate what would happen when a machine finishes its cycle. Once a users machine is done, it will send them a notification that looks like this:

![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/washer_notif.png?raw=true)

The notification will alert the user that their machine is done and that they need to return to get their clothes. We decided to include this because the majority of our users said that they leave the laundromat once they start their laundry. Since most users will not be around when their machines are complete, we thought this was the perfect way to alert them that their laundry is done and they need to get back. This helps save the user some time, but it also will help the laundromat to keep their customers cycling in and out quicker which makes them more money. This idea was also specifically inspired from our scenario with Gina. Gina is a stay at home mom and is always on the move, so forgetting about laundry would be very easy to do. A notification would help to remind her about her laundry while she's running around taking care of her children.

We also have wireframes that simulate the rest of this user's interaction. The pictures below show what that would look like:

![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/dryer_prenotif.png?raw=true) ![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/dryer_notif.png?raw=true) 
![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/home.png?raw=true)

Once all of the users machines are completed, the user will be returned to the home page to add more machines if necessary. We designed it this way because in our user research, we learned that most users will do multiple loads in one day and this makes it easier for them to do this.

Lastly, we have our "Stats" section that can be accessed from any other page. This section helps the user to learn about their habits doing laundry, such as their most visited store or average time spent doing laundry. We included this section because we learned from our user research that most people who use laundromats are students or low income families. We felt like these types of users would be interested in things like how long they take or how much they spend typically at the laundromat. 

![alt text](https://github.com/UsabilityEngineering/Whirlpool/blob/master/phase2/Pictures/stats.png?raw=true)

Overall, we designed our wireframes to be as simple and user friendly as possible while still considering our user research data and personas/scenarios. We believe that this design is easy to use and includes several design aspects that will make it simpler for our target audience to use.

## Supplementary Materials

[Comprehensive Wireframes](https://github.com/UsabilityEngineering/Whirlpool/blob/master/wireframes.md)

[Prototype Draft](https://xd.adobe.com/view/72935f84-d459-4b12-a4e3-f2c125af0e65-27c0/)

