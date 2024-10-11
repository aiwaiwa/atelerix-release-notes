## Lost Attachments SL Bug (Part 2)
> Date: 10/8/24\
> Author: Aiwaiwa Hurricane

If you've been having trouble with your attachments disappearing or not responding upon arrival in new sims, 
press `Alt-Shift-R` upon arriving. This will refresh/reset your attachments and should resolve the issue.

### However...

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

> We will be preassigning different attachment points when we release our items to help address this issue.

* In the meantime, `Alt-Shift-R` upon arrival to another sim!
* [Upvote here](https://feedback.secondlife.com/server-bugs/p/attachment-loss-on-rc-channel-2024-08-2910619830788) to help push for a permanent fix.



