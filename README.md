###    [![Build Status](https://travis-ci.com/AtlasOfLivingAustralia/ala-bie.svg?branch=develop)](https://travis-ci.com/AtlasOfLivingAustralia/ala-bie)

[April 2022] The _Atlas of Living Australia_ (ALA) version of the BIE front end has been moved to [ala-bie-hub](https://github.com/AtlasOfLivingAustralia/ala-bie-bub), **which merges [ala-bie](https://github.com/AtlasOfLivingAustralia/ala-bie) and [bie-plugin](https://github.com/AtlasOfLivingAustralia/bie-plugin) into a single code-base**. 
Other users can still use this repository for updating their own BIE.


THE BIE handles general search duties and serves taxon/species pages. 
This Grails app is a light-weight wrapper for [bie-plugin](https://github.com/AtlasOfLivingAustralia/bie-plugin) Grails plugin.
For more details on the architecture see [BIE index](http://github.com/AtlasOfLivingAustralia/bie-index)

Separation of concerns between the organisation specific application (ala-bie) and the plugin is that
this application is responsible for configuration, styling, layout and i18n.
