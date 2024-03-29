## Summary
There are nine principles to building and sustaining a modern value driven engineering organization. The journey is not complete until all of the following principles are part of the engineering practice.

A practical definition of Platform Enginering would include the practices and philosophies of DevOps, SRE and SecOps. While DevOps has been misunderstood over the years, I believe that the fundamental aspect of this practice is to make the platform easy to develop against. A modern public cloud Platform Engineering landscape would look something like this;

![healthy pe framework](shot.png)

*The tools aren't as important as what the tools are used for*.


### 1. Leadership
  Leaders align and execute these principals. Assure time and material is accounted for and provide a 'North Star' for their teams. Inspire and reward accomplishments of engineers.

### 2. Collaborative culture
  The organization encourages cross-functional collaboration, shared responsibilities and works to reduce blockers between organizational. This includes establishing or reinforcing business stakeholder relationships.

### 3. Design for flexibility and resilance  
  Products are architect'ed to support service-oriented, modular, independent packaging, testing and releases.

### 4. Continuous integration
  Changes to software code and artifacts are frequently merged, built, tested and packaged into executable artifacts.

### 5. Continuous testing
  Automated software tests verifying the each stage of the release completed w/o error.
  * pre-flight checks
  * integration
  * regression
  * performance
  * release acceptance tests

### 6. Elastic infrastructure
  Infrastructure as a-Service (IaaS) is integrated into your tool chain. Similar to software merges,
  elasticity should have tests and validations

### 7. Continuous monitoring
  Applications, pipeline tools and infrastructure instrumented with metrics. Infrastructure should a
  service level framework (SLO, SLI, and SLA).

### 8. Continuous security (DevSecOps)
  Security practices, processes and technologies for applications, databases, pipelines and infrastructures are integrated into the engineering culture and tool chain. This to should adhere to a service level framework. $to assure security.

### 9. Continuous delivery
  Release artifacts are validated, prepared for deployment to production and may be automatically deployed to production once acceptable deployment measures are achieved.
  ____________________________________

## But wait, there's more
  As the DevOps framework is being implemented, continue to define following principles. As the organization evolves these principles will be important to the functions of the practice.

  **Version management systems** – The Platform Engineering incorporate the DevOps value stream of keeping track of source code
   * configuration data
   * executable images
   * artifact repositories
   * configuration management systems

  **IaaS** – Infrastructure is built ephemerally. Engineering practices such as orchestration is
  applied to bare metal, hybrid cloud, cloud  and multicloud services. 

  Platform Engineering pipeline practices (CI/CD), include two additional categories that use DevOps principles.

  **Application release automation** – The CI/CD pipeline requires process orchestration and data
  analysis working at a level above the CI/CD pipeline itself.

  **Value stream management** – No software or data services, are manually deployed. This should be
  a well defined architecture and process.

## Management and Administrative Practices
  DevOps Service Management practices include four CI/CD sub practices practices:

  **Service catalogs** – A collections of software stacks, tools and pre-configured release
  pipelines are made available via a continuous integration tool. 

  **Disaster prevention and recovery** – Proactive disaster monitoring/alerting coupled with
  high-availability configurations and disaster mitigation practices. This should reduce the blast
  radious and minimize RTO. 

  **Site reliability engineering (SRE)** – Practices which include
  * [service level objectives](https://github.com/winslowb/winslowb/blob/master/servicelevle.md) (SLOs)
  * error budgets 
  * monitoring
  * paring policies
  * blameless post-mortems
  * integrate security, resiliency, efficiency and operations practices into source code

  **Governance** – Cross functional engineers enforce "As Code" policies through service catalogs, management dashboards and error budget policies.

### Project Practices
  Agile project practices include four categories that guide enterprise adoption and evolution of DevOps, as follows:

  - **Adoption** – Enterprise-wide DevOps adoption strategies that engineer and build DevOps
  capabilities in logical phases. Start small with a set of representative applications that is a
  model for other applications.

  - **Return on investment** (ROI) – DevOps investments must be considered as important as other
  projects. An ROI model that measures cost savings.

  - **Continuous improvement** – DevOps is never a finished endeavor. Continuous evaluation of your
  implementation will serve as the platform to improve.   

### The Human Element
  Qualities of a Platform Engineer
    * curious
    * inventive
    * humble (and declarative) - you can be both :)
