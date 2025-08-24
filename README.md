# CS230

The Gaming Room was the client, and they wanted to expand their game Draw It or Lose It into a cross-platform, web-based version. The software requirements included creating and managing teams, assigning multiple players per team, ensuring team names were unique, and storing all game data in memory without external databases. The system also needed to be scalable and structured for future deployment across web and mobile platforms

One thing I did particularly well in this documentation was clearly defining the system’s structure and how the different classes (GameService, Game, Team, and Player) interact. By using object-oriented principles like inheritance and the Singleton pattern, I showed how the design prevents duplicate team names and keeps the program lightweight while still supporting scalability

The process of writing the design document before coding was very helpful. It allowed me to think through requirements, constraints, and architecture ahead of time. For example, writing out the UML and domain models made it easier to visualize how the system’s objects would interact, which guided the later implementation phase.

If I could revise one part of my documentation, I would expand the security section. While I mentioned Linux’s strong security features, I could have included more detail on how the application itself should handle encryption, authentication, and protecting user data as it scales. Strengthening this part would make the design more production-ready

I interpreted the user’s needs by prioritizing scalability, cross-platform support, and performance. Choosing Linux as the main operating environment reflects this, since it’s reliable, cost-effective, and widely used in production. It’s important to focus on the user’s needs during design, because if the application doesn’t scale or meet their expectations, it won’t succeed regardless of technical execution.

When approaching the design, I broke it down step by step: defining requirements, considering constraints, evaluating different platforms, and then structuring the architecture with UML. Going forward, I would continue to use structured design techniques like requirement analysis, system modeling, and modular coding. I would also incorporate more user feedback early in the design process to validate decisions before development begins. These strategies ensure the final product is both technically sound and user-focused.
