## Working Proposal for Web Wednesday Workshop

**Sessions led by:**
 * Shelby Swtizer
 * Mike Amundsen
 
What are Web APIs and how do you design and build them? And what do all these acronyms mean: REST, CRUD, Hypermedia, GraphQL, AOI, Swagger, RAML, Blueprint, OAuth?  Join the RESTFest team for a wide-ranging and in-depth workshop that touches on the basics of Web APIs, what makes them work, and how you can navigate the alphabet soup of standards and practices that make up this essential part of the World Wide Web.

- **MORNING** (9-Noon)
  - [Morning Slides (PDF)]https://github.com/RESTFest/2018-workshop-day/blob/master/2018-09-restfest.pdf
  - *REST: A starting point* (40min)
    - System Properties
    - Architecture Constraints
    - When REST and WWW disagree
    - _Exercise: REST or WWW?_
  - *CRUD for the masses* (40min)
    - CRUD’s roots (databases)
    - The advantage of CRUD
    - The downsides of CRUD
    - _Exercise: Desing the ToDo CRUD API_
    - [Sample Solution](https://github.com/apiacademy/tasks-crud)
  - **BREAK** (20min)
  - *GraphQL for the new kids* (40min)
    - Query-Style APIs Pros & Cons
    - Client View
    - Server View
    - _Exercise: Design the ToDo GraphQL API_
    - [Sample Solution](https://github.com/mamund/graphql-todo)
  - *Hypermedia for the dedicated* (40min)
    - What/Why Hypermedia?
    - Link-centric formats (Atom, HAL, etc.)
    - Form-centric formats (Siren, Cj, etc.)
    - _Exercise: Design the ToDo Hypermedia_
    - [Sample Solution](https://github.com/apiacademy/tasks-hypermedia)
- **LUNCH** (Noon to 1PM)
- **AFTERNOON** (1PM-4PM)
  - Starting with an API definition, we will identify and discuss common REST API design practices and patterns. Topics covered:
    - API definition languages such as Open API Spec (Swagger), RAML, API Blueprint, ALPS, etc
    - Resources & Representation
    - Links
    - Request/Response Loop
  - Next, we will build a client against the API definition. This will be hands-on, but will also include a discussion at the end on what we learned and feedback we would give the API designer. Topics covered:
    - URLs, Methods, and Actions
    - Formats and Representations
    - Following Links
    - Usability
  - Finally, we will update the API spec based on changes we identified that we wanted to make in the previous section, and then build a server to that spec. This will be followed up by a discussion on the pros and cons of the changes made server-side, and how participants would take this further. Topics covered:
    - Versioning
    - Security
    - Testing

<!--
- **AFTERNOON** (1PM-4PM)
  - *Anatomy of a Web API Server* (40min)
    - The Request/Response Loop
    - Data & Objects
    - Resources & Representation
    - _Exercise: Map out the ToDo Server_
  - *Anatomy of a Web API Client* (40min)
    - The Request/Response Loop
    - URLs, Methods, and Actions
    - Formats and Representations
    - _Exercise: Map out the ToDo ClientApp_
  - *BREAK* (20min)
  - *API Definition Languages* (40min)
    - WSDL/WADL
    - Swagger/RAML/Apiary
    - ALPS/DCAP
    - _Exercise: Describe the ToDo API_
  - *The Hard Stuff* (40min)
    - Documentation
    - Versioning
    - Discovery
    - Security
    - _Exericise: Supporting the ToDo API_
- **Alternative Afternoon** (1PM-4PM)
  - Starting with an API definition, we will identify and discuss common REST API design practices and patterns. Topics covered:
    - API definition languages such as Open API Spec (Swagger), RAML, API Blueprint, ALPS, etc
    - Resources & Representation
    - Links
    - Request/Response Loop
  - Next, we will build a client against the API definition. This will be hands-on, but will also include a discussion at the end on what we learned and feedback we would give the API designer. Topics covered:
    - URLs, Methods, and Actions
    - Formats and Representations
    - Following Links
    - Usability
  - Finally, we will update the API spec based on changes we identified that we wanted to make in the previous section, and then build a server to that spec. This will be followed up by a discussion on the pros and cons of the changes made server-side, and how participants would take this further. Topics covered:
    - Versioning
    - Security
    - Testing
Things not covered above that would be interesting:
- Event-driven/Reactive approaches
- SOAP is left out (that’s ok, i think?)
- others?
-->
