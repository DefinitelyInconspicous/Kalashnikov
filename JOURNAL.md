---
title: "Kalashnikov"
github: "https://github.com/DefinitelyInconspicous/Kalashnikov"
description: "A billiards bot that uses an overhead camera to track the game and a physical cue stick striker\n\n"
created_at: "2026-11-01"
total_time: "2h 30m"
---

# November 1, 2026: Took measurements of table, Ideated on the cue stick piston
<!-- fabricate:entry 1785 -->

Took measurements and drew sketch of existing billiards table. Used trigo to calculate minimum FOV of camera + buffer. 

![](https://fabricate.hackclub-assets.com/8792068e6b87031ac225a72dd7117224d329d1e703da76f1ee90df719a41c6cf/image-jpeg/IMG_7902.jpeg)

Ideated on different ways to use a solenoid to push a cue stick onto the table. Both of the current ideas use the same support structure that surrounds the billiards table. These supports would be affixed to the table using 4 screws, 2 on each breadth of the table. A worry is that this would be insufficient to support the parts where the solenoid is on the length of the table, but I don't have a solution to that yet since I cannot drill or add new holes to the billiards table, and floor supports would be too bulky and large. I plan to use the rolling system similar to that of the Blot to move the module around the supports (similar metal cuboid supports as well (Im not sure what they are called)).


The first Idea consists of a simple spring suspended platform(with 2 motors to adjust the angle of depression of the platform). The cue stick and solenoid would be attached to the platform. There would be a second camera on the platform to ensure the cue stick correctly lines up with the ball as planned by the overhead camera. I feel that this approach would not work very well as it requires the cue ball to be close to the edge, and unobstructed by any stray balls. It is also limited by the length of the cue stick (which would likely be half the length of an actual cue stick), which is why I have tentatively rejected this approach.
![](https://fabricate.hackclub-assets.com/9caa42a8877542467ba972632f7888b5158bca537452bf5fb78b268df26b60c7/image-jpeg/IMG_7903.jpeg)

The second approach, albeit complex, seems to be a more complete solution to the task at hand. It is similar to a robot arm, with a module at the end with the solenoid and cue stick holder. This approach seems more ideal as it allows the module to reach more places on the table and allows for more precise control over the positioning of the stick. This does come with drawbacks such as requiring an obscene number of motors and likely limit switches and homing required to accurately position everything. This would also need strong components as the solenoid would cause quite a bit of recoil on the arm, likely needing a metal/aluminium chassis. This would also need a stronger bottom rail support. There is still more planning that needs to be done before a final approach is decided on.
![](https://fabricate.hackclub-assets.com/9994298870cc9bc80a4ecace510e6ea25a8fa110d12454f93e548fea39304c93/image-jpeg/IMG_7904.jpeg)

**Total time spent: 2h 30m**
