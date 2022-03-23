# Stack Technique et architecture

D’un point de vue technique, Pix est conçue comme une "plateforme" (cf. [ADR-0002](https://github.com/1024pix/pix/blob/dev/docs/adr/0002-style-d-architecture.md)).

La grande majorité du code est en JavaScript (cf. [ADR-0003](https://github.com/1024pix/pix/blob/dev/docs/adr/0003-langages-frameworks-et-technologies.md)).

À ce titre elle comprend :

* une **API Node.js / Hapi.js** au format [JSON:API](https://jsonapi.org/) 
* plusieurs applications front-end **Ember.js**
* quelques applications front-end **Vue.js**
* une base de données utilisateurs **PostgreSQL**
* une base de données référentielles (contenus pédagogiques) [Airtable](https://airtable.com)
* un cache de données référentielles **Redis**
* un CMS headless ([prismic.io](https://prismic.io/)) pour le contenu éditorial / institutionnel
* le tout déployé, hébergé et administré sur le PaaS français [Scalingo](http://scalingo.com)
* et soigneusement orchestré par [GitHub](https://github.com/1024pix/pix) / [CircleCI](https://circleci.com)
* [Metabase](https://www.metabase.com/) pour nos dashboards data
* [Datadog](https://www.datadoghq.com/) pour le monitoring et le suivi de nos logs 
* [Matomo](https://fr.matomo.org/) pour nos traces utilisateurs
