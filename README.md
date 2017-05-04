# CSCI 260 - Course Blog
## CSCI 260 Software Engineering Spring 2017

This page is devoted for my software engineering course

## What Software Engineering means to me?

```markdown
Software Engineering for me is the art and science of designing, 
constructing, and maintaing general computer software applications.
It means being creative in designing certain software, while also 
using logic in the process. 
```

## Pragmatic Programmer

### Chapter 1

```markdown
There are many several points that I found important in this chapter.
First of all, the chapter talks about taking responsibility on the work
that you are going to commit to. It is important to make a call based on
your own ethics and judgment. If the work does not seem to match your personal
judgment, do NOT take the responsibility because that means you are also
responsible of the outcome. If you take the responsibility and the outcome
is not what to be expected, do not make excuses, provide options on
what can make it work or better. The chapter also talks about the disorder 
of the system, or the disorganized code. It's interesting how the authors compare this
to "broken windows." What interests me even more is the stone soup story. 
It gives a clear picture of how important teamwork is, and also how effective
small things can be. Furthermore, the author talks about the good-enough code.
I learned that good enough code does not necessarily mean sloppy and poorly produced
code. Once the program meets the requirements of the users, there is no need to
further develope the code. You just need to know when to stop. More importantly,
what I found the most important in this chapter are the knowledge portfolio and
the communication. It is interesting on how closely related investors and programmers
are. We developers invest every day using our knowledge, just like the investors.
For the communication part, I think it is the most critical part of software engineering
because you first need to know what your audience needs or interested in before
planning out what to say or to be presented. Then, once you are already in process,
communicating with the audience early by showing them your drafts on what you are doing
or planning to do helps you to get feedback from them early. That way, you can fix things
early in the process.
```

### Chapter 2
```markdown
Chapter 2 is quite a long chapter. It starts with a topic of the bad of duplication and the 
important of documentation. Documenting your code not only tells other people what your program 
does, it also helps you to recognize your own code. Sometimes, after you finished a project in 
a while, you tend to forget what you have coded, or the purpose of the project. Also, having 
duplicate codes is bad because not only is it difficult to make a change without ruining the whole 
project, it is also a waste of time to go back and change the same code in every method. This is 
why decoupling is encouraged. The book related the term Orthogonality to the independent or 
decoupling of each class of the code. There are many benefits to using Orthonality. The major 
two are gaining productivity and reducing risk. As mentioned before, having a method that can be 
reused over and over again can save a lot of time. All changes are localized, so the development 
time and testing time are reduced. Having these in mind, applying them to the real work can be 
very effective. Using the same analogy on project teams, we can divide the team into small groups 
and assign each group a specific task, so that we all do not get confused of what to do. Having 
this kind of organization not only reduces risk of making change of something in the project, 
it also reduces time of going about to discuss the change. One topic that I found interesting 
would be the tracer bullets analogy. Applying the approach of aimming the target before firing 
can be very helpful anf effective to a lot of developers. With the approach, developers can have 
a better feel for their progress because their users are able to see their progress. Each and every 
iteration the developers commit, the users can go ahead and see whether it is what they want. 
This, I think, is also part of commnication. Although it is not a direct one, but the result 
is about the same. Being able to see what the developer is doing, users can make a comment and 
suggest or require a change to the program. Getting feedback early is always a good thing.
The last topic I found very important in this chapter is the estimation. Whether it be estimating 
a certain value or a period of time to get something done. Giving an estimation of how long you 
will be working on your project can be critical to not just you as a developer, but also to the 
users that wait for their product to be finished. Another important aspect of the estimation is 
it keeps you organized and not lose track of what you are doing. Making a schedule of what needs 
to be done in estimately how many days can be very helpful with those lacking time management.
```

### Chapter 3
``` markdown
What I found interesting in this chapter
```

### The Mythical Man-Month: Chapter 2
``` markdown
In chapter 2 of the Mythical Man-Month, the author talks about how most of the software projects have gone awry
for lack of calender time more thna for all other causes combined. He first mentioned the optimism that most of 
the young programmers have. He said that they always have the same thought of how debugging and testing their
softwares won't take too long or how the bug they found is the last bug, and how "all will go well."
With this in mind, he goes on to talk about how the men and the months are interchangable. After going over
the systems tests, the gutless estimating, an the regenerative disaster, it turns out that adding more manpower
to a late software project actually makes the project finished later (Brooks's Law), making the estimated schedule even worse.
In one of the discussion, it makes sense how adding more manpower does not really make the project finished earlier
or at least on time. The example talks about the 12 man-month project - assigning 3 men for 4 months to finish a project -
assuming that the task for the first month actually takes two, adding 2 more men to the team does not make the project
finished earlier than having 3 men to continue work on the project since the 2 new men will need traning, which might take
up to a month. Instead of giving the 2 new men the traning, the 3 men can continue working on the project and can
finish it by the same time as having two more men added to the team.
```

### Chapter 4
``` markdown
Chapter 4 talks about how pragmatic programmers turn depressing situations into advantage, and how they 
write codes to defend themselves, not other programmers. They first talk about design by contract and 
how our develop have to be like a business contract. They are required to do what their requirements specify,
but anything else. And the control classes only have to require that, not more than the methods it is for.
The next focus is about dead programs tell no lies. Sometimes we have system errors, like memory performance
or maybe a problem that spouse it will never happn, then you don't only catch it in an exception and let it pass
to the final testing, you can use exceptions to find what the problem is but not to ignore the problem.
At least a dead program is less dangerous than a sick one. In the assertive programming section, when we find
an error that suppose it will never happen, in some programming languges we have the ASSERT finction. It is
only for this exceptional errors, not for every kind, and if our language does not have this function, we likely
have to create one. The next section is when to use exceptions. It mainly talks about proving that if the program
runs correctly when all exceptions were removed, then you are making a good use of the exceptions. It is
for exceptional errors in the system, not for every kind. In the how to balance resources, it follows a few
simple rules: The function that allocate the resource needs to be the functions that deallocate it too.
If you allocate some resources to your code, deallocate it in inverse order will avoid some conflicts.
if you will allocate the same resources in many places, then deallocate it in the same order. The same rules
can be applied at constructors and destructors of an object, where dynamic memory is allocated by nodes.
Like pragmatic programmers, we always have to check for overload our resources like memory, CPU, data buses
and so on, there exists a lot of programs that do this for us, and if it is difficult to deallocate resources,
we can create a stack to determine when the resource is free to be deallocate.
```

### Chapter 5
```markdown
Chapter 5 first talks how the world changes every day, so our code must be flexible, too. 
   - Decoupling and the Law of Demeter: couple your classes to no more other classes than reasonably necessary:
   your instance variables, method arguments, and new local objects (the law of demeter). Have those objects
   perform a complete service for you rather than giving you an object with which you perform the service.
   This will require many delegation-only methods, though.
   - Metaprogramming: provide many configuration option to avoid change programming. Put abstractions in code 
   and details in metadata. If you drive this far enough, you may even be able to implement different systems
   using the same application engine but just with different metadata. Business rules and workflows are good
   candidates for business data. Great applications can change then even without requiring a restart.
   - Temporal coupling: design for maximal concurrency, avoid introduce unneeded ordering constraints on steps.
   This may help your design quality too, for example, because you may ask yourself why that global variable
   that you now need to lock exists at all.
   - Events and views: event-based control is a good decoupling mechanism, for example, in a publish/subscribe
   structure. In particular, separate views from models, e.g. in a model-view-controller (MVC) structure, whether
   in the context of GUIs or elsewhere. You can stack them: one structure's view becomes the next, higer structure's view.
   - Blackboards: an even stronger form of decoupling, where only data structures are shared but no call coupling
   is explicit is a blackboard storage (e.g. JavaSpace). Asynchronous and possibly transactional, were events that
   are created by the fact that an object with certain propoerties appears in the storage (written by some other
   participants). Often combines with rules engines to coordinate workflows.
```

### Chapter 6
```markdown
In the craft of programming is necessary to have an active participation in the possible resolution of the problems,
if we code mechanically, we will produce ugly, inscable and bad performed system.
    - Programming by coincidence: to make sure that your program works tomorrow, you must thoroughly undersand 
    why it works today. If you don't, then your code may be slow, confusing, only partially correct, error-prone
    to change, and prone to collapse if the objects change that it is calling. Know what you are relying on.
    Don't rely on anything you don't need to rely on.
    - Algorithm speed: the O-notation and runtime complexity classes, complexity estimation rules-of-thumb,
    estimate, then test your estimates. Be pragmatic about algorithm choice.
    - Refactoring: building SW is more like gardening than like construction; a constant process of monitoring
    and care. Regularly refactor your SW to push back duplications, non-orthogonal design, outdates knowledge,
    and performance degradation. Refaction early, refactor again, refactor often, and avoid telling your clients
    you do it. Make small steps and do not change functionality at the same time. Have automated tests to
    safeguard your changes.
    - Code that's easy to test: write automated tests for each module that test against its contract (self-testing
    code). Use assertions in the code. Test lowest-level modeules first and higher-level modules later (to simplify
    defect localization). Co-design code and its tests. Store the test code close to the module code. Tests also
    serve as documentation. Use a test harnessly. Do not throw away the ad-hoc tests you invented during debugging.
    Make sure you can test your software during production, too. Log files and semi-official debugging console
    windows or built-in webservers are helpful. Establish a standardized test culture.
    - Evil wizards: if you use a Code Generation Wizard, make sure you understand the code produced, because it
    will be interwoven with your application.
```

### Chapter 7
```markdown
If before we start the project, we don't know if we can carry with the problems that the project will bring us, 
it's time to be honest and save some money and time to our sponsors, but if we decide to take the risk, then 
it's time to know how to estimate.
    - The requirements pit: "Requirements rarely lie on the surface. Normally, they're buried deep beneath layers
    of assumptions, misconceptions, and politics." Identify policies (e.g. access privilege rules) that come as
    part of requirements and expect them to be volatile; make then configurable. Identify user interface details
    that come as part of requirements and initially treat them as manner of speaking only. Understand and document
    why users want certain things, not just what they want. To understand the domain, become a user yourself for
    a week - it helps build trust and rapport, too. To document requirements, use a suitable use case format.
    Do not overspecify, stick to what's actually needed. Track all requirements changes to avoid creeping featurism.
    Maintain a glossary and stick to those terms. Use hypertext and internally publish the requirements.
    - Solving impossible puzzles: the key to coping with seemingly impossible problems is discriminating real 
    constraints from perceived ones. The question is "are you even solving the right problem?" Then, enumerate all
    conceivable routes and carefully explain for each why it cannot work. Find you weak arguments: there are your 
    possibilities.
    - Not until you're ready: don't start as long as you have doubts, but start when you are ready. How to discriminate
    real doubts from mere procrastination? Prototyping will often reveal the problrm behind your doubts or quickly
    get you ready.
    - The specification trap: don't write highyly detailed specifications.
    - Circles and arrows: don't become a slave to formalized methods. Beware of requirements specification notations
    your end users do not understand, beware of developer overspecialiation, beware of methods that restric the 
    flexibility of your designs. Never underestimate the learning cost for a new method. Each method should be 
    a tool in your toolbox, selected and used when approproiate and its use constantly refined.
```
