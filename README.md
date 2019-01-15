Here I, and others from the *Open App Ecosystem*, have collected some information related to **ActivityPub**:  

* The [Recommendation](https://www.w3.org/TR/activitypub/)  
* W3C Launches Push for [Social Web Application Interoperability](https://www.w3.org/blog/news/archives/3958)  
* The [Social Web Working Group](https://www.w3.org/wiki/Socialwg)(OVERVIEW) pulished in the period of June 2014 to December 2017 7 Recommendations and some notes  
* The [Charter](https://www.w3.org/2013/socialweb/social-wg-charter) of the Social Web Working Group  
* [Current status](https://www.w3.org/standards/techs/socialweb#w3c_all) of the social Web(Like an OVERVIEW of the protocols etc.)  
* The core types like Activity, Actor, Collection etc. are defined in the [ActivityStreams 2.0 core](https://www.w3.org/TR/activitystreams-core/)  
* And the [ActivityStreams 2.0 Vocabulary](https://www.w3.org/TR/activitystreams-vocabulary/) extends the core functionality  
* The ActivityStreams Objects are acutally [JSON Linked Data](https://www.w3.org/TR/json-ld/) Documents  
* For signing the object itself instead of using [HTTP Signatures](https://w3c-dvcg.github.io/ld-signatures/) for Server-to-Server communication  
* [Repositories](https://github.com/cwebber?utf8=%E2%9C%93&tab=repositories&q=json+OR+signatures&type=&language=) related to jsonld and ldsignatures  
* [Other repositories](https://www.diigo.com/profile/oceatoon/?query=%23json-ld) and information related to jsonld  
* A little OVERVIEW of what exactly is defined in the [ActivityStreams Namespace](https://www.w3.org/ns/activitystreams)  
* [Security Context](https://web-payments.org/vocabs/security) for adding a public key pem etc.  
* [Outbox Collection](https://octodon.social/users/cwebber/outbox?page=true) of cwebber  
* If you send a HTTP GET request to https://octodon.social/users/cwebber with a ACCEPT Header of "application/activity+json" then you can see the Actor Object of cwebber  
* [Blog Post](https://schub.io/blog/2018/02/01/activitypub-one-protocol-to-rule-them-all.html) from Dennis Schubert (diaspora*); also about the topic why they, till now, not want to implement ActivityPub  

###Regarding to the implementation of ActivityPub
* https://blog.joinmastodon.org/2018/06/why-activitypub-is-the-future/  
* https://blog.joinmastodon.org/2018/06/how-to-implement-a-basic-activitypub-server/  
* A [NodeJS minimal ActivityPub federated Server](https://github.com/dariusk/express-activitypub)...  
* .. and a [blog post](https://hacks.mozilla.org/2018/11/decentralizing-social-interactions-with-activitypub/) from the author of the above minimal server  
* [Link collection](htthttps://github.com/w3c/activitypubps://github.com/w3c/activitypub)  
* A go implementation [Tutorial](https://go-fed.org/tutorial)  
* Also a link to the [Federative protocol implementations](https://github.com/go-fed/https://github.com/go-fed/) in golang github organization    
* An WIP [generic federated server implementation](http://commonspub.org/) of the ActivityPub Standard in elixier  

###Some resources related to Webfinger (Discovery of "Profiles")
* insight in the [discovery mechanism](https://diaspora.github.io/diaspora_federation/discovery/webfinger.html) of diaspora federation protocol  
* [Webfinger online client](http://silverbucket.github.io/webfinger.js/demo/) (eg. try cwebber@octodon.social)  
* [Webfinger npm client](https://www.npmjs.com/package/webfinger.js)  
* The [.well-known directory](https://serverfault.com/questions/795467/for-what-is-the-well-known-folder) is a location for site-wide meta data  
* https://www.iana.org/assignments/well-known-uris/well-known-uris.xhtml

###Different Ontologies/Vocabularies
* The fundamental difference between an ontology and a conventional representational vocabulary is the level of abstraction and relationships among concept. (https://surface.syr.edu/istpub/38/ page 3)  
* When I understand it right, a vocabulary has less semantic relations than an ontology.  
* [Wikipedia Ontology definition](https://en.wikipedia.org/wiki/Ontology_(information_science))  
* [W3C definition of a vocabulary](https://www.w3.org/standards/semanticweb/ontology)  
* The W3C [Linked Data Platform](https://www.w3.org/ns/ldp) (LDP) Vocabulary  
* With https://schema.org/ the AS2 Vocabulary can be extended  
* A [ontology/vocabulary](https://github.com/pixelhumain/buildingCommons) developed by the Communecter Community  
* A [ontology/vocabulary](https://valueflows.gitbooks.io/valueflows/content/) for the distributed economic networks of the next economy  

###Information related to the Fediverse
* An high [OVERVIEW of the Fediverse](https://fediverse.party/en/fediverse/), used protocols, networks and used programming languages  
* Another [OVERVIEW of the Fediverse](https://ethercalc.org/fediverse-stacks) in table form, with "What it's for", "Alternative to", "Front-end/Back-end stack" and links to the code  
* [List of network nodes](https://the-federation.info/) in the Fediverse  
* [Fediverse Report 2018](https://fediverse.network/reports/2018)  

###Visualizations of the Fediverse  
* https://fediverse.space/
* https://kumu.io/wakest/fediverse

###Other related Information  
* Description, Characteristics and Examples of the [Open App Ecosystem](http://wiki.p2pfoundation.net/Open_App_Ecosystem)  
* [Dokieli](https://dokie.li/) is a clientside editor for decentralised article publishing, annotations and social interactions  
* [Dokieli Github Repo](https://github.com/linkeddata/dokieli)
* [Nextcloud](https://github.com/nextcloud/social), a safe home for all your data, becomes part of the Fediverse  
* [Federated WordPress blogging](https://github.com/pterotype-project/pterotype) via ActivityPub  
* [Bridge](https://github.com/snarfed/bridgy-fed) between IndiWeb and federated social Networks(Fediverse)  
* [Differences between IRI URI URL URN](http://fusion.cs.uni-jena.de/fusion/blog/2016/11/18/iri-uri-url-urn-and-their-differences/) (GERMAN)  
* End-to-End Encrypted & Decentralized [Messaging Service](https://github.com/fedimos) for the Fediverse  

Another interesting ressource is the **Web Report** from Tim Berners-Lee
