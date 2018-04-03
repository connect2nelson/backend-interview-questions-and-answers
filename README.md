
## Back-End Developer Interview Questions And Answers

I'm not a big fan of asking technical questions in job interviews: I rather prefer to sit together with candidates in front of some real code, hands on the keyboard, facing a real problem, and have a full day of pair programming, hopefully rotating with all the other team members. Yet, I feel some technical questions could be a good starting point to begin an engaging and nice conversation, and this can be useful to get a deeper knowledge of each others.

This repo collects a number of back end related questions that can be used when vetting potential candidates. It is by no means recommended to use every single question on the same candidate: that would take hours, and would have no sense at all, as they cover a too broad set of topics for a single developer's to possibly know. Browse the section you find more relevant for your context, 


#### Notice
Most of the questions are open-ended, and some of them just don't have a right or a wrong answer. On the contrary, they are intended to be used as the starting point for a conversation that hopefully tells you more about the person's capabilities than a straight answer would. Personally, I would even choose the questions whose answers are not yet clear to me.

Again, I stress that just asking questions is hardly sufficient. Complete the interview with a long pair programming session with your candidates: it is one of the best opportunities to know each others' style and approach and to let candidates know some details about their future day job.

This project is admittedly inspired by Back-End Developer Interview Questions by @arialdomartini


#### [↑] Questions about Design Patterns:
- Q. What is an Anti-corruption Layer?

  A. Implement a façade or adapter layer between different subsystems that don't share the same semantics. This layer translates requests that one subsystem makes to the other subsystem. Use this pattern to ensure that an application's design is not limited by dependencies on outside subsystems. This pattern was first described by Eric Evans in Domain-Driven Design.


  - Q. What is an Anti-corruption Layer?

    A. Implement a façade or adapter layer between different subsystems that don't share the same semantics. This layer translates requests that one subsystem makes to the other subsystem. Use this pattern to ensure that an application's design is not limited by dependencies on outside subsystems. This pattern was first described by Eric Evans in Domain-Driven Design. Use this pattern when:
   
    a) A migration is planned to happen over multiple stages, but integration between new and legacy systems needs to be maintained. 
    
    b) Two or more subsystems have different semantics, but still need to communicate.
    
    