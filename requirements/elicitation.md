# Requirement Elicitation

## Preparation of Elicitation (Inputs)

### Project Scope

| **Project Overview** | This project aiming to develop the "Terror in Tilburg" board game using streamlined computer simulation. The object is to maintain the game's role-play and storytelling dynamics while making it more accessible and interactive for players. |
| --- | --- | 
| **In-Scope** | Develop the "Terror of Tilburg" computer simulation game, keep the role playing and storyline, design a user-friendly interface, support multi-player mode, simplify the probability system, reduce the game round to 4 and add election mechanism  |


## Elicitation Activities

+ **Group discussion**
+ Purpose and Platform:
Engage the project team in a discussion to finalize decisions on the game's target users and the educational purpose. This will help tailor the gameplay and content to the identified user base.
Discuss the suitability of a desktop app versus a web-based platform, considering the advantages of each based on feedback from the team and client’s supervisor.
- Login Methods:
Decide whether to allow anonymous access through QR codes or require user registration. This involves evaluating the pros and cons, such as privacy concerns versus ease of access.
+ **Interview**
+ Client and Supervisor:
Conduct interviews with the client and possibly the client’s supervisor to get a deeper understanding of their expectations for the visual style and usability standards.
Inquire about their views on the need for real-time communication features and the extent of functionality for saving game states.

## Roles And Responsibilities

| Role              | Name(s)                   | Responsibilities                                             | Collaborative Approach                                       |
| ----------------- | ------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Scrum Master**  | Xinyi Yuan                | Responsible for organizing and coordinating the requirements mining process to ensure tasks are completed on time and to periodically check the progress and quality of requirements collection. | Schedules and hosts meetings for requirements gathering, discusses requirements priorities with product owners, and ensures smooth communication among team members. |
| **Product Owner** | Yuchen Dong               | Provides high-level requirements and goals for the project, defines the direction and focus of requirements mining based on customer feedback and business objectives. | Provides background information on requirements and business objectives to team members, participates in requirements analysis and validation, and ensures that the requirements collected are aligned with the project objectives. |
| Quality Assurance | Yuxing Huang, Sixuan Chen | Ensures that the final product meets quality standards and requirements through testing and validation. Identifies bugs and issues, and collaborates with the development team to resolve them. | Works closely with development leads to understand the implementation and ensure thorough testing. Provides feedback on potential issues and works with UI/UX designers to ensure the product meets user expectations. |
| Architecture Lead | Tongjia Hu                | Designs and oversees the technical architecture of the project, ensuring that it aligns with the project's requirements and goals. Provides guidance on technical decisions and standards. | Collaborates with the development lead and UX/UI designers to ensure architectural decisions support the overall design and functionality. Engages with the development team to address architectural concerns and implement solutions. |
| Development Lead  | Yingyi Luan               | Leads the development team, ensures coding standards and practices are followed, and coordinates development activities. Oversees the progress of development tasks and integrates features according to the project plan. | Works closely with the architecture lead to align development with technical specifications. Collaborates with QA to address any issues and ensures that development aligns with the product owner’s requirements and UX/UI design. |
| UX Design         | Wenyao Wang               | Focuses on the user experience aspects of the product, ensuring that the product is intuitive and meets user needs through user research and design. | Collaborates with UI designers to ensure cohesive design and with the development team to implement user-centric solutions. Provides feedback on usability and ensures that user experience considerations are integrated into the design. |
| UI Design         | Wenquan Wan               | Responsible for the visual design and layout of the product, ensuring it is aesthetically pleasing and consistent with the brand. | Works with UX designers to create a cohesive visual and functional design. Coordinates with developers to implement design elements and ensures that the UI meets the project’s design standards. |
| Testing           | Jiayuan Li                | Conducts various types of testing (e.g., functional, regression, performance) to ensure the product meets quality and performance standards. | Collaborates with QA team members and development leads to understand features and create effective test cases. Provides feedback on test results and works with developers to address any identified issues. |
| Design Lead       | Runbing Wang              | Oversees the design process, ensuring that both UX and UI design elements are aligned with project goals and user needs. Coordinates design efforts and provides guidance to UX and UI designers. | Works with UX and UI designers to ensure a unified design approach. Collaborates with the product owner and development lead to align design with functional requirements and technical constraints. |
| Development Team  | All of the team           | Executes the development tasks, writes code, integrates features, and ensures that the product meets technical requirements and quality standards. | Collabor                                                     |

## Question And Strategies
### Strategies:

+ **The easy ones go first**: Dig the interviewee’s requirement from broad to narrow, from shallow to deep.
+ **Ask open-ended questions and probe**: Ask questions that can elicit detailed responses，allowing for better understanding of the requirements.
+ **Record and Organize information**: To ensure that the information provided by interviewees is documented accurately and clearly.
+ **Consider from the perspective of other participants**: Prepare questions from other stakeholders’ views to gather diverse perspectives on requirements.
+ **Use Scenarios and Case Studies**: Encourage interviewees to provide specific scenarios and present cases to them can help to enforce the communication and get a better understanding.

### Questions List :

+ What are the reasons/advantages that prompt the idea for playing this game online rather than face2face 

+ Who are the target users? Students? What purpose do you want to use this game for (Educational purposes or Commercial purposes) 

+ What platform should the software support? (Website, desktop app or smart-phone app) 

+ Do you prefer your game to allow players to join matches anonymously by scanning a QR code, or would you prefer players to register an account and log in to participate in the game?

+ How do players communicate with each other in real time? Does our product need to contain a chat box/voice box/real-time voice conversation?Do we need functionality to save the current game state and load a previously saved game?

+ What overall visual style and theme do you envision for the game? 

+ Are there specific usability standards to follow to ensure the interface is user-friendly for everyone? How should the interface support users with special needs, such as color blindness or visual impairments?

+ Does it need a player facilitator for the operation of this game? How to determine whether an argument is valid in the Pros and Cons system if the system has to be the facilitator?

+ Do you need a system design for specific game achievements to increase player engagement and repeat play?

+ What range of player count do you prefer for each game session?

+ What are the specific actions available to players, and what icons will represent these actions?
+ What are the objectives for each player/role? Can players customize their roles (including the objectives) or actions before the game starts?
+ Are there specific brand colors or elements that should be incorporated?
+ How to form a government, what is the "off-table" negotiation. What is "radical shift to the right", are there any conditions to determine whether it is shifted to the right
+ Does the game have any unit / troop movements 
+ Should we have a strict limitation of the game time, each round, each player 
+ How should the voting system work? How to decide the player gain an additional vote, is it by the end of player turn or before Election round?
+ Do players play forces such as Hofstadt Network and Dutch Government, or party leaders such as Mark Rutte and Lodewijk Asscher?
+ Does every player have to raise an argument in each turn in a specific order? Or just one argument for each turn (which player is responsible for proposing it). How do the results of arguments affect the final vote?



## After Elicitation (Outputs And Follow-up Actions)
### Follow-up actions

1. Organize the notes of the interview.
2. Discuss the requirements in the group, determine the scope and identify the roles, form a general framework of this project and decide where to dig deeper.
3. Transform the requirements into specific scenarios or user stories to form a better understanding of the system and serve as a measure to verify the needs of the client.
4. Identify the challenges and elements which can cause failure in this project and start to seek a possible solution.
5. Prepare questions for those requirements that still remain unclear.

### Organised notes

| Agenda/Question                                              | Description/Answer                                           | Action                                                       |
| ------------------------------------------------------------ | :----------------------------------------------------------- | ------------------------------------------------------------ |
| The reasons/advantages for playing this game online rather than face to face | 1. It's intended as this sort of educational tool, so sort of enabling a bit more of a remote play as well, but still keeping that kind of role playing aspect to it.<br/> 2. It's good to add a chat function. |                                                              |
| Target users and purpose                                     | 1. Target user: predominantly focused on students.<br/> 2. Purpose: It's predominantly an educational tool as a way to test the knowledge that the students have learned through the semester <br/> | Prepare the persona for target user                          |
| What platform will it run on                                 | Probably a desktop app, about web based should double check with client's supervisor | Waiting for reply                                            |
| Log in or scan QR code                                       | Both are good.                                               | Discuss the final decision within team(For all)              |
| Will the players communicate in real time or use a chatbox   | It's good to add a chat function if possible                 | 1.Add the chat function to "should do"                       |
| Save the current game state                                  | It's good to have save function if possible.                 | 1.Add the save function to "could do"(For all)               |
| Overall visual style                                         | Client haven't thought too much about the visual style<br/>  | Contact with client more about this when start to implement(For product owner) |
| Usability standards                                          | It's good to consider that if possible<br/>                  | Discuss in the sprint plan meeting(For all)                  |
| Does the game need a player facilitator                      | It's good to add timer function<br/>                         | Consider it in the meeting                                   |
| Game achievements                                            | No need for this function since it already have this.        | Delete game achievement function                             |
| Role name                                                    | Client don't want to change the role name                    |                                                              |
