## Understanding & Inferring User Tasks and Needs

### Venue
The tutorial will be held at [The Web Conference](https://www2018.thewebconf.org/), 2018 (WWW) in Lyon, France, April 24th, 2018. The tutorial begins at 9 AM on Tuesday in Salon Gratte-Ciel.

**Tutorial material to be released shortly**


### Introduction
Search behavior, and information behavior more generally, is often motivated by tasks that prompt search processes that are
often lengthy, iterative, and intermittent, and are characterized by distinct stages, shifting goals and multitasking. Current
search systems do not provide adequate support for users tackling complex tasks due to which the cognitive burden of keeping
track of such tasks is placed on the searcher. Developing a comprehensive understanding of user's tasks would help in providing
better support and recommendations to users based on their contextual information and as a result, help users accomplish the
task. In this tutorial, we begin by discussing recent advancements towards building task based IR systems and present analytical
results which highlight the importance of considering tasks as the focal unit of modelling search behavior. Additionally, we
consider the challenge of extracting tasks from a given collection of search log data and present some recently proposed task
extraction techniques which rely on recent advancements in bayesian non parametrics, word embeddings, structured predictions
and deep learning. Finally, we present applications of task inference techniques alongside discussing the implications of task
based systems & summarize few key open research questions.


### Target Audience
Intermediate researchers, industry technologists and practitioners. We are expecting a general background in information retrieval
and machine learning. Given the interest of the WWW community in information access, retrieval and user modelling,
this tutorial on task based systems will provides WWW attendees with a novel perspective of analysing log data, enabling them
to view user interactions in a new light. The algorithmic approaches presented would help not only academic researchers but
also industrial practitioners in better developing systems which support users in accomplishing their task.

### Learning outcomes
The tutorial is aimed at introducing practitioners to the upcoming field of search tasks. The main focus of the tutorial is (i)
helping the audience understand the importance of consider tasks as a rich information source, (ii) discussing novel algorithmic
approaches to extract tasks from log data, (iii) imparting knowledge on how to leverage this task information for various
applications across different domains. The tutorial would help practitioners from various different subfields including search, user modeling, personalization and recommender systems develop a comprehensive understanding of user-tasks and equip them
with the necessary mathematical and analytical tools required to extract task information to be used in their domain of choice.
In addition to the algorithmic overview, we intend to provide details on existing datasets that could be leveraged, including
insights from the TREC Tasks Track (2015-2017) which the organizers have organized. In addition to literature survey and slides,
we also intend to provide participants access to a software toolkit which provides implementation of various state-of-the-art
approaches.

### Outline of the tutorial
```
1. Introduction
  - Evolution of search
  - Functionality levels of search offerings
  - Conversational & Task completion engines
  
2. Characterizing Tasks
  - Understanding Intents & Tasks
    - Query intents in IR
    - Search sessions
    - Sessions --> tasks
  - Characterizing Tasks across devices
    - Taxonomy of desktop based search tasks
    - Digital assistants
    - Voice-only assistants
  
3. Task extraction algorithms
  - Latent task extraction
    - Clustering based approaches
    - Entity based task extraction
    - Structured learning approach
    - LDA-Hawkes model
  - Subtask Extraction
    - Chinese Restaurant Processes
    - dd-CRPs with deep embeddings
  - Hierarchies of Tasks & Subtasks
    - Agglomerative Clustering
    - Bayesian Rose Trees
    - Bayesian Non-parametric approach
  - Intent Understanding in Personal Assistants
    - Session boundary detection in conversational dialogue
    - Contextual intent tracking in personal assistants
    - User modeling for personal assistants
  - Evaluating Task extraction techniques
    - Gold standard dataset
    - Designing user studies for hierarchical evaluation
    - Alternate evaluation techniques
    - TREC Tasks Tracks
    
4. Task based Evaluation
  - Tasks as a trail: modeling action sequences
  - Multi-view deep sequential models for Tasks SAT
  - Explicit Satisfaction signals
  
  
5. Applications
  - Task based Personalization
  - Task based Recommendations
  - Task tours
  - Predicting task continuation
  - Task completion dialogue systems
  
6. Conclusion
  - Open Research questions
```

### Organizers
1. [Rishabh Mehrotra](http://www.rishabhmehrotra.com), Research Scientist, Spotify, London

2. [Emine Yilmaz](https://sites.google.com/site/emineyilmaz/), Associate Professor, University College London; Faculty Fellow, Alan Turing Institute, London

3. [Ahmed Hassan Awadallah](http://research.microsoft.com/en-us/um/people/hassanam/), Research Manager/Researcher, Microsoft Research


