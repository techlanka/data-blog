---
title: "An Exploration of General-Use Immersive Visualization Applications"
author:
  name: Walt Gurley
  picture: images/gurley-walt-2018.png
  email: jwgurley@ncsu.edu
  links:
    - title: Email
      url: mailto:jwgurley@ncsu.edu
      icon: fas fa-laptop
categories:
  - Data Visualization
  - Virtual Reality
  - Immersive Analytics
tags:
  - data visualization
  - vr
  - analytics
  - immersive
  - NCSU
comments: true
---


Virtual reality (VR) has matured into a widely adopted computing platform with increasingly affordable hardware and dedicated application development in fields such as gaming, art, entertainment, and education. With the concurrent growth and availability of digital data, VR stands as a possible medium for understanding complex information with new modes of insight and novel methods of presentation through immersive data visualization. As part of the NCSU Libraries support of visualization and immersive technologies several colleagues and I have been investigating the current landscape of general-use immersive visualization technologies (i.e., technologies that are not domain specific or require specialized hardware or software and are available for use on personal devices) to evaluate existing software applications and determine the viability of visualization in a VR environment. Through our exploration we have identified some promising platforms and gleaned a few insights about this niche, but growing, field of VR and the possible applications and services the Libraries can provide around this emerging visualization tool.

### A case for immersive visualization
Though I was skeptical about the broad utility of immersive visualization there are documented and suggested benefits to learning and cognition in VR environments and pattern recognition through visualization of data in three-dimensional space. When carefully crafted, a VR experience can create a feeling of immersion and delight for the end user. There are benefits provided by immersive environments that reduce cognitive load and may improve a user’s ability to acquire information (Sweller, Ayres, & Kalyuga, 2011; or see Extraneous cognitive load). These benefits mainly relate to reduction in external stimuli and an increased presence within a virtual space. This feeling of presence can be influenced by not only the visual design of the environment but also interaction with the environment and other sensory stimuli. On the other hand, a poorly designed environment can lead to disengagement from the user or, worse, discomfort and sickness. Well crafted visualizations also serve to reduce cognitive load when exploring patterns in a dataset. It has been shown that viewing a visualization in an interface designed for three-dimensional space in an immersive environment can aid pattern recognition and detection (Ware & Franck, 1996). However, direct porting of an interface from a low-immersion environment, like a two-dimensional screen, to a high-immersion environment like VR has been suggested to hinder a user’s learning and cognition (Moreno & Mayer, 2002). Given the basic cognitive concerns of immersive environments and an awareness of visualization best practices, a thoughtfully designed immersive visualization tool may be beneficial in some research cases.

### An overview of the exploration
While not necessarily indicative of all the immersive visualization applications on the market, through a series of searches on the web as well as searches within the VR application repositories Oculus Store and SteamVR Store we identified six applications claiming to offer three-dimensional data visualization in virtual reality. At the time of our original searches none of these application were production ready – we were met either with websites prompting for an email to receive more information and free demos or disclaimers indicating a particular application was an “experiment in exploring data in new ways” that came out of a company engineering team hack day. One of the applications we identified was freely available as a demo on the SteamVR Store while we submitted requests to demo all the other applications. We received contact from representatives of four of the applications and two have provided interactive demos as of the time of this writing. Following the search with three applications we had for hands-on testing and evaluation were Virtualitics, 3Data (formerly titled datavizVR), and LookVR. Each of these products focuses on virtual experiences built for immersive head mounted displays (HMD), though Virtualitics also features a full desktop environment and 3Data provides a limited interactive desktop and mobile-based interface.

#### Virtualitics
Virtualitics markets its product as “an AI-based data analytics platform in Desktop and Virtual Reality” that is based on research conducted at California Institute of Technology and NASA/JPL. At the time of this writing they do not advertise a commercial application but do provide an opportunity to ‘Request a trial’. Following an email exchange with a representative from the company and the acceptance of a license agreement we acquired a month access to the software via a download link. The application consisted of a standalone desktop application that ran on only on the Oculus Rift.

#### 3Data
3Data claims to be the “most advanced online environment for data scientists to create, collaborate, and present data in virtual reality to anyone on any device, anywhere.” At the time of this writing they do not advertise a commercial application but do provide an opportunity to for a free trial. Following communication with a representative we acquired access to 3Data via a link to the online web application. For our demo 3Data created a cloud-based virtual space, protected by credentialed login, in which we could create our own visualizations and upload our own datasets. As a web-based platform, 3Data provided the ability to create and manipulate visualizations using the Oculus Rift and HTC Vive headsets as well as the limited ability to view created visualizations on a desktop browser or mobile device.

#### LookVR
LookVR was developed during a hackday by the engineering team at the company Looker, a data exploration and business intelligence software platform developer. While not a stand alone commercial application, a demo of LookVR with predefined data is available for download on the SteamVR Store (Apparently, customers of Looker have access to a version of the application in which they can view the data they have stored in the platform.). LookVR runs on the Oculus Rift as well as the HTC Vive, though we only tested the application on the Rift.

### Evaluations

In an effort to structure assessment and standardize comparison between applications we developed an evaluation rubric to rate immersive visualization applications based on metrics related to fundamental usability, functionality, and user experience. We implemented an integer scale of 1 through 3 to rate each metric – where 1 indicates subpar performance, 2 indicates acceptable performance, and 3 indicates exemplary performance. This rubric was inspired by, and incorporates some of the metrics of, the more general Visualization Software Evaluation Rubric developed by Atwood and Reznik-Zellen (2018).

#### Evaluation metrics

Fundamental usability: Given the possibility of discomfort introduced by the use of a HMD (see Virtual reality sickness) we considered usability to be an important factor in evaluation. Any immersive visualization application must meet basic performance standards to ensure comfortable use of the application. Usability metrics include:
Frame rate performance - does the application display any visual lag or frame skips
Visual artifacts - does the application display any glitches in object renderings

**Functionality**: Metrics related to functionality covered the flexibility and utility of the application, assessing the extent of data formats accepted, visualization types provided, and the degree to which visualization designs could be manipulated; the inclusion of analytical tools; and the modes through which content could be shared. Functionality metrics include:

* Ability to manipulate - how extensive are the accepted data formats and visualization types, how much modification can be made in the design of a visualization
* Provided analytical tools - does the application provide any analytical tools
* Output - to what extent are visualizations and other content developed with application sharable

**User experience**: User experience covered metrics relating to the ease of use of the application and the general level of enjoyment and engagement with the experience. User experience metrics include:

* Ease of use - do interactions feel natural, is the interface design appropriate for easy navigation
* Learning curve - are the software features easy to understand and master
* Aesthetics of the environment - are there moments of delight while using the application
* Novel use of VR - are there new interaction types for VR that incorporate natural gestures versus analogues of two dimensional screen gestures, is there a unique use of spatiality for the layout of interface or visualizations

Note that while we did spend considerable time considering evaluation metrics, we did not follow a structured manner of selecting a set group of people to evaluate each application. In some cases an assigned individual thoroughly tested an application while in other cases a group of individuals participated in a general introduction and testing of an application. As such, the following evaluations are not representative of the average opinion among a standardized group of individuals and exact metric ratings should be considered with some skepticism. Additionally, at the time of testing each of these applications was either a demo or in beta form and may have issues that are addressed in later software versions.

### General observations across applications

#### Fundamental usability

Each application performed well enough graphically and did not induce any feelings of discomfort or sickness in any tester. There were instances in each application in which some lag would occur when data was being loaded or large amounts of data were being rendered on the screen, however. This was less than ideal, but was typically aided by the understanding that a large process was occurring through the visual cue of a loading icon. In an initial test of 3Data we did have an issue in which the virtual camera was at the level of the floor and we could not see any content we were manipulating below the plane of the floor. This issue was addressed after consulting with the 3Data development team, and no instances of this occurred subsequently.

#### Functionality

There was considerable difference between applications with regard to functionality. Only Virtualitics and 3Data provided the ability to upload your own data, and we were able to load and visualize spreadsheet data in each of these application. The datasets we tested contained upwards of 100,000 observations. The developers of both applications also claimed to support database connections, though we did not try this. In addition to data upload, Virtualitics also provided a built in spreadsheet view with some statistical information and manipulation of the dataset within the application.

Virtualitics provided the broadest range of three dimensional visualization types with plots ranging from 3D scatter plots with clustering visualizations, 3D histograms, 3D bar charts, and proportional 3D symbol geospatial maps. Each visualization was customizable with regard to color scale. In addition to three dimensional plots Virtualitics also provided a set of two dimensional plots for inclusion in a 3D dashboard providing ancillary information to the main visualization. LookVR included 3D bar charts, 3D scatter plots, 3D area plots, and 3D word clouds. The visual encodings of this application could not be modified and only one visualization could be viewed at a time. 3data provided 3D scatter plots, 3D area plots, and 3D histograms. With the scatter plots, 3Data also provided the ability to set four other variables in addition to x, y, and z position using point color, size, shape, and rotation. Multiple plots could be created at the same time.

Virtualitics was the only application that included robust analytical tools in the form of automated analyses for analyzing correlations across multiple variables to determine collections of variables that might be best fit for plotting. These ‘AI’ tools seemed powerful and useful for someone who knows what they are doing. 3Data did provide the ability to visually analyze points in a plot through selection and popup tooltips.

No application provided diverse methods for sharing content outside of the given environment. Given the fact that 3Data was web-based it did provide the convenient method of sharing the live, immersive analytics environment via a URL. With access to the unique URL multiple participants could interact and/or view the visualization in real-time via another HMD, desktop, or mobile device. Virtualitics also provided a method for creating 3D dashboard presentations to share with other users and a more closed virtual space in which other clients running the Virtualitics software could participate in an environment remotely.

#### User experience

Interaction in each of these applications is performed via two spatially tracked hand controllers specifically built for interacting with VR environments in a HMD. These controllers allowed gestures like pointing to select and rotation, dragging, and pinch-zoom of objects with the motion of your hands. 3Data and, especially, Virtualitics were menu heavy and required continuous pointing and selecting. The basic flow for creating a visualization in both applications was pointing and pressing a controller button to: select your visualization type, select each variable you would like to map, and select the spatial axis on which you would like to map the variable. In some cases this selection method could cause annoyance if buttons were too small or your hands were not completely steady. After creating a visualization you had the ability to explore the 3D object similar to how you would a physical object, holding it and turning it to view from different angles and different depths. These ‘real world’ actions did not translate perfectly to the VR environment and often resulted in cumbersome interaction.

Virtualitics presented the most challenging learning curve given the intricacies and breadth of visualization types, the multiple views (e.g., spreadsheet view, dashboard view), and the inclusion of analytical tools. Mastering this application would likely take multiple sessions and dedicated study of the options and interface. Alternatively, after approximately thirty minutes of exploration with 3Data and LookVR we were able to efficiently interact and utilize these applications. A lacking feature of all application though is the inclusion of an in-environment tutorial or documentation explaining the use of the application.

With regard to aesthetics and novel use of VR, LookVR was the most enjoyable and engaging to work with. This application provided some novel ways of experiencing data such as stacks of banknotes representing monetary spending scaled to real-life and the ability to blow up the size of a bar chart and climb the tallest bar like a rock wall and view the data from the perspective of a peak. These features, while maybe gimmicky, did provide the most instances of excitement from testers. While not drab or unenjoyable, Virtualitics and 3Data both provided generic futuristic-looking environments or virtual boardrooms in which you could manipulate and create 3D visualizations.

### Takeaways

Our experience testing these three applications provided some insight into the nascent field of general-use immersive visualization technologies. Based on our evaluation we determined that each application provided usefulness for varying needs. With its array of visualization types and analytical tools, Virtualitics may serve as an appropriate application for the data scientist or researcher initially exploring and cleaning a dataset. 3Data provided a more general visual exploration of data that may be more appropriate for multiple users to analyze and derive further insight from a prepared dataset. Finally, an application like LookVR may serve as a great tool for presenting data in an engaging way to a broad audience in a virtual environment.

Personally I do not find these applications to be necessarily appropriate for general use at the current moment. However, I do believe the analytically focused applications could hold significance to researchers with more specialized analytical and visualization needs – mainly people who have data with multiple variables. While our research community definitely contains many individuals with these needs we did not identify an essential use-case to justify the further step of licensing and supporting this niche software for patron use in the library. We will continue to monitor the environment and watch the development of each of the platforms we tested.
