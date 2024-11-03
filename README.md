# TaskBreakdown
Tasks diagram / graphical editor Web-App

TaskBreakdown
Tasks diagram / graphical editor Web-App
This project aims to build a web application for visualizing and managing tasks in a hierarchical structure, similar to a Work Breakdown Structure (WBS).  It will provide a graphical editor for creating and manipulating task diagrams, offering a centralized platform for project planning, source code management, and collaboration between developers and clients.
Features
 * Hierarchical Task Breakdown:
   * Visualize tasks in a tree-like structure.
   * Each task can have child tasks, labels, descriptions, and appearance properties.
   * JSON-based persistent storage for each task.
 * Tech Stack Context:
   * Top-level tasks can be associated with a "tech stack" (e.g., frontend, backend).
   * Visual representation of tech stacks as clouds encompassing sub-tasks.
   * Option to define different tech stacks for sub-level tasks using gateways.
 * Implementation Modules:
   * Terminal tasks (leaf nodes) include source code editors.
   * Pluggable language transpiler for converting code between different languages.
   * Transpiler selection available through a dropdown menu at the top-level tech stack node.
 * Single Source of Truth:
   * Diagram serves as the central hub for project documentation, source code, and client communication.
   * Facilitates feedback and collaboration by providing a visual representation of the project's progress and structure.
Future Development
This project is envisioned as a foundation for a more comprehensive visual programming environment. Future development may include:
 * Visual Programming Constructs:
   * Class and function declarations and instantiation.
   * Visual parameter passing.
   * Name space visualization, object property linking.
   * Control flow visualization (if-else, loops, switch, exceptions, promises, callbacks).
   * Visual representation of declarations, literals, expressions, and object manipulation.
   * Package and library visualization.
Contributing
Contributions are welcome! Feel free to submit issues, feature requests, or pull requests.
License
GPL License

#Discord server
https://discord.gg/WWd3PT76


*Discord notes
I want to do something similar to https://en.wikipedia.org/wiki/Work_breakdown_structure?wprov=sfla1

*<Top-down approach>

Tasks breakdown diagram editor
Each task (of a workspace project) can have children tasks(breakdown) 
And a task-label ,and a task description text area, and appearance properties

Each task should have a Json for persistent storage

Top 2 levels of tasks should have a tech stack context (appears visually as a cloud for all the sub tree) , although any sub level tasks can also have a gateway (different) tech stack

And the terminal tasks (that can be implemented, in other words, very focused and narrowed down) will have implementation modules (source code text area) in addition to a task-label and a task description

The implementation modules in a near future stage (of the grand project) should have a pluggable\interchangeable language transpiler ( visually on the diagram at a top most tech-stack node\task as a drop down menu of languages transpilers )


*This diagram(the workspace project) should be a single source of truth

Meaning the diagram is:
1. the integration of all the documents of the workspace project
2. The central repo of the product\ project source code files (generated from the transpilers) 
3. Central bridge between all the client teams and all the developer teams, in otherwords, the workspace project is the visual presentation of the project from-the-developer-to-the-client , and it (the interactive diagram) is the platform for feedback from-the-client-to-the-developer , in other words, capturing the feedback cycle in a central repo

This task-breakdown app is one incarnation of many old projects of the dream of building a visual programming language, i mean other projects will integrate\augment

For example , in another (stage 3 or maybe stage 2 ) project will be to develop(into stage 1) visual constructs of programming constructs , like 
1. a class declaration and instantiation
2. a function declaration and instantiation
2.1 visual parameter passing,
3. visual name space scopes and references and linkages of properties of objects by other object properties ( inbound properties & outbound properties) 
4. Control flow
4.1 if-else expressions
4.2 loops expressions
4.3 switch expressions
4.4 exception handling
4.5 promises\async
4.6 callbacks and event-driven 
5. Declarations and literals
6. Expressions (arithmetic, logical, dot-notation, method calls, ect,)
7. Objects(and builtin data types and user define data types) and properties creation and manipulation
8. Packages and libraries

