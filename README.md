<h1 align="center"> Hi 👋, I'm Karthik M A M </h1>

<p align="center">A polyglot full-stack software engineer, who loves building complex and large scale systems.</p>

<section>
  <h2> Work Experience </h2>
  <section>
    <h3> <a href="https://amazon.com">Amazon.com</a> </h3>
    <ul>
      <li>
        <p>
          <b>Software Development Engineer II - Alexa Social</b>
          &nbsp;
          (Jun 2020 - Present)
        <ul>
          <li> Lead engineer for "Smart Contacts Suggestion", a feature that teaches Alexa what contacts are important to a customer and will recommend such contacts to customers say during calling/messaging etc. Alexa will initially build a suggestion model for the customer based on the raw contact information like last name, relationship etc. As the customer starts interacting with their contacts, new signals like calling/messsaging will build upon the existing model and refine the predictions on what contact is important to the customer. This is one of the key projects within Alexa Social in 2021 and I was chosen to lead, design and implement this system. Potential future use cases include recommending products, music etc. based on the people the customer has a strong connection with.</li>
          <li> As a part of the above feature, I also implemented an intelligent backfill system. It intelligently listens to event streams within Alexa Social and predicts when the customer will require a certain feature for the first time. Based on that and heuristics model for that particular feature, it will backfill/create data migrations just before the customer actually requests that data. This saved scanning billions of contacts from inactive customers, saving approx. 10-20K USD in upfront costs when launching a new feature.</li>
          <li> Led the implementation and adoption of a new UI framework within communications and social org of Alexa in the Alexa mobile app. This was a part of a wider initiative within the Alexa app, to improve consistency, reusability and accessibility of the UX across the Alexa app. As a part of this, I also enabled theming support on the screens owned by our org.</li>
          <li> Took up ownership of a core service within my team and improved it for reliability and scalability during Q4 peak christmas traffic of 2020. Peak traffic for each API of this service would be in the order or 25K calls per second during this period. Some of the enhancements and optimisations include metrics based intelligent downstream traffic predictor, service level caching, dynamic throttling and circuit breaking. </li>
          <li> Implemented GDPR V2 solutions for Alexa Social Contacts. It addressed multiple limitations associated with previous systems like race conditions in data deletion flows amongst dependencies, profile based data deletion etc. </li>
        </ul>
        </p>
      </li>
  </section>

  <section>
    <h3> <a href="https://pro.com">Pro.com</a> </h3>
    <ul>
      <li>
        <p>
          <b>Full-Stack Software Engineer</b>
          &nbsp;
          (Mar 2019 - Jun 2020)
        </p>
        <ul>
          <li>Built payments system using ACH, handling millions of dollars in payment every month. Also, built the payment terms and invoice management systems.</li>
          <li>Built a suite of tools and services that manage the day-to-day activities of field agents in an intelligent way. This particular tool allowed project management activities to be templatized and allowed automatic creation and assignments of such actions to potential owners with manual overrides.</li>
          <li>Built a suite of tools that manage sub-contractor onboarding and management.</li>
          <li>Built parts of the bidding systems that enabled project managers to send out bid invites to subcontractors and enabled the subcontractors to price and accept/reject such bids.</li>
        </ul>
      </li>
  </section>

  <section>
    <h3> <a href="https://www.qubecinema.com/">Qube Cinema Technologies</a> </h3>
    <ul>
      <li>
        <p>
          <b>Associate Software Development Engineer</b>
          &nbsp;
          (May 2017 - Feb 2019)
        </p>
        <ul>
          <li>Built a suite of tools and services that manage metadata about movies, theatres, actors, production houses in the film industry.</li>
          <li>Re-architected a platform called Moviebuff, to progressively move away from a monolith architecture to a mix of micro-service and server-less architecture. Built high throughput and scalable APIs as a part of this migration that are now consumed by top companies like Spotify, Justickets, SPI Cinemas etc.</li>
          <li>Built systems that represent multiple versions (dubs, multilinguals) of the same movie as a tree, which enables complex metadata to flow down the tree with intelligent downstream patching, conflict resolution and approval flows.</li>
          <li>Built de-duplication systems that uses configurable heuristics to identify potential movie, actors, production houses, theatre duplicates and allows for intelligent merging of such duplicates with diff review, conflict resolution and approval flows.</li>
          <li>Built performant consumer web UI that utilised a multitude of web technologies like service workers, server side rendering, progressive web apps etc. to deliver fluid navigations, standalone offline experience etc. (Note: This has been de-prioritised and further development was postponed).</li>
          <li>Built configurable forms engine which enables developers to create beautiful and responsive web forms for complex data entry jobs using only a simple JSON object in a matter of a few minutes (structure similar to JSON schema). Some of the features of the engine include complex validations, data fetching for selects, automatic data flow management inside complex nested forms etc.</li>
          <li>Integrated the Moviebuff platform with EIDR <a href="https://eidr.org/">(https://eidr.org/)</a>.</li>
          <li>Built tools that manage CPLs (Composition Playlist) and their related movies.</li>
          <li>Built scalable scrapers that scrape ticketing information from different websites like BookMyShow, Justickets, SPI Cinemas etc. with an intelligent mapping system to map the scraped shows to theatres, movies, language, date and time etc.</li>
        </ul>
      </li>
      <li>
        <p>
          <b>Software Engineering Intern</b>
          &nbsp;
          (Jan 2017 – Apr 2017)
        </p>
        <ul>
          <li>Worked closely with the senior architects understanding the architecture of the company and coming up with solutions and proposals to optimise them.</li>
          <li>Worked on learning different technologies like Ruby on Rails, GoLang, AWS, React, Angular, Postgres, Redis</li>
          <li>Built prototypes for various technology demonstrations that later were adopted into the production systems after I joined full-time.</li>
        </ul>
      </li>
    </ul>
  </section>
</section>

<section>
  <h2>Education</h2>
  <ul>
    <li>BE Computer Science & Engineering, SSN CE, Anna University, Chennai • 2013-2017 • <b>CGPA: 7.82/10</b></li>
    <li>HSC (+2), Bharathi Vidya Bhavan, Erode • 2011-2013 • <b>Total: 1151/1200</b></li>
    <li>SSC (10th), Amala Matric HSS, Gobichettipalayam, Erode • 1999-2011 • <b>Total: 475/500</b></li>
  </ul>
</section>

<section>
  <h2> Awards & Recognition </h2>
  <ul>
    <li>
      <p>
        <b>Best employee award at <a href="https://pro.com">Pro.com</a></b>
        &nbsp;
        (Jan 2020)
      </p>
      <i>
        This was awarded to me for displaying excellent project ownership and technical skills.
        I took complete ownership of a project that aimed at automating the entire operations workflow at the company.
        I defined the requirements for this project by collaborating with the product team directly, built the entire feature end-to-end, delivered the project on time in such a way that future requirements were easy to add, built metrics around this project and iterated based on them.
        I got a $100 gift card as a part of this award.
      </i>
    </li>
    <li>
      <p>
        <b>Winner of the hackathon conducted by Noon Academy and HasGeek at JSFoo</b>
        &nbsp;
        <a href="https://www.linkedin.com/feed/update/urn:li:activity:6461916055148302336/">(Press)</a>
        &nbsp;
        (Oct 2018)
      </p>
      <i>JSFoo is the top annual JavaScript conference in India. I participated in the hackathon/challenge conducted during this conference and won a Kindle by placing first among hundreds of top JS professionals from across the country</i>
    </li>
    <li>
      <p>
        <b>8 Best Free Open Source Download Manager Software For Windows</b>
        &nbsp;
        <a href="https://listoffreeware.com/free-open-source-download-manager-software-windows/">(Press)</a>
        &nbsp;
        <a href="https://github.com/KarthikMAM/Download-Manager">(Project Link)</a></b>
        &nbsp;
        (Dec 2016)
      </p>
      <i>I built a download manager for windows while I was still doing my undergrad studies and it got featured in this popular blog as one of the best open-source download manager for windows.</i>
    <li>
      <p>
        <b>Best Project Award, ExpertsHub</b>
        &nbsp;
        (Jan 2016)
      </p>
      <i>Created a prototype for an automated parking reservation system.</i>
    </li>
    <li>
      <p>
        <b>Winner Paper Presentation, National Conference on IoT and Data Analytics, SSN</b>
        &nbsp;
        (Mar 2016)
      </p>
      <i>Presented my findings on IoT based solutions for efficient parking reservation system. Won 5000 INR as a part of this by placing first.</i>
    </li>
  </ul>
</section>

<section>
  <h2> Skills & Technologies </h2>
  <ul>
    <li> Full stack development (FrontEnd, BackEnd, Mobile, Infra)
    <li> Platform and language agnostic development (Java, Go, Ruby, TypeScript, Python, React, ReactNative, C#, AWS, Terraform, SQL, NoSQL etc. to name a few)
    <li> Design and implementation of large scale distributed systems
  </ul>
</section>

<br>
<br>

<br>
<br>
