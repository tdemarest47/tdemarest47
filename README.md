## About Me:

I have a long track record of building production-ready software. 

I started my journey long ago as a C developer on DOS, UNIX and embedded environments, and morphed into a full-stack web
developer along the way.

My work has been shipped inside printers (and their OS drivers), shrinkwrapped into boxed applications sold in software stores,
delivered to browsers over the internet, and run inside corporate data centers to maintain critical data pipelines.

I am most comfortable on the server-side (with a very strong database focus); but can also able to contribute on the client side
to produce clean, concise user experiences.

I have found that any codebase can be improved by adding automated testing and targeted refactoring, and that it will be faster
than switching to the latest / greatest technology trend (which will be replaced by a later/greater trend by the time you release).
Test-driven development really does produce better code, and refining what you already have is almost always cheaper and more
effective than any ground-up re-write.

Reach me at:
 - tdemarest47@gmail.com
 - https://github.com/tdemarest47
 - https://www.linkedin.com/in/timothy-demarest

## My Resume:  [resume.pdf](https://github.com/user-attachments/files/19636922/resume_2025_03.pdf)

---

## web Portfolio
  - Unfortunately, you cannot reach very deeply into my portfolio... as most of my work lives behind paywalls.
  - There are a couple of publicly visible sites I can share, but this only proves that the sites exist.

### Wheels Up: https://wheelsup.com/
  - I worked on the backend server behind this site, which was responsible for:
    - Hydrating static content with live data from internal API.
    - Serving page data to Web and Mobile (both iOS and Android) clients.
    - Managing flight bookings, updates, status alerts etc. for end users.
    - Technology stack was Node.js (TypeScript) atop a custom content delivery system and various internal API.
  - I also performed some maintenance work on the Android client; I am not primarily an Android developer, but I
      was able to stabilize a crash-prone app, and get the flight booking flow working end-to-end.
  - Unfortunately, without a WheelsUp membership, it is impossible to showcase much of my work here...
      I don't really have the budget to fly private!
   
### Electronics for Imaging: https://iq.fiery.com/
  - You can get some sense of how this site works from the "Try a Live Demo" button.
    - This will let you walk through the client-side software, with a selection of demo data.
    - I cannot speak to the current state of this demo, as I left the company in mid-2021.
    - I spent most of my time getting real data into the system, from real devices.
  - I worked on both server and client software for this project.
    - I brought this project from a minimal POC to a production-ready platform.
    - Technology stack is Angular frontend, and nodejs backend using MySQL, elasticsearch, redis, cassandra and rabbitmq for data management tasks.
    - Primarily an IOT data capture application, connected to agents running on Fiery servers worldwide.
  - This grew to be a multi-application cloud
    - Multiple licensing models, each application was different.
    - I managed the app permissions by applications / tenants / users / devices for all API in the cloud.
    - I was responsible for the core API and database schema to support all apps / license models.
  - Other key tasks I was responsible for:
    - Managing the cloud end of websocket connections to live devices (nodejs websocket servers, MySQL).
    - Capturing and storing incoming message traffic from those devices (rabbitMQ, Cassandra).
    - Post-processing the raw data to produce normalized data to feed the web clients (elasticsearch).
  - I refined the client-side charting code to minimize user wait times / maximize code and data re-use.
  
### Canfield Scientific: https://clinicalservices.canfieldsci.com/login.php
  - You can really only reach the login /signup page, access is only granted to Canfield Scientific customers.
  - While at Canfield, I worked on:
    - Client and server for this site (php / apache / SQL Server)
    - Data pipelines to deliver the web view of data / images (webified partial mirror of internal data / images).
    - Data pipelines to deliver images uploaded through the website into internal data warehouse.
    - Data pipelines to deliver images from dedicated imaging hardware systems in the field into internal data warehouse.
    - Various internal study management tools used by in-house staff.

