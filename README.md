# capstonevr-test















Cybersecurity Training in Virtual Reality Simulation














Project Name: Virtual Cybersecurity Training Module
Advisors: Scottie Murrell, Dr. Fang Wang, Dr. Ronny Bazan, Michael Tompkis, Brian Maurer
Team Name: Virtual Cybersecurity Training Project Team









Abstract
Our team has created a cybersecurity training module using virtual reality as a medium. This immersive experience is used to serve as a memorable and enjoyable training module in comparison to other training modules for basic level cybersecurity concepts currently available. The team identified five key elements that are often overlooked in cybersecurity and attempted to emphasize the importance of these elements, educating end users of technology. The five concepts we focused on are as follows: safeguarding physical items, password strengths & weaknesses, hardware and software vulnerabilities, wired vs. wireless networks, and multifactor authentication. Through the use of a narrative, we designed our training module by dividing the module into 2 sections: learning and application of learned knowledge. The learning portion is accompanied by slideshow presentations on each of the five concepts, while the application of learned knowledge takes place in a series of five rooms - one for each concept. Firstly, the user is introduced to the narrative as if they are an unpaid intern and must complete a variety of tasks to determine if the company will hire the intern. In the beginning room, a tutorial on how to use the Oculus controls are available and afterwards the user can progress to the orientation room, where the user learns about each key cybersecurity concept. After learning about each concept, the user is able to move to the first room where they apply their knowledge to the room. To move to the next room(s), the user must complete all tasks within the room before continuing.



Proposal
		Originally the team pitched the project proposal as a cooperative virtual escape room that would serve as a virtual reality cybersecurity training module. The initial idea included relying on a partner throughout the entire module that would be crucial in giving you clues or specific information, as well as the learned material in the module to progress through rooms in a sequence. A meeting with Scottie Murrell prior to our midterm presentation shifted our focus in terms of getting a singleplayer module ready instead of relying on multiplayer to educate a user within our module. Despite this, a grand majority of what we planned to use was still necessary for the completion of our module.
	As far as software deemed necessary for our project, we expected to need these pieces of software for development: Unity, Unity Plastic SCM, Blender, Visual Studios, Normcore, VRTK, LipSync, and Oculus XR Plug-in. The only pieces of software we did not end up using in our project were Normcore, LipSync, and Blender. This coincided with our new goal to successfully create a single-player virtual reality cybersecurity training module. Normcore is what the team intended on using to implement multiplayer, which was scrapped after adjusting our goal throughout development. LipSync would have been an addition to multiplayer, allowing users to have a visual cue for another user’s voice being transmitted in sync with the user’s avatar. This again was deemed unnecessary as our primary goal to create a single-player training module would not include the use of another user. Efforts were made to use Blender for certain aspects of our project, though our group lacked a sufficient modeler. Through trial and error we were able to create or purchase what we needed through Unity and the Unity asset store respectively. 
	The team made use of the VR lab located on Mizzou’s campus for all stages of development. We were using the Oculus Rift S which is not a standalone VR device and requires the use of a computer with the minimum required specifications to use: 64-bit Windows 10 OS, Intel Core i3-600 / AMD Ryzen 3 1200 (FX4350), 8GB of available RAM, NVIDIA GeForce GTX 1050Ti / Radeon RX470, compatible miniDisplayPort video output, and 1 USB 3.0 port. There were attempts to port our project to the Oculus Quest 2 using Kyle’s Oculus Quest 2, though he was unsuccessful due to build errors. 
Methods
Our team tasked ourselves with educating users on basic cybersecurity concepts through a virtual simulation training module. We used a variety of methods from concept to completion in order to create a project that would achieve our goal. In the conceptual stage of our module, we discussed who the training module would target specifically to teach these concepts. The design evolved many times, ultimately with a decision to create a serious-style multiplayer game-like module, which offers a narrative and points-based reward system. This module targeted basic level tech users in an institutional or company setting. We decided on the use of Unity Engine for development and Oculus Rift S hardware early in the start, as this is what was available in the university’s lab and also the method taught in virtual reality class. For communication, we messaged over Discord and conducted meetings, including many face-to-face meetings. For file sharing throughout the project we utilized Google Drive and Unity Collaborate, and later PlasticSCM for version control.
At the start of the project, our team met and discussed the possibilities of how to present cybersecurity concepts in a virtual reality setting, including the limitations and challenges. As all our team members had been educated beyond basic cybersecurity, it was difficult to step back and put ourselves in the shoes of users without such knowledge at first. We had to learn to roll back our skills to a more basic user level, and decide on what concepts would be most useful at that skill level. And also, what would be feasible concept-wise to educate in a simulation. The first conceptual ideas for the project were very different, some included a Capture the Flag or HackBox scenario, which is much beyond basic user level and would present difficulties in a virtual setting as well. As our idea evolved to include very basic cybersecurity principles, the style of the training module changed as well to a more serious gaming style. The next iteration in design was a centralized hub, where the user would be placed at the center of the module, in which primary learning would take place, then with many hallways leading to each room representing a different cybersecurity concept, in which testing the knowledge takes place in an escape room-style game. As the project began early development however, the design of the module reached its final concept: a narrative based training module with the setting of a company office. The user is presented as an unpaid intern tasked with completing a number of cybersecurity defensive practices throughout the module, in order to achieve a full-time position at the company. As advised by Scottie Murrell, we used a storyboard to present our design in an advisor meeting with both Mr.. Murrell and Prof. Michael Tomkins (see Appendix A). Prof. Tomkins advised us on feedback and scoring system elements to include in the module, including a timer to add as a multiplier to further influence the user to do well. Mr. Murrell also demonstrated a virtual reality simulation with onscreen feedback to the user, which we used as inspiration in our project, when user feedback in the last few weeks of development included that more feedback would be useful. This was implemented using a coded function included in the Score Manager script, and added to the Unity Editor scene (see Appendix B).
In order to keep in communication throughout the semester, we utilized Discord instant messaging to keep in contact with each other. In the beginning of each week, usually there was a message sent by Kyle or another team member requesting where everyone was in terms of the project and what the plan was for the week: for meetups, helping each other with research and development, or work being done individually. Sometimes meetings were held together over VoIP on Discord, where we discussed design plans, timelines issues, and work distribution. Also, we met in person often or also met together in person with members of our advisor team. Often, we met as a team in the VR Lab and went through the project together to show where we were at on development and to help each other with complications. We often worked in tangent on the project, either helping research development issues, or working out logic in coding, or one to make edits in Unity while another team member tested the edits. All in all, [as a team we feel we excelled in terms of communication.
For the media, design, and front end development of the project, the team utilized a number of tools to bring out the right environment for this project. Mostly everything being in the asset store we just needed to agree on some asset packages that we were going to use. After making the first couple of rooms we were aWith the project being a learning experience we wanted the user to get a hands on approach to something that could potentially save them from a lot of danger. We were always looking for ways to improve our project. One way that we liked to test those waters was by faculty meetings. We set up a couple different meetings, but the one with Prof. Chip Gubera set the foundation for why those things look the way they look. Prof. Gubera began to tell us that if the aesthetics of the project aren’t correct then it will be harder for the user to get the full grasp of what they are learning. That's why in every room we made sure there are at least two things, a desk and a device. With the project's main goal being to teach beginners more about cybersecurity, it just makes sense to have desks for everyone because we essentially want you to learn the material and apply it. We also made sure there is either a laptop or tablet to remind the user that your devices that you own need to be secured or they are on track to be hacked. Looking back at every room that was created we took all of that into account before even creating them. We wanted to make our module aesthetically pleasing to the viewer being that the module won't be something that you can just zip through. We wanted them to feel comfortable in the environment, and feel comfortable enough to sit through it and engage fully. 
Development for the back end, user interface,  and overall development of the project was achieved using the Unity Engine/Editor. The Unity Editor compiles in C#, thus this is the language we used for the scripts. We connected the Unity Editor with Visual Studio and was able to take advantage of the intellisense available for coding, which connects to the Unity Engine. The scripts were mostly used for custom elements in the project that could not be achieved through the builtin elements in Unity Editor or XR Toolkit. We also included an exception handling device in the scene, in case of collider or interaction error on the walls or floors of the module. When in the case of collision error, the player can fall through the floor element in the scene and fall indefinitely without the option to teleport or exit the game. Thus, a safety net was created in event of falls, when collision with the safety net object occurs, the XR Origin (player main camera/character controller) is automatically transported back to the orientation room in the module, where the user is available to either continue or exit the game safely (see Appendix C). Another unique element we added to the project included a tablet in which the user can interact, view points accrued as objectives are completed, review training videos introduced in the orientation room, and also a user interaction feature when the user is presented with setting up multi-factor authentication as an objective in the module. We created a script to replace the Oculus left controller model visible in the scene, to the tablet, once it appears the user has secured the tablet for wireless use by following prompts on the tablet’s screen. Once the wireless connection objective is complete, the tablet’s parent is declared as the left controller, and a new location is set (see Appendix D). Many other user interactive elements and back end features we used builtin development included with Unity Editor itself, mostly with use of canvases. Such as when a user clicks a button, the OnClick feature within Unity is activated and a function is added within the editor. As in the functionality of the tablet, when the user clicks the buttons displayed on the tablet, a series of canvases are ready to be set active or inactive and looped accordingly to display a menu feature for the user in order to interact with the review videos and multifactor authentication popups simulated on the tablet.
In addition to using Unity Editor, in order for all team members’ accessibility to edit and contribute to the project, Unity featured a builtin version control feature called Collaborate (Collab). Through Collab, each team could pull and push changes to the project’s repository and view changes made previously by each team member. Over the course of the semester, Unity Editor made a changeover from Collab to PlasticSCM. Therefore, the team set up a new cloud repository and moved all version control to PlasticSCM. Unfortunately, the most complications arose between these two features. Hours of productivity were lost many times as entire blocks of the project were either not saved to the cloud repository, or overwritten due unresolvable merge conflicts. Due to the VR Lab lack of PlasticSCM tool installation, the team resorted to working on the project in time intervals or saving work done as a prefab object outside the scene environment and saving to the project after all other changes had been updated. File sharing was another method we used as a collaboration tool throughout the project. We utilized a shared Google Drive folder and shared files, documentation, screenshots, and other resources through the shared drive.








Ethics
The cybersecurity training module’s medium is an immersive virtual experience. Using a VR headset, the user experiences a virtual “hands-on” experience through the headset and controllers while learning about cybersecurity. Virtual reality is a new and evolving technology, which presents developing concerns of privacy and ergonomic issues for the user (Kenwright, 2019). Immersive simulations require the user to look around using their neck, stretching their back and shoulders, and reach with their arms during gameplay, increasing the risk of ergonomic stress and the possibility of injury (Nilsson, 2017). As the simulation requires a headset to be worn, there is a risk of fall and injury due to loss of sight and disorientation, including injury to bystanders when controllers are waved around during gameplay. Oculus and Quest 2 headsets already include safety messages in the setup of the hardware, encouraging users to clear a safe “play area” and guardian boundary to protect the user and bystanders from injury (Oculus.com, 2022). The team opted to create our own set of guidelines that further outline potential injuries that could arise through the use of VR headsets themselves and through the use of our training module. Cybersickness was also a concern, with symptoms very similar to motion sickness illness including symptoms of nausea, sweating, dizziness, headache, vomiting, and disorientation (Pietrangelo, 2021). An effective action plan to protect users from injury was instilled - a warning message to clear the area of obstacles before gameplay and schedule breaks in gameplay to reduce the chance of ergonomic injury. Concerning cybersickness, in the development process, we will be implementing mitigation factors to gameplay to combat motion mismatch including tunneling and camera shakes (Curtis, 2015).
Physical risks were not the only problems that were found in VR through the team’s research. A study at Rutgers University in New Brunswick discovered security vulnerabilities unique to VR that could be used to eavesdrop on users and record sensitive data obtained from audio, video, and motion sensors in the headsets (Rutgers, 2021). In an effort to protect ourselves and end users of our product, a privacy policy was drafted. This essentially reiterated Oculus’ policies and allowed for our team to enforce any rules we deemed fit for the environments that we have created. It was originally thought to implement a multiplayer aspect into our project, though we ran into challenges including deletions of portions of our project that set us back. Before running into this issue, we found that ethical complications could arise through the use of a multiplayer instance. For example, verbal abuse was a topic we were concerned about. We implemented an acceptable use policy for users to accept upon loading into our training module to cover violations that could terminate a user’s ability to participate in our module. This was created by our team to let users know that harassment of any form would not be tolerated and any violations in an overseen environment with an administrator could be reported. We felt this was necessary in the event of a multiplayer feature being added to our product to foster an inclusive environment and further help the legitimate users of our training module enjoy it to its full potential without unwarranted harassment.
The hardware required to run the training module is an Oculus headset, manufactured by Reality Labs, acquired by Meta Platforms, also known as Facebook. In order to use Oculus headsets, the user must have a Facebook account, which through our research was found to have a history of mishandling user information. Facebook was found to have violated Illinois’ Biometric law (known as BIPA) in 2020, paying $650M for the violation (Mir & Ramirez, 2020). The company has also demonstrated non-transparency to users concerning data handling, breaches, and security issues, leading to federal investigations and fines. Although third-party risks to the user are outside our control, a plan of action to keep users informed of third-party use ensures knowledge and openness at least. Our assessment of Meta Platforms and Reality Labs’ safeguarding of user data is low, however, to make a virtual simulated game with full support, choices are limited in this technology (Oculus Quest 2, 2021). At best, our team decided informing the user to evaluate risks with their data and third-party entities was the most control we could offer in this regard (PricewaterhouseCoopers, 2022).
Accessibility
	ADA stands for the Americans with Disability Act that was signed into law in 1990 by President George H.W. Bush. Ultimately, this enactment, an expansion of civil rights, prevents discrimination against individuals with disabilities in “all areas of public life, including jobs, schools, transportation, and all public and private places that are open to the general public” (ADA National Network, 2022). The law was created to ensure that people with disabilities are granted the same rights and opportunities as everyone else. In 2010, the ADA was expanded further by the Federal Communications Commission (FCC) to include accessibility guidelines in technology through the Communications and Video Accessibility Act (CVAA) (21st Century Communications, 2011). This law as such applies to electronic and information technology and as such must be made accessible to those with disabilities. Due to the inherent nature of Virtual Reality (VR) and the hardware required to use it, some concerns are raised in terms of ADA compliance. For example, the virtual reality hardware required for the training module project includes a headset with a camera, and two controllers, all containing motion tracking sensors. Games or applications may involve rapid motion that can serve as a hindrance to someone who has a disability that limits the range of motion in their arms. And while gamepads could serve as an alternative to motion sensor controllers for applications that don’t rely on rapid movement, the gamepads themselves wouldn’t be able to replace the motion tracking controllers for most games. These are just two examples of issues disabled individuals may expect to face when using a VR headset. 
Another concern encountered in terms of accessibility was the reliance on the visual environment to guide the user through the objectives of the module - technology has not been able to mimic the touch and feel of the environment in simulation. While our project possesses elements that may account for some issues people with disabilities may face, our project is not entirely accessible by those with disabilities and therefore is not ADA compliant. With these concerns in mind, we were able to make additions to the project that can allow users with disabilities to enjoy the module with ease and allow users to complete the module with the goal of teaching users cybersecurity concepts & further allowing them to apply what they learned to scenarios encountered inside the virtual environment. Elements such as snap turns using the right joystick, the ability to grab objects through the use of a raycasting beam, and audio elements have been added to the project to accommodate some, but not all potential disabilities. While some efforts were made to accommodate other potential user disabilities, we discovered limits as to what could be added to the module -  available technology, the skillset of the team, and keeping a balance between inclusiveness and user experience.
The VR headset and hand controllers are required to direct motion and visual tracking in the training module. The training module requires input from a joystick on the left hand for movement and other button presses on both controllers to interact with objects within our virtual environment. Although head and hand gestures are used for typical movement within the module’s locomotion, reaching for objects, and visual tracking system, several features embedded in the controls accommodate users with mobility issues. The Unity XR Toolkit’s class “XRRayInteractor,” or raycast, is a directional beam originating from the hand controls pointer in order to interact with objects and controls within the game without reaching the controller to touch them (Unity, 2022). Objects can be grabbed and manipulated within the raycast beam without reaching by the user. This feature includes controls and button selection within the game with a raycast beam, again without reaching by the user. Including manipulation of objects without too much mobility by the user, locomotion in the game is also joystick controlled. The user has free mobility in the game without the need for walking or mobility outside of the module without finger movement through the joystick control. 
The team discovered an important concern with VR headsets and navigation within a virtual environment. If a user wished to look from side to side, they would need to turn their neck to look in both directions. The team discovered that The Unity XR Toolkit (XRTK) possesses a class called “Snap Turn Provider” that allows for this same functionality to be achieved via a button press (Unity, 2019). This prevented the need for a user to move their head in order to rotate their avatar. Typically, this can be bound to a controller’s analog stick to rotate a player a defined number of degrees with 15, 30, 45, and 90-degree angles being most common (Xinreality, 2019). This was a simple yet effective way to make VR more accessible to those with disabilities that may limit their mobility within our project. It was also found that users with muscle weakness who find difficulty in keeping the headset attached to the head could find relief in using the headset as a viewport only. This was something the team was capable of adding to the module that improved the accessibility for individuals, specifically for those that may have limited mobility in their head or neck.
The main purpose of the Cybersecurity Training Module is to educate the user on basic cybersecurity concepts. An education medium we chose to include in the module is PowerPoint slide videos with text and pictures displaying information on each of the cybersecurity concept lessons taught in the module. To orient the user to the concepts before sending the player through the challenging part of the game, the user views the videos in the orientation portion of the training module. To provide more accommodation to users of all abilities, the video features descriptive audio of the presentation slides. Although a definite limit exists to a visually impaired user’s ability to navigate the training module due to spatial awareness necessary in a virtual simulation, there is current experimenting being done in audio description in 360-degree video content. According to the Royal National Institute of Blind People, our team discovered there are several ways to implement descriptive audio in a simulated environment, however, at the time of research there appeared there was no determined correct way of implementation, including the possibility of overwhelming the user with too much auditory information, thus defeating the original purpose of inclusivity (RNIB, 2019). The team also researched gaze control, which is a feather in virtual reality that can be useful in including an audio description of objects and controls contained within our module. When a raycast beam, or gaze control site collides with a tagged object, an audio cue could be triggered to play and inform the user what exactly they are targeting. However, the team found that this would not solve the spatial awareness problem inherent to a virtual environment & navigating the environment would still present an issue for visually imparied users of our training module. In many standard games and websites, in order to bring inclusivity to visually impaired users, simple features are employed such as magnification and color contrast. Although completely blind users need descriptive audio to comprehend the simulated environment, users with only visual impairments benefit from these simple enhancements being added to the project (Boia.Org, 2022). Though these elements could have been added to our module, we found ourselves unable to implement gaze controlled audio cues. Primarily, we encountered setbacks in our project using Plastic SCM that caused deletions of sections of our project. This was initially a problem we had thought to have overcome, but due to the fact we made use of the VR Lab for each step of our project we were unable to download the Plastic SCM client to the computers located in the VR Lab. Had we been able to use the Plastic SCM client inside the VR Lab, we may have been able to spend less time losing progress and more time focusing on further features to implement into our project.
In addition to the potential difficulties of sensory impairments for users identified by the team inside the game, the hardware requirements for VR are a wearable headset and two handheld controllers. Our training module doesn’t feature remapping for one-handed controls, and the headset is required, which can be bulky and cumbersome to a user with neck or mobility issues (Boia.Org, 2022). Communication between these tracking motion devices and the game engine is required. A user that would be unable to manipulate these physical devices would be unable to use the training module. It was originally thought that one-handed control support could be possible. However, the way we designed our training module it was not plausible to include single-controller support. We designed a tablet to be equipped in the user’s left hand that can be continuously accessed at any point during the training module as a memory refresher and to view the user’s current score. The left controller was designed to be used to reference the tablet, with the use of the right controller and button presses to interact with the tablet.
According to the FCC, the accessibility function of a product, “to be usable, individuals with disabilities must be able to learn about and operate the product or service’s features” (21st Century Communications, 2011). Although our project made an effort to provide reasonable accommodation for some users, our product did not align completely with these standards for all users with disabilities (w3.Org, 2022). Some features in the case of virtual reality and simulations, in order to bring inclusivity to all users, the technology was not yet available at the time of research. In the worst-case scenario, it was found that virtual reality hardware can become a safety hazard to individuals with disabilities without taking proper precautions or having a spotter nearby to help. A wheelchair-bound gamer and author for Ablegamers.org, A.J. Ryan reported he was unable to remove the headset unaided. Therefore, if the game were to freeze or an emergency to occur, without assistance, he was essentially tethered to his computer (Ryan, 2017). Though some VR headsets are wireless and do not require a computer to be connected in order to use them, like an Oculus Quest 2, other headsets exist that require the use of a computer such as the Oculus Rift S. Accommodations must be considered as much as technology can allow avoiding these types of emergency situations. The team came to an agreement to be as mindful as possible to include all users - including disabilities or not - and a user’s respective headset of choice. Though it does not help in the instance of a person remaining tethered to their computer, an added feature that we implemented is a way to exit the game.
As a team, we made a conscious effort to be mindful of accessibility concerns by opting to add not only a visual aid for specific parts of our project but providing an audio aid for those who may be unable to read portions of the project. We also have ensured to include warnings and an acceptable use policy added to our project at the very beginning, though through our research there are many more features that could still be added to reach our goal of complying with the terms laid forth by ADA. By making comparisons to games and other virtual reality software available on the Oculus store, we observed how other developers overcame accessibility concerns. According to the president of Ablegamers, a public charity that works to foster inclusiveness in gaming, “100% inclusion is not feasible…Our goal is to make gaming as accessible as technology will allow” (Along Together, 2022). The disabled community is a diverse one and requires many sets of solutions and different options for the unique challenges faced by any user, especially due to the unique nature of a virtual gaming environment’s multiple point contacts. Remapping not only the key controls, but customizing input controls, or using different input devices would aid disabled people who may be missing limbs or have mobility issues in their head or neck (w3.Org, 2022).
In conclusion, our project has included many features in order to be inclusive to users with different abilities. However, it is not accessible enough to be able to include all disabled people and therefore does not comply with the American Disability Act standards and could be at risk of legal action. There remain additional features that could have been implemented to the module to include more opportunities for people with extra needs. In virtual reality gaming, with the hardware required and visual-spatial environment inherent to a simulation, compliance to accommodation for disabled persons becomes beyond the technology currently available. The headset and controllers required for motion tracking, and a visually represented environment become problematic for people with visual or mobility issues. Providing additional accessibility options to the user, such as the “Snap Turn Provider” within the Unity XR Toolkit, allowed for a more comfortable experience for potential users with specific mobility issues. Along with the “Snap Turn Provider”, the raycast beam provided in the module allows users with mobility issues to manipulate and grab items that could be out of users’ reach. Providing a raycast beam and joystick locomotion further accommodated users with disabilities, allowing them to fully experience the virtual reality module without even having to take a step forward. Additionally, descriptive audio for text in PowerPoints, pop-ups including user feed-back, and the overall virtual reality scene provides accommodations to users with visual impairment. While reasonable efforts were made in these areas to include and allow special accessibility options for some users with disabilities, our team agreed that our project was not able to meet the needs for all users with disabilities to fully comply with ADA.

Security
The training module our team developed provides cybersecurity education and we found that it was paramount to establish an ethical foundation, as knowledge in defense against security threats presented great potential for misuse. To prevent security attacks and vulnerabilities, cybersecurity professionals must learn and use the same skill set that cybercriminals use to launch such attacks. Despite the main purpose of our module being geared towards learning, one ethical issue arose from the knowledge gained from the module itself and the potential for the concepts to be weaponized. Cybercriminals are capable of using educational tools used for learning or security defense and instead misuse them for malicious purposes (Goodchild, 2021). Although the virtual training module has no functionality available for such misuse, the educational qualities could be used to seek out vulnerabilities of businesses and home networks of people who haven’t attained the same awareness. For example, our training module includes tips on creating strong passwords and demonstrates an example of  a brute force password attack. This awareness is aimed to help users create a password that is difficult to crack by using a mixture of alphanumeric and special characters that are not found in most dictionary wordlists. We also teach users what makes for a strong password in an effort for users to understand how insecure their current passwords might currently be. Unfortunately, it was found that this information can easily be exploited to crack passwords through the use of wordlists and brute force methods and also increase the resolve of established cybercriminals to enhance current wordlists. As an action plan to prevent such misuse, simply withholding information as a mitigation tool for the exploitation of such knowledge is ethically debatable as a solution (Oxplore, 2022). An acceptable use policy that clearly states the acceptable guidelines for use of the product, including the agreement to the policy before use of the product will at the very least limit liability and hold accountable the actions of the user using the skills and knowledge obtained directly from the VR training module (BioMelbourne Network, 2020).
The team was in agreement that this was the largest security concern pertaining to the scope of our project. We also agreed that omitting relevant information to teach cybersecurity principles would be counterintuitive to the purpose of our module. We could not effectively teach others about cyber security without exposing what exactly cyber criminals look for or the methods they use to launch attacks on unsuspecting victims.To ensure users of our module were aware that the information contained in our module could be used from the viewpoint of a cybercriminal, we chose to draft an acceptable use policy. We explicitly stated within our acceptable use policy that any and all information included in our training module is to be used for educational purposes only. The team also emphasized the importance of the educational material, advising users to not take what they learn inside our module and use it in the real-world for malicious or unauthorized purposes.
Testing
	Testing was constant throughout our project. Nearly after each addition to the project, someone was using the training module to ensure changes were applied successfully. This was done to ensure everything was working on the project before making additions and pushing it to the main branch of the project. We agreed that getting people that were a little less familiar with cybersecurity would serve as the most accurate response for us. That's another reason why we made sure that the number of testers outside of the college of engineering exceeded the numbers of testers inside the college of engineering. 
User testing consisted of seven willing participants using our training module shortly before final additions were made to the project. Two participants were a part of the DND VR Capstone project group, while five of the participants were those outside of Mizzou’s College of Engineering. A google survey was provided to each individual to complete upon finishing the training module. To see that our module was helping people already was amazing. Four out of the seven willing participants that we had test our module said that they use the same password for everything upon entering into the Passwords room. To see that after going through our module that they were able to actually learn something so fast and be able to apply it to life is crazy to us. 
Most of the testing feedback that was returned was positive. Everyone said that they knew a bit more about cybersecurity after going through the module as opposed to before going through it. In the survey we asked if there is anything that you would add or take away. We had a couple answers for removing the tablet but we didn't think it was enough to remove it completely, because the tablet helps with the overall message of the module, which is to protect and secure your devices.
User Experience
	From the Google Survey, it was apparent there were some fixes we needed to apply in order to call our project complete. There were concerns with text being difficult to read, as well as lighting issues in portions of the project. We have since revamped the font of the text and removed shadows of our narrative canvases to make the text easier to read and prevent lighting issues on the canvases themselves.
Results
	The results of our Google Survey concluded that all seven participants of the training module felt as if they learned something by using our application (See Appendix E). We asked the participants two questions about their own knowledge of cybersecurity - one regarding their cybersecurity knowledge before entering the training module, and one regarding their cybersecurity knowledge after completing the training module. The results show that most users felt that they lacked an understanding of cybersecurity practices prior to using the training module. After using the training module, it appeared that more than half of the participants felt they had a better understanding of cybersecurity practices (See Appendix F).

Conclusion
	In conclusion, 
rewrite this:
Our team has created a cybersecurity training module using virtual reality as a medium. This immersive experience is used to serve as a memorable and enjoyable training module in comparison to other training modules for basic level cybersecurity concepts currently available. The team identified five key elements that are often overlooked in cybersecurity and attempted to emphasize the importance of these elements, educating end users of technology. The five concepts we focused on are as follows: safeguarding physical items, password strengths & weaknesses, hardware and software vulnerabilities, wired vs. wireless networks, and multifactor authentication. Through the use of a narrative, we designed our training module by dividing the module into 2 sections: learning and application of learned knowledge. The learning portion is accompanied by slideshow presentations on each of the five concepts, while the application of learned knowledge takes place in a series of five rooms - one for each concept. Firstly, the user is introduced to the narrative as if they are an unpaid intern and must complete a variety of tasks to determine if the company will hire the intern. In the beginning room, a tutorial on how to use the Oculus controls are available and afterwards the user can progress to the orientation room, where the user learns about each key cybersecurity concept. After learning about each concept, the user is able to move to the first room where they apply their knowledge to the room. To move to the next room(s), the user must complete all tasks within the room before continuing.
plus add these things → → →
key lessons, experiences, recommendations, What would you implement if you had more time? What might you have altered? What lessons were achieved through this reflective process?












Citation Page
Berkman, M. I. (2018). History of virtual reality. In Encyclopedia of Computer Graphics and Games (pp. 1–9). Springer International Publishing.


Curtis, M., Dawson, K., Jackson, K., & Litwin, L. (2015). Mitigating Visually Induced Motion Sickness: A virtual hand- eye coordination task [University of Iowa]. https://doi.org/10.1177/1541931215591397

Goodchild, J. (2021, May 13). How criminals abuse common security tools – and use them against you. CSO Online. https://www.csoonline.com/article/3618834/how-criminals-abuse-common-security-tools-and-use-them-against-you.html
Hate is no game: Harassment and positive social experiences in online games 2021. (n.d.). Anti-Defamation League. Retrieved March 10, 2022, from https://www.adl.org/hateisnogame
Importance of acceptable use policy – IT Systems & Services. (2020, January 28). BioMelbourne Network. https://biomelbourne.org/importance-of-acceptable-use-policy-it-systems-services/
Kenwright, B. (2019, January 14). Virtual reality: Ethical challenges and dangers. IEEE Technology and Society. https://technologyandsociety.org/virtual-reality-ethical-challenges-and-dangers/
Meta Quest. (n.d.). Conduct in VR Policy. https://support.oculus.com/. Retrieved March 10, 2022, from https://support.oculus.com/articles/accounts/privacy-information-and-settings/conduct-in-vr-policy/ 
Mir, R., & Rodriguez, K. (2020, August 25). If privacy dies in VR, it dies in real life. Electronic Frontier Foundation. https://www.eff.org/deeplinks/2020/08/if-privacy-dies-vr-it-dies-real-life
Nilsson, F. (2017). Upper body ergonomics in virtual reality An ergonomic assessment of the arms and neck in virtual environments [Linköping University (LiU)]. http://www.diva-portal.org/smash/get/diva2:1133788/FULLTEXT01.pdf
Oculus Quest 2. (2021, November 8). Mozilla.Org. https://foundation.mozilla.org/en/privacynotincluded/oculus-quest-2-vr-headset
(N.d.). Oculus.Com. Retrieved March 10, 2022, from https://www.oculus.com/safety-center/quest/
Oxplore. (n.d.). Oxplore.Org. Retrieved March 10, 2022, from https://oxplore.org/question-detail/is_knowledge_dangerous
Pietrangelo, A. (2021, February 4). Cybersickness: What it is, symptoms, causes, and treatments. Healthline. Retrieved March 10, 2022, from https://www.healthline.com/health/cybersickness#What-is-cybersickness? 
PricewaterhouseCoopers. (n.d.). Mapping and managing cyber risks from third parties and beyond. PwC. Retrieved March 10, 2022, from https://www.pwc.com/us/en/services/consulting/cybersecurity-risk-regulatory/library/third-party-risks.html
Rutgers researchers discover security vulnerabilities in virtual reality headsets. (n.d.). Rutgers.Edu; Rutgers University. Retrieved March 9, 2022, from https://www.rutgers.edu/news/rutgers-researchers-discover-security-vulnerabilities-virtual-reality-headsets
Securing your reality: Addressing security and privacy in virtual and augmented reality applications. (n.d.). Educause.Edu. Retrieved March 9, 2022, from https://er.educause.edu/articles/2018/5/securing-your-reality-addressing-security-and-privacy-in-virtual-and-augmented-reality-applications
21st century communications and Video Accessibility Act (CVAA). (2011, September 13). Federal Communications Commission.
https://www.fcc.gov/consumers/guides/21st-century-communications-and-video-accessibility-act-cvaa
Accessibility considerations for augmented and virtual reality for the classroom and beyond. (n.d.). Boia.Org. Retrieved April 13, 2022, from   https://www.boia.org/blog/accessibility-considerations-for-augmented-and-virtual-reality-for-the-classroom-and-beyond
Accessibility of virtual reality. (n.d.). Www.W3.Org. Retrieved April 13, 2022, from https://www.w3.org/WAI/APA/task-forces/research-questions/wiki/Accessibility_of_Virtual_Reality
Audio description for 360-degree content. (2019, September 9). RNIB - See Differently. https://www.rnib.org.uk/audio-description-360-degree-content-scripting
Class SnapTurnProvider. (n.d.). Unity3d.Com. Retrieved April 13, 2022, from https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@0.0/api/UnityEngine.XR.Interaction.Toolkit.SnapTurnProvider.html
Class XRRayInteractor. (n.d.). Unity3d.Com. Retrieved April 15, 2022, from https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@0.0/api/UnityEngine.XR.Interaction.Toolkit.XRRayInteractor.html
Eddie. (n.d.). 10 best VR (virtual reality) games for disabled in 2022. Disabilitease.Com. Retrieved April 15, 2022, from https://disabilitease.com/vr-games-disabled/
Heilemann, F., Zimmermann, G., & Münster, P. (2021). Accessibility guidelines for VR games - A comparison and synthesis of a comprehensive set. Frontiers in Virtual Reality, 2. https://doi.org/10.3389/frvir.2021.697504
Ryan, A. J. (2017, January 27). Thoughts on accessibility issues with VR. The AbleGamers Charity. https://ablegamers.org/thoughts-on-accessibility-and-vr/
What is the Americans with Disabilities Act (ADA)? (n.d.). Adata.Org. Retrieved April 13, 2022, from https://adata.org/learn-about-ada
XR accessibility user requirements. (n.d.). Www.W3.Org. Retrieved April 13, 2022, from https://www.w3.org/TR/xaur/




































Appendix A











Appendix B














Appendix C


using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class SafetyNet : MonoBehaviour
{
    public Transform xrOrigin;

    void Start()
    {
    
    }

    void Update()
    {
        
    }

    private void OnTriggerEnter(Collider other)
        {
            if (other.gameObject.tag == "net")
            {
            xrOrigin.transform.position = new Vector3(-18.2299995f, 1.65999997f, 5.65999985f);
        }
    }

}


Appendix D



using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Tablet : MonoBehaviour
{

    public GameObject tablet;
    public Transform leftHand;
    public GameObject lHand;
    private GameObject t1;
    private GameObject h1;

    // Start is called before the first frame update
    void Start()
    {
    }

    // Update is called once per frame
    void Update()
    {

    }

    public void GetTablet(Transform newParent)
    {

        tablet.transform.SetParent(newParent, true);
        StartCoroutine(PositionTablet());
    }

    IEnumerator PositionTablet()
    {
        yield return new WaitForSeconds(1f);
        tablet.transform.position = new Vector3(leftHand.transform.position.x, leftHand.transform.position.y, leftHand.transform.position.z);
        //tablet.transform.rotation = new Quaternion(-0.496706903f, 0.80676353f, 0.300120205f, 0.111097589f);
        //t1 = tablet.transform.Find("t1").gameObject;
        //h1 = lHand.transform.Find("h1").gameObject;
        //tablet.transform.position = h1.transform.position;
    }
}
 


Appendix E
Appendix F


