---
layout: page
title: "Data Driven Advancements in Major League Baseball: The Rise of Torpedo Bats"
description "The rise of torpedo bats, how data, collision physics and precise manufacturing are transforming bat design in Major League Baseball"
category: work

## Data Driven Advancements in Major League Baseball: The Rise of Torpedo Bats ##
Eero Sorensen — KNES 381: Computer Applications in Kinesiology — Dr. John Holash — April 9th, 2026



## Introduction ##
Major League Baseball is in the middle of a technological revolution, making the game more relevant for the new generation. While tools like iPads and metric measuring systems have been available in dugouts since the mid-2010s (Zakarin, 2017), the application of this technology has only recently entered the public eye through radical changes in the traditional design of physical equipment. The most prominent change is the "torpedo bat craze" in which the traditional profile of the baseball bat is being replaced by the technology-driven "torpedo" design (Pereira, 2026). This essay will explore how data driven improvements, collision physics, and precise manufacturing has transformed the baseball bat from a normalized design utilized over 100 years, to a highly optimized and individualized tool for offensive production, redefining the use of technology within the game.



## Traditional Bat Design Limitations ##
Hitting a baseball is one of the most difficult tasks in sport, requiring mastery of visuomotor coordination, precise timing, and elite physical power and perceptual skill (Tremblay et al., 2025). The challenge is the time constraint (Carleton, 2015). The average human reaction time is 250ms, and a 90-mph fastball reaches the plate in 417ms, leaving 167ms for a hitter to swing. Within this window, factors like pitch velocity, location, spin and movement must all be processed (Tremblay et al., 2025).

Successful contact depends on striking the ball in the bat's "sweet spot" — a 3cm wide impact zone where energy transfer is maximized (Sawicki et al., 2003). If a batter misses this zone, contact results in weak contact, leading to an out or a foul ball (Carleton, 2015).

Despite these challenges, bat design has had the same shape for decades (Pereira, 2026). Regulations in Major League Baseball require bats to be made from a single piece of wood, with limits on length and diameter (Anthopoulos et al., 2021), but there are no outlines for shape. Traditional bats stick to a "one size fits all" design which does not account for each individual batter's swing mechanics or hitting profile (Pereira, 2026). These normalized designs highlight the need for more individual approaches, setting the stage for technological innovations such as torpedo bats.



## Technology Behind the Bat ##
To create a customized torpedo bat, teams collect multiple points of data spanning over multiple years of their player's career to build a highly individualized hitting profile. Taking place in specialized bat fitting labs, teams use motion capture sensors and high-tech cameras such as the Vicon system. Reflective markings are placed on anatomical landmarks to define joint locations and record the movement of the player's body during every swing phase, creating 3D segment velocities (Berkson et al., 2020).

Analysts record swing mechanics, swing path, bat speed, attack angle, attack direction, and swing path tilt. Spatial positioning is also monitored — where they stand in the batter's box and where contact with the ball occurs relative to home plate and the batter's center of mass. Impact quality is measured via:

Exit velocity

Square up swings (contact achieving at least 80% of maximum exit velocity)

Blasts (squared up swings with bat speed meeting a player-specific threshold)

These data points can create a bat that increases peak exit velocity by 1 mph (Pereira, 2026), leading to a 2–5% increase in hit probability (Statcast).

A design constraint is the player's "wood budget", typically limited to a mass of 31 ounces. Using the collected data points, the weight is redistributed to shift the player's sweet spot up or down the barrel (Millanta, 2025). Moving the sweet spot proximally is done by thinning the tip of the bat — giving the design the name "torpedo". Manufacturers can achieve this without changing the moment of inertia, ensuring swing weight remains constant compared to the player's previous traditional model.

Piezoelectric sensors are used to refine the bat's internal physics. They act as accelerometers to collect vibration signals upon impact (Lu et al., 2024), identifying the bat's bending modes and ensuring contact with the sweet spot minimizes vibrations felt in the player's hands (Cross, 1998).

Teams analyze these variables privately, but tools such as JMP's Workflow Builder and Python packages like PyBaseball are publicly available. Advanced modeling methods can be used to identify how design changes affect swing mechanics, such as swing length or contact consistency (Cooper & Higgins, 2025).

Finally, CNC (Computer Numerical Control) machines are programmed with thousands of data points that define the ideal bat profile. A wood billet is shaped to the exact millimeter with a precision that traditional lathes cannot achieve (Nielsen, 2025).



## Algorithms and Mass Distribution ##
Torpedo bats are created via a precise data-driven workflow. Years of data are compiled to create a hitting profile, and algorithms combining statistical modeling, physics and biomechanics optimize the design. Analysts apply tree-based learning models — such as bootstrap forests and boosted trees — to evaluate how non-linear bat design variables alter swing mechanics. Batted ball models connect contact outcomes like launch speed and launch angle to the result of the play (Cooper & Higgins, 2025).

Collision physics models use mathematical foundations to evaluate energy transfer. They use the effective mass of the bat at the point of contact, rather than its total mass. Using effective mass allows analysts to understand the mass that the ball "sees" during the collision (Sawicki et al., 2003). Analysts model the bat as multiple mass segments, determining impact location frequency and effective mass distribution while keeping MLB's bat regulations in mind (Nathan, 2025).

The output results in the optimal sweet spot location along the length of the bat for the individual player. These alterations often result in a "torpedo" shape due to the redistribution of the thickest part of the barrel to align with the player's hitting patterns.

Notable contributors to this process include Aaron Leanhardt, a former physics professor with a doctorate from MIT serving as a New York Yankees analyst, and Alan M. Nathan of the University of Illinois, credited with creating the computer models used to estimate performance outcomes of these designs (Pereira, 2026).

Algorithms and methods are treated as proprietary advantages. While performance data is publicly available through resources such as Statcast, the way it is utilized differs from team to team. Because of the inherent variability in baseball, teams use models that rely on distributions of contact locations rather than fixed values (Cooper & Higgins, 2025).



## Implications for the Modern Game ##
The adoption of torpedo bats indicates a broader shift towards data-driven optimization in Major League Baseball. Early evidence reflects small but meaningful improvements. In one analysis of players using torpedo bats during the 2025 season, the majority showed increases in hard hit percentage with an improvement of over 4%. However, these gains are not universal — some players experienced declines in performance, showing that effectiveness relies on how well the bat aligns with the hitter's individual patterns.

Beyond bat design, a large technological trend has emerged within the MLB. Systems like Statcast have shifted the way teams evaluate performance, tracking detailed metrics across multiple aspects rather than single outcomes. This shift has fueled an "arms race" across the league, with organizations developing their own models and algorithms to gain competitive advantages.

While reactions to these technological advances have been mixed — some viewing it as natural evolution, others as a challenge to traditional norms — they have ultimately become a larger movement in modern baseball. Marginal gains are now being driven by technology, with an increasing role in player development, strategy, and equipment design.



## Conclusion ##
The adoption of torpedo bats into the modern game represents more than a passing trend — it represents the use of technology to transform the way the game is played. By addressing the variables a batter faces when attempting to hit a baseball, torpedo bats provide hitters with an advantage in situations where milliseconds determine success or failure. Through a data-driven workflow, teams use Statcast metrics and high-tech cameras to identify unique patterns and effectively redistribute the effective mass in a player's bat. Further study into the long-term usage of these bats is needed to determine their effectiveness, and the overall impact of technology within the game remains an area available for investigation.



References ##
Anthopoulos, A., Dipoto, J., Hill, M., Antonetti, C., Finley, J., Mozeliak, J., Daniels, J., Gorman, B., Stearns, D., & Gaski, M. (2021). Official Baseball Rules 2021 Edition.

Berkson, E. M., Linderman, S. E., Stein, H. S., Yong, C. M., & Scarborough, D. M. (2020). The Kinematic Sequence Of The Baseball Bat Swing And Associated Upper Extremity Torques. Medicine & Science in Sports & Exercise, 52(7S), 260–260. https://doi.org/10.1249/01.mss.0000676384.16410.b7

Carleton, R. (2015, January 8). Baseball Therapy: The Trouble With Velocity. Baseball Prospectus. https://www.baseballprospectus.com/news/article/25303/

Cooper, R., & Higgins, L. (2025, July 9). Evaluating the Impact of Torpedo Bats in Major League Baseball Using JMP. JMP User Community. https://community.jmp.com/t5/Abstracts/Evaluating-the-Impact-of-Torpedo-Bats-in-Major-League-Baseball/ev-p/884359

Cross, R. (1998). The sweet spot of a baseball bat. American Journal of Physics, 66(9), 772–779. https://doi.org/10.1119/1.19030

Lu, Y.-C., Liu, C., & Ma, H.-P. (2024). Impact Position Detection of Baseball Bat Using Multi-axis Accelerometers. Artificial Intelligence in HCI (pp. 395–408). Springer Nature Switzerland. https://doi.org/10.1007/978-3-031-60615-1_27

Millanta, R. (2025, April 14). What to Make of the Most Talked-About Bat in Baseball. https://www.justbaseball.com/mlb/what-is-torpedo-bats-baseball/

Nathan, A. M. (2025). The Physics of the Torpedo Bat: An Update.

Nielsen, K. (2025, April 2). The 'torpedo bat' is the latest MLB craze. Global News. https://globalnews.ca/news/11111106/mlb-new-torpedo-bats/

Pereira, O. (2026, January 9). Bringing the Boom: Analyzing the Long-Term Effects of Torpedo Bat Usage. Sports Analytics Group at Berkeley. https://sportsanalytics.studentorg.berkeley.edu/articles/bringing-the-boom.html

Sawicki, G. S., Hubbard, M., & Stronge, W. J. (2003). How to hit home runs: Optimum baseball bat swing parameters for maximum range trajectories. American Journal of Physics, 71(11), 1152–1162. https://doi.org/10.1119/1.1604384

Tremblay, M., Couëpel, B., Abboud, J., & Descarreaux, M. (2025). What are the Individual Characteristics or Skills Associated with Baseball Batting Performance? A Scoping Review. Sports Medicine - Open, 11(1), 150. https://doi.org/10.1186/s40798-025-00947-1

Zakarin, J. (2017, April 7). 10 Ways Baseball Technology Is Changing the Game. Inverse. https://www.inverse.com/article/29968-10-baseball-technology-advances
