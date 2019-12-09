## Abstract EN
### How to PaaS ?! Migrating a JavaEE Monolith live to different cloud platforms.
### Live Migration Demo of a WebSphere-based Java EE Monolith to Cloud Foundry

The intention of this talk is to show a live step-by-step approach to migrate a monolithic WebSphere application to Cloud Foundry. It starts showing the application running in it’s WebSphere environments and finishes running the migrated app on Cloud Foundry. 

On the migration journey the following steps are shown:
  * Deployment and runtime on WebSphere
  * Analysis of application in terms of required code changes and connected backend services
  * Configuration and bring up of the application on WebSphere Liberty Profile
  * Deployment and runtime on PCF Dev using Community Buildpack for Liberty
  * Migration of backend services to Cloud Platform (Microsoft Azure in this example)
  * Deployment and runtime of application on PCF on Azure
  * Application of strangler pattern to start slicing the monolith into Microservices.

It is based on a talk given at the User track of Cloud Foundry Summit in Basel 2018. It was received very well, got a lot of good feedback and brought up interesting discussions with the attendees. While this talk was very conceptual, this new version is intended to demonstrate the involved steps in a live example and perform the migration within the given time of 30 minutes

## Abstract DE
### PaaSts ?! Live Migration eines JavaEE Monolithen zu verschiedenen Cloud Plattformen.
Mit dieser Session zeigen wir live einen Schritt-für-Schritt Ansatz zur Migration einer monolithischen WebSphere Anwendung zu Cloud Foundry und Kubernetes. Wir beginnen mit der Anwendung laufend in der WebSphere Umgebung und Enden mit der migrierten App auf einer Cloud Platform. 

Unser Migrationsreise zeigt folgende Schritte:
   * Deployment und Laufzeitumgebung WebSphere
   * Analyse der Anwendung hinsichtlich Codeänderungen und Kompatibilität der Backendsysteme
   * Konfiguration und Boot der Anwendung auf WebSphere Liberty Profile
   * Deployment auf PCF Dev / Minikube
   * Migration der Backend Services auf managed Services
   * Deployment auf Cloud Platform
   * Anwendung des Strangler Pattern zur Transformation des Monolithen zu Microservices

Aufbauend auf einem konzeptionellen Vortrag den wir im Jahr 2018 auf mehreren Konferenzen (unter anderem Cloud Foundry Summit, WJAX und OOP) gehalten haben, zeigen wir nun wie die Konzepte umgesetzt werden können.

## Given at
* [Cloud Foundry Summit North America 2019](https://cfna19.sched.com/event/KJCW/live-migration-demo-of-a-websphere-based-java-ee-monolith-to-cloud-foundry-thorsten-jakoby-matthias-haeussler-novatec-consulting)
* [Kubernetes Meetup Hamburg](https://www.meetup.com/de-DE/Hamburg-Kubernetes-Meetup/events/261506259/)
* [Java Forum Stuttgart 2019](https://www.java-forum-stuttgart.de/de/Vortr%E4ge+von+09.50+-+10.35+Uhr.html)
* [Cloud Foundry Meetup Munich 2019](https://www.meetup.com/de-DE/CloudFoundry-Munich/events/262897094/)
* [JCON 2019](https://jcon.one/de/)
* [Basel One 2019](https://baselone.ch/speech/B8291AA7-DAB2-416A-826B-B6FD235D3E5A/Matthias-Haeussler)
* [IT Tage Frankfurt 2019](https://www.ittage.informatik-aktuell.de/programm/2019/live-migration-eines-javaee-monolithen-zu-verschiedenen-cloud-plattformen/) 

