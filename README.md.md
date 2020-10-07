# TSFS12: Autonomous vehicles – planning, control, and learning systems

This repository includes lecture notes, material for hand-in exercises, links to reading material, and other course material. Information here will be added during the course and you can always get the latest version of course material here.

Link to slides with a * indicates slides from 2019.
## Lecture 1: Introduction [[slides](Lecture_notes/lecture_1_introduction.pdf)]

### Video
1. [_Introduction to autonomous systems_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/introduction_intro.mp4) [9:44]
2. [_Autonomous systems - a broader context_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/introduction_autonomous_systems.mp4) [16:03]
3. [_Enabling technologies_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/introduction_enabling_technologies.mp4) [11:17]
4. [_Autonomous vehicles and summary_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/introduction_autonomous_vehicles.mp4) [18:34]

### Reading material
Recommended reading material for the introductory lecture are
* Introduction to SLAM, Part E Chapter 46.1 in Siciliano, B., and Oussama K., eds. “[_Springer handbook of robotics_](https://login.e.bibl.liu.se/login?url=https://search.ebscohost.com/login.aspx?authtype=guest&custid=s3912378&groupid=main&direct=true&db=cat00115a&AN=lkp.941644&profile=eds2&lang=sv)”. 
* "[_National Highway and Traffic Safety Administration ODI on Tesla_](https://static.nhtsa.gov/odi/inv/2016/INCLA-PE16007-7876.PDF)". Interesting text but there are parts that have met critique, see, e.g., [_NHTSA's Flawed Autopilot Safety Study Unmasked_](https://www.thedrive.com/tech/26455/nhtsas-flawed-autopilot-safety-study-unmasked) (Note: Opinion piece written by automotive industry analyst).
* A. Pernestål et al. "[_Effects of driverless vehicles-Comparing simulations to get a broader picture_](https://d1rkab7tlqy5f1.cloudfront.net/TBM/Over%20faculteit/Afdelingen/Engineering%20Systems%20and%20Services/EJTIR/Back%20issues/19.1/362018%20Pernestal.pdf)" European Journal of Transport & Infrastructure Research 19.1 (2019).
* Michon, John A. "[_A critical view of driver behavior models: what do we know, what should we do?_](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.473.3166&rep=rep1&type=pdf)." Human behavior and traffic safety. Springer, Boston, MA, 1985. 485-524.
* SAE, "[_Taxonomy and Definitions for Terms Related to Driving Automation Systems for On-Road Motor Vehicles_](https://login.e.bibl.liu.se/login?url=https://saemobilus.sae.org/content/J3016_201806/)", Standard J3016.
* Recommends an interesting discussion on [_The Artificial Intelligence podcast_](https://lexfridman.com/ai/) with Sertac Karaman https://lexfridman.com/sertac-karaman/ on autonomous driving and flying. Sertac Karaman is also author of course litterature in lecture 4.

## Lecture 2: Discrete motion planning [[slides](Lecture_notes/lecture_2_discrete_motion_planning.pdf)]

### Video
1. [_Introduction to graph search_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/discrete_planning_intro.mp4) [16:32]
2. [_Dijkstra's algorithm_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/discrete_planning_dijkstra.mp4) [14:04]
3. [_A* algorithm_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/discrete_planning_astar.mp4) [17:35]
4. [_Anytime planning and conclusions_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/discrete_planning_outro.mp4) [08:59]

### Reading material
Main text is Chapter 2 (mainly sections 2.1-2.3) in "[_Planning Algorithms_](http://planning.cs.uiuc.edu)", S. Lavalle. 

For the interested reader, suggested material to dig deeper is
* Likhachev et al. "[_ARA*: Anytime A* with provable bounds on sub-optimality_](http://papers.nips.cc/paper/2382-ara-anytime-a-with-provable-bounds-on-sub-optimality.pdf)", Advances in neural information processing systems. 2004.
* Introductory section in Bertsekas, D.  "[_Reinforcement learning and optimal control_](https://web.mit.edu/dimitrib/www/RLbook.html)", 2019, Athena, is used in the exercise for higher grade in hand-in 1. A PDF with the introductory text can be found on the authors book-page at
https://web.mit.edu/dimitrib/www/RL_1-SHORT-INTERNET-POSTED.pdf
* Chen, Mo, et al. "[_Priority queues and Dijkstra's algorithm_](https://www.researchgate.net/profile/Vijaya_Ramachandran/publication/250152101_Priority_Queues_and_Dijkstra's_Algorithm/links/54170a0a0cf2218008bec462.pdf)". Computer Science Department, University of Texas at Austin, 2007. 

## Lecture 3: Modelling of ground vehicles [[slides*](Lecture_notes/lecture3_ground_vehicles.pdf)]
* Sections 13.1 and 15.3-15-4 in LaValle, S. M.: [_Planning Algorithms_](http://planning.cs.uiuc.edu). Cambridge University Press, 2006.

## Lecture 4: Motion planning with differential constraints [[slides*](Lecture_notes/lecture_4_motion_planning_with_diff_constraints.pdf)]
* Sections 5.1-5.5 and 14.1-14.4 in LaValle, S. M.: [_Planning Algorithms_](http://planning.cs.uiuc.edu). Cambridge University Press, 2006.
* Sections 3.3.3 and 5 in Karaman, S., & E. Frazzoli: ”[_Sampling-based algorithms for optimal motion planning_](https://login.e.bibl.liu.se/login?url=https://doi.org/10.1177%2F0278364911406761)". The International Journal of Robotics Research, 30(7), 846-894, 2011.
* Section 2.3 in Bergman, K.: ”[_On Motion Planning Using Numerical Optimal Control_](https://doi.org/10.3384/lic.diva-157077)”, Licentiate Thesis, Div. Automatic Control, Linköping Univ., 2019.

Additional material for further reading:
* Likhachev, M., & D. Ferguson: ”[_Planning long dynamically feasible maneuvers for autonomous vehicles_](https://login.e.bibl.liu.se/login?url=https://doi.org/10.1177%2F0278364909340445)". The International Journal of Robotics Research, 28(8), 933-945, 2009.
* Dahl, O.: ”[_Path Constrained Robot Control_](https://lucris.lub.lu.se/ws/files/4364453/8566341.pdf)”, Ph.D. Thesis, Dept. Automatic Control, Lund Univ., 1992.
* Ljungqvist, O.: ”[_Motion planning and feedback control techniques with applications to long tractor-trailer vehicles_](http://urn.kb.se/resolve?urn=urn:nbn:se:liu:diva-165246)”, Ph.D. Thesis, Div. Automatic Control, Linköping Univ., 2020. 

## Lecture 5: Dynamic optimization as a tool for motion planning and control [[slides*](Lecture_notes/lecture_5_dynamic_optimization_motion_planning_control.pdf)]
* Limebeer, D. J., & A. V. Rao: ”[_Faster, higher, and greener: Vehicular optimal control_](https://login.e.bibl.liu.se/login?url=https://doi.org/10.1109/MCS.2014.2384951)”. IEEE Control Systems Magazine, 35(2), 36-56, 2015.

For a more mathematical treatment of the topic of numerical optimal control and further reading on the methods presented in this lecture:
* Chapter 8 in Rawlings, J. B., D. Q. Mayne, & M. Diehl: [_Model Predictive Control: Theory, Computation, and Design_](https://sites.engineering.ucsb.edu/~jbraw/mpc/). Nob Hill Publishing, 2017
* Diehl, M.: [_Numerical Optimal Control_](https://www.fs.isy.liu.se/Edu/Courses/NumericalOptimalControl/Diehl_NumOptiCon.pdf), Optec, K.U. Leuven, Belgium, 2011.

A guest presentation on optimization-based methods for motion planning will also be given by Kristoffer Bergman, Div. Automatic Control, Linköping University, during this lecture.

Additional material for further reading:
* Bergman, K.: ”[_On Motion Planning Using Numerical Optimal Control_](https://doi.org/10.3384/lic.diva-157077)”, Licentiate Thesis, Div. Automatic Control, Linköping Univ., 2019.
* Nocedal, J., & S. Wright: [_Numerical Optimization_](https://link.springer.com/book/10.1007%2F978-0-387-40065-5). Springer, 2006.

## Lecture 6: Control of autonomous vehicles I: Ground vehicles [[slides](Lecture_notes/lecture_6_ground_vehicle_motion_control.pdf)]
### Video
1. [_Introduction to paths and trajectories_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/control_I_intro.mp4) [19:35]
2.	[_Pure pursuit path controller_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/control_I_pure_pursuit.mp4) [08:51]
3.	[_State-feedback path controller_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/control_I_state_feedback.mp4) [16:32]
4.	[_Tuning, non-linear control, and summary_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/control_I_tuning.mp4) [09:21]
5.	[_Derivation of Frenet equations_](https://www.fs.isy.liu.se/Edu/Courses/TSFS12/Videos/control_I_frenet.mp4) [13:23]

### Reading material
Main texts are
* Paden, Brian, et al. "[_A survey of motion planning and control techniques for self-driving urban vehicles_](https://doi.org/10.1109/TIV.2016.2578706)". IEEE Transactions on intelligent vehicles 1.1 (2016): 33-55.

    A good but slightly advanced text and therefore many details are included in the lecture notes.

* Coulter, R. Craig. "[_Implementation of the Pure Pursuit Path Tracking Algorithm_](https://apps.dtic.mil/dtic/tr/fulltext/u2/a255524.pdf)" (1992). 


    But don’t look at figure 1, it is badly scaled which makes it difficult to understand; use figures in the lecture slides instead

For the interested reader, suggested material to dig deeper is
* Siciliano, B., and Oussama K., eds. “[_Springer handbook of robotics_](https://login.e.bibl.liu.se/login?url=https://search.ebscohost.com/login.aspx?authtype=guest&custid=s3912378&groupid=main&direct=true&db=cat00115a&AN=lkp.941644&profile=eds2&lang=sv)”. Springer, 2016. Part E, Chapters 49 (wheeled robots), 51 (underwater), and 52 (aerial) 

* Werling, M., Gröll, L., and Bretthauer, G.. "[_Invariant trajectory tracking with a full-size autonomous road vehicle_](https://doi.org/10.1109/TRO.2010.2052325)". IEEE Transactions on Robotics 26.4 (2010): 758-765. 
    An advanced text, nonlinear trajectory stabilizing controllers.

## Lecture 7: Model Predictive Control for Autonomous Vehicles

## Lecture 8: Control of autonomous vehicles II [[slides*](Lecture_notes/lecture_8.pdf)]
Main text is
* Kuwata et.al. [_Real-Time Motion Planning With Applications to Autonomous Urban Driving_](https://doi.org/10.1109/TCST.2008.2012116)

## Lecture 9: Collaborative control [[slides*](Lecture_notes/lecture_9.pdf)]
Background and history can be found in [_Springer handbook of robotics_](https://login.e.bibl.liu.se/login?url=https://search.ebscohost.com/login.aspx?authtype=guest&custid=s3912378&groupid=main&direct=true&db=cat00115a&AN=lkp.941644&profile=eds2&lang=sv)”. Springer, 2016. Part E, Chapter 53 (Multiple Mobile Robot Systems)

The methods described in the lecture  can be found in 
[_A survey of multi-agent formation control_](https://doi.org/10.1016/j.automatica.2014.10.022)

## Lecture 10: Learning for autonomous vehicles I [[slides*](Lecture_notes/lecture_10_learningI.pdf)]
* Sections 11.2-11.8 in Hastie, T., R. Tibshirani, J. Friedman, & J. Franklin: [_The Elements of Statistical Learning: Data Mining, Inference and Prediction_](https://web.stanford.edu/~hastie/ElemStatLearn/). 2nd Edition, Springer, 2005.
* Sections 1 and 2.1-2.3 in Rasmussen, C. E., & C. K. I. Williams: [_Gaussian Processes for Machine Learning_](http://gaussianprocess.org/gpml/chapters/). MIT Press, 2006.
* Sections 1, 4.1-4.4, and 6.1-6.5 in Sutton, R. S., & A. G. Barto: [_Reinforcement learning: An introduction_](http://incompleteideas.net/book/the-book-2nd.html). MIT Press, 2018.

Further reading on deep neural networks and Markov decision processes under uncertain state information:
* Goodfellow, I., Y. Bengio, & A. Courville: [_Deep Learning_](http://www.deeplearningbook.org). MIT Press, 2016.
* Åström, K. J.: ”[_Optimal control of Markov processes with incomplete state information_](https://doi.org/10.1016/0022-247X(65)90154-X)”, Journal of Mathematical Analysis and Applications, 10(1), 174-205, 1965.

## Lecture 11: Learning for autonomous vehicles II + guest lecture

* Industrial guest lecturer: Dr. Karl Berntorp, Principal Research Scientist, Mitsubishi Electric Research Labs, Boston, MA (https://www.merl.com/people/berntorp)

