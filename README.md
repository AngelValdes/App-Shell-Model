# The "App Shell Model"

Architecting an app "shell" with the minimal HTML, CSS and JavaScript required to power the user interface and when cached offline can ensure instant, reliably good performance and high scalability to users on repeat visits.

The app shell will load the distinct part of the application based on user preference and user demand using lazy loading techniques. It is  responsible for communicating with the different application sections/pages (extentions) and areas (blades) for notifications and styling and building navigational menus.

## Rererence
- This [repository](https://github.com/azure/portaldocs) contains documents for creating extension in Azure Portal.
- Google [App Shell Model](https://developers.google.com/web/fundamentals/architecture/app-shell) theory and documentation
- Two Way [Page to IFrame](https://gist.github.com/pbojinov/8965299) communication example.
- JavaScript [Service Worker](http://mdn.github.io/performance-scenarios/js-worker/index.html) example
- Microsoft Ignite 2018 Portal video session on [high scalable web apps architecture](https://www.youtube.com/watch?v=4YOjlIioapw&t=600s)
- Channel 9 video - [Azure Portal - The Largest SPA in the World](https://channel9.msdn.com/Events/Visual-Studio/Visual-Studio-Live-Redmond-2016/T15)
