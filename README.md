CS 230 Portfolio Reflection

Briefly summarize The Gaming Room client and their software requirements. Who was the client, and what type of software did they want you to design?

The client was The Gaming Room, a company that wanted to expand its Android game, Draw It or Lose It, into a web-based application that could operate on multiple platforms. The application needed to support multiple games, teams, and players while maintaining unique names and identifiers for each object. The client also needed a secure and scalable server environment, reliable network access, browser compatibility, and a design that would prevent duplicate instances of the game service.

What did you do particularly well in developing this documentation?

I did particularly well identifying the differences among Linux, Windows, macOS, and mobile platforms and connecting those differences to the client’s needs. I evaluated each platform’s strengths and weaknesses and recommended Linux as the server platform because of its security, stability, scalability, and lower licensing costs. I also used the domain model and object-oriented design patterns to clearly explain the relationships among the GameService, Game, Team, and Player classes.

What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me understand the application’s classes, responsibilities, and relationships before focusing on the code. The UML diagram showed how the classes were connected, while the requirements helped identify rules such as using unique names and identifiers. Planning the structure first made it easier to apply the Singleton and Iterator patterns, organize the application, and reduce duplicate code.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would revise the evaluation section by expanding each table cell into a more complete and detailed comparison. I would include more information about compatible server software such as Apache Tomcat and Nginx, operating-system licensing, scalability, load balancing, and reverse proxies. I would also add more details about client technologies such as HTML5 Canvas, WebSockets, WebKit, and Blink. Finally, I would further explain development tool costs, Maven build automation, and whether the project would require one development team or multiple teams.

How did you interpret the user’s needs and implement them into your software design? Why is it important to consider the user’s needs when designing?

I interpreted the user’s needs by identifying the main goal of making Draw It or Lose It available through web browsers on several operating systems and devices. I included a distributed client-server design, unique game and player information, responsive browser access, centralized data management, and security protections. Considering the user’s needs is important because the software must solve the client’s actual problem and provide a reliable experience for players. Ignoring those needs could result in an application that is difficult to use, insecure, or incompatible with the devices customers use.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached the software design by first reviewing the client’s requirements and identifying the application’s main objects and responsibilities. I then used a domain model, UML diagram, design patterns, platform comparisons, and technical recommendations to develop the overall design. In the future, I would continue using these strategies while also creating a requirements checklist, simple prototypes, and a testing plan earlier in the process. I would also request client feedback throughout development and evaluate security, performance, scalability, compatibility, and accessibility before finalizing the design.
