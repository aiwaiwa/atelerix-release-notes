## **BOM Eyes** Update _Coming soon!_

The BOM Eyes group gift will soon receive an update for all members.\
This update will include the long-requested abilities to perform:

* Vertical texture shift
* Individual scaling options for both horizontal and vertical adjustments.


## Lost Attachments SL Bug _Fixed!_
> Dates: 10/8/24, 10/11/24, 10/25/24 \
> Authors: [Salt Thistle](https://my.secondlife.com/salt.thistle), [Aiwaiwa Hurricane](https://my.secondlife.com/aiwaiwa.hurricane)

> Thank you for [upvoting the issue](https://feedback.secondlife.com/server-bugs/p/attachment-loss-on-rc-channel-2024-08-2910619830788).\
> Linden Lab took the issue seriously and **announced on 10/25/24 that it has been fixed**. The original article may still be useful, so we will keep it available.

If you've recently been having trouble with your attachments disappearing or not responding upon arrival in new sims, 
press `Alt-Shift-R` upon arriving. This will refresh/reset your attachments and should resolve the issue.

> Noticing this visually might be tricky, because everything may look fine to you, but others around you will see the problem.


### Workaround

The lost attachments bug in Second Life servers seems to particularly affect attachments assigned to the same attachment point.
Until this bug is fixed, _reassign attachments_ to points that have nothing else assigned.

Which points should you choose?

For rigged mesh, take note of the number in parentheses after the attachment point name in Firestorm.
The lower the number, the higher the priority the attached item gets during rendering.\
Therefore:

* It's good to assign the _Head_ to a **higher-numbered** attachment point, like **Right Wing (46)**,
since, from the user's point of view, the head is the ‘farthest’ surface on the avatar.
* Anything positioned closer from our point of view that contains alpha, like _Hair_, should be attached to a lower-numbered point, ideally the lowest, like **Skull (2)**.\
Since there is typically nothing else in front of the rigged hair, this will ensure it is rendered with priority in front of any other attachments that might be added later.

![rendering_priority](https://github.com/user-attachments/assets/97985fc8-8fc2-4d8a-8799-7ef69151312b)

> We will be preassigning different attachment points when we release our items to help address this issue.

* In the meantime, `Alt-Shift-R` upon arrival to another sim!



