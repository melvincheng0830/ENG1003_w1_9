<p align="center">

  <h1 align="center">ENG1003_w1_9' s report</h1>
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
    <li><a href="#Background-of-Path-Planning-to-Aviation-Engineering">Background of Path Planning to Aviation Engineering</a></li>
    <li><a href="#Theory-of-Path-Planning-Algorithm">Theory of Path Planning Algorithm</a></li>
    <li><a href="#Introduction-of-the-Engineering-Tools">Introduction of the Engineering Tools</a></li>
    <li><a href="#Task-1-Methodology-results-and-Discussion">Task 1:Methodology, results and Discussion</a></li>
    <li><a href="#Task-2-Methodology-results-and-Discussion">Task 2:Methodology, results and Discussion</a></li>
    <li><a href="#task-3-Methodology-results-and-Discussion">task 3:Methodology, results and Discussion</a></li>
    <li><a href="#task-4-Methodology-results-and-Discussion">task 4:Methodology, results and Discussion</a></li>
    <li><a href="#Reflective-Essay">Reflective Essay </a></li>
    <li><a href="#Reference">Reference </a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
# Background of Path Planning to Aviation Engineering


When travelling by air, we may often think: what is the trajectory of the plane in the sky？ how is the plane's route  planned？
This is a graph of global airline data. Under normal circumstances.You can see that there are approximately 100,000 aircraft movements per day, taking off and landing between 6,000 airports.

![This is an image](https://github.com/KeiraXu03/image/blob/main/228e227c81520ac0d7b7af5427e98cb.png)

"At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat."

"On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain. These cases are perfectly simple and easy to distinguish. In a free hour, when our power of choice is untrammelled and when nothing prevents our being able to do what we like best, every pleasure is to be welcomed and every pain avoided. But in certain circumstances and owing to the claims of duty or the obligations of business it will frequently occur that pleasures have to be repudiated and annoyances accepted. The wise man therefore always holds in these matters to this principle of selection: he rejects pleasures to secure other greater pleasures, or else he endures pains to avoid worse pains."

# Theory of Path Planning Algorithm 
  Path planning technology[[1]](#jump6)[[2]](#jump7) has a wide range of applications in many fields. The applications in the high-tech field include: autonomous robots' collision-free actions; UAVs' obstacle avoidance and penetration flight; cruise missiles to avoid radar searches, anti-rebound attacks, and complete burst explosion missions.Applications in daily life are: GPS navigation; road planning based on GIS system; urban road network planning and navigation. Applications in the field of decision management include: vehicle problems in logistics management (VRP) and similar resource management resource allocation problems. Routing issues in the field of communication technology, etc.Basically, all the planning problems that can be topologically formed as a point-line network can be solved by the method of path planning.  
  The core of path planning is the design of algorithms. Path planning algorithms [[3]](#jump8) have received widespread attention. From traditional algorithms to later algorithms developed in combination with bionics, intelligent algorithms have made tremendous progress.Different intelligent algorithms have different characteristics, and their scope and fields are also. Therefore, studying the path planning intelligent algorithm from the characteristics of the algorithm itself and its application is of great significance to the development of path planning technology.  
General steps of path planning
  General path planning problems in the continuous domain, such as dynamic path planning problems of robots and aircraft, etc. The general steps include environment modeling, path search, and path smoothing[[4]](#jump9)[[5]](#jump).  
  **Common path planning algorithms**  
  **（1）Traditional algorithm**  
  Traditional path planning algorithms include: simulated annealing algorithm, artificial potential field method, fuzzy logic algorithm, tabu search algorithm and so on.  
  **（2）Graphics algorithm**  
  Traditional algorithms often have difficult modeling problems when solving practical problems. Graphics methods provide basic modeling methods. However, graphics methods generally have insufficient search capabilities, and they often need to be combined with specialized search algorithms. Graphics methods include: C-space method, grid method, free space method, voronoi diagram method, etc.  
  **（3）Intelligent Bionics Algorithm**  
  When dealing with path planning problems in the context of complex and dynamic environmental information, inspiration from nature can often play a very good role. Intelligent bionics algorithm is the algorithm people discover through bionics research. Commonly used are: ant colony algorithm, neural network algorithm, particle swarm algorithm, genetic algorithm, etc  
  **（4）Other algorithms**  
  There are also some artificially invented algorithms that are widely used because of their excellent characteristics. These algorithms generally have strong path search capabilities and can play a good role in discrete path topology networks.These algorithms include: A* algorithm, Dijkstra algorithm, fallback algorithm, Floyd algorithm, etc.
# Introduction of the Engineering Tools 

## a.Python

### Introduction
Python was founded by Guido van Rossum, who was working at the Dutch Mathematical and Computer Science Research Institute in Amsterdam, and during Christmas 1989, Guido van Rossum, in order to pass the time, decided to develop a new interpretive scripting language as a successor to the ABC language, as an alternative to using the Unix shell and C for system administration, and to take on the responsibility of interacting with the Amoeba operating system and handling exceptions. Interaction and exception handling with the Amoeba operating system [[6]](#jump1)
![python](https://github.com/KeiraXu03/image/blob/main/python.png)
Python reached version 1.0 in January 1994. The main new feature of this release is to include the functional programming tools lambda, map, filter and reduce provided by Amrit Prem[[7]](#jump2)
### What python can do?
* *Python can be used on a server to create web applications.*   
* *Python can be used alongside software to create workflows.*   
* *Python can connect to database systems. It can also read and modify files.*   
* *Python can be used to handle big data and perform complex mathematics.*  
* *Python can be used for rapid prototyping, or for production-ready software development.*  

## b.Github
<img width="400" height="250" src="https://github.com/KeiraXu03/image/blob/main/github2.png"/>
  
### What is Github?
* *A social network and platform for software developers*  
* *A place where people can share code*    
* *Over 65 million users*  
* *Many big companies are using it*  
* *A place to Share, Communicate, Collaborate with others, especially programmers*  

### How GitHubThe GitHub developed？
* *The GitHub platform began development on October 1, 2007.*[[8]](#jump3)  
* *On April 10, 2008, GitHub was officially launched.*  
* *On January 23, 2014, co-founder Tom Preston-Werner took over the position of president from another co-founder, Chris Wanstrath. The latter will also take over the CEO position left by Preston Werner.*  
* *On the evening of June 4, 2018, American technology company Microsoft announced the acquisition of GitHub for $7.5 billion in stocks[[9]](#jump4) [[10]](#jumup5).On October 29th, Microsoft's vice president of developer services, Nat Friedman (Nat Friedman) will become the new CEO of GitHub.*  
* *On March 17, 2020, Github announced the acquisition of npm. GitHub has now guaranteed that npm will always be free to use.*
# Task 1 Methodology results and Discussion
## Methodology:
### First,we should find the code which needs to be changed.
**Start and Finish Point:**  
![1](https://github.com/KeiraXu03/image/blob/main/08bc4b5b246daf9f1ddbfa83321f580.png)
****
**Set obstacle positions:**   
![2](https://github.com/KeiraXu03/image/blob/main/b371647410ce3d465af05395a40fb69.png)
****
**Set fuel consuming area and time consuming area:**
![3](https://github.com/KeiraXu03/image/blob/main/6a1f1753efd2a5eb662ab240d4283bb.png)
### Secondly,according to our goal,we change the code:**
```
# start and goal position
    sx = 0.0  # [m]
    sy = 0.0  # [m]
    gx = 50.0  # [m]
    gy = 50.0  # [m]
    grid_size = 1  # [m]
    robot_radius = 1.0  # [m]
```
****
```
    # set obstacle positions for group 9
    for i in range(-10, 20): # draw the free border
        ox.append(20.0)
        oy.append(i)

    for i in range(40, 50):
        ox.append(i)
        oy.append(140-2*i)
```
****
```
# set fuel consuming area
    fc_x, fc_y = [], []
    for i in range(30, 35):
        for j in range(0, 40):
            fc_x.append(i)
            fc_y.append(j)
    
    # set time consuming area
    tc_x, tc_y = [], []
    for i in range(0, 20):
        for j in range(20, 40):
            tc_x.append(i)
            tc_y.append(j)
```
## Result:
<img width="570" height="450" src="https://github.com/KeiraXu03/image/blob/main/task1.gif"/>

# Task 2 Methodology results and Discussion

# task 3 Methodology results and Discussion
<img width="570" height="450" src="https://github.com/KeiraXu03/image/blob/main/task3.gif"/>

# task 4 Methodology results and Discussion

# Reflective Essay

# Reference
<span id="jump6">[1]</span> *Cong Yanfeng. Research on path planning method based on rolling optimization principle [D]. Jilin: Jilin University, 2007.*  
<span id="jump7">[2]</span> *Peter Stiles, Ira Glickstein.RoutePlanning[C].IEEE,1991:420-425.*  
<span id="jump8">[3]</span> *Zhang Yongfang, Zhang An, Zhang Zhiyu, et al. Tactical flight path planning algorithm[J]. Journal of Traffic and Transportation Engineering, 20
06 (12) :84-87*  
<span id="jump9">[4]</span> *Xu Peipei. Research on global path planning algorithm of mobile robot in complex dynamic environment. [D]. Beijing: Beijing University of Posts and Telecommunications, 2009*  
<span id="jump10">[5]</span> *Wang Tao.Robot path planning and simulation system based on ant colony algorithm[D]. Xi'an: Xi'an University of Science and Technology, 2009.*
<span id="jump1">[6]</span> *Why was Python created in the first place?. Python FAQ. [2007-03-22].*     
<span id="jump2">[7]</span> *van Rossum, Guido. The fate of reduce() in Python 3000. Artima Developer. [2007-03-22].*    
<span id="jump3">[8]</span> *Weis, Kristina. GitHub CEO and Co-Founder Chris Wanstrath Keynoting Esri’s DevSummit!. 2014-02-10 [2015-07-02].*  
<span id="jump4">[9]</span> *Lee. Microsoft buys Github code-sharing site for $7.5bn. BBC News. 2018-06-04 [2018-06-06].*       
<span id="jump5">[10]</span> *defunkt. A bright future for GitHub. The GitHub Blog. 2018-06-04 [2018-06-06].*  

