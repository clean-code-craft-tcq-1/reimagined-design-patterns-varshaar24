# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.



    Observer Pattern

    With this pattern , it allows us to view and observe the changes and only act on it when needed. The usage of this design pattern is used in any ethernet communication as to just get the data from server when there is update in the data from server. This reduces the higher bandwidth usage in general.

    Advantages :- It can act on the events without coupling to it. We need not poll and ask if there is any data that is updated.

Disadvantage:- It requires prior subscribe to that event. Although this doesn't seem like disadvantage.

    Visitor Pattern

    Visitor pattern helps to realize open-close principle. With this pattern, we could add new features , without altering the existing code. This reduces the effort for unit testing as well as the older tested code need not be revisited. The usage of this pattern is used in many places such as :- to add the ways of communcication about the change of event. If the nofier was via email first , then we can add via telecommunication also as an added feature in the future development.

Advantage:- Major advantage is in reduced maintanence even with respect to testing and coding both.

Disadvantage:- :- I do not think there would be any disadvantge of a design pattern which involves building on the existing code.

    Strategy Pattern

    Strategy pattern provides a way to follow the open-close principle. Example of usage of startegy pattern is in a shopping mall, to segragate the cutomer categories based on their shopping value and give the benifits accordingly. Suppose the gold customers get 10 % off, silver customer gets 5% off. Here it is good to use strategy pattern such that the customer doesn't know about the categories. In this startegy, it is possible to add any extra offers to each category envidually or change the categories itself.

    Advantage:- Follows the open-close principle.

    Disadvantage:- I do not think there would be any disadvantge of a design pattern which involves building on the existing code.

    Memento Pattern

    The Memento pattern helps to store the states of an application and restore it when needed for furture reuse. This helps in many applications of basic texting app as well. When we wish to go back in time and undo or redo what we did, the memento pattern helps.

    Advantage:- The states of an application is recorded and hence it helps in reviewing the history as well.

    Disadvantge:- It requires memory to take snapshot and store the states of an application.

