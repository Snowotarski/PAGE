# PAGE Web Search form code

This is a place to store the code we are using for our Planarian Anatomy Gene Expression Search form. It includes our php, java script, and css files. This code requries a webserver, blazegraph server, and an owlery server. I think I create a separeate repo to house the curations that are used to build the triples that are loaded into the blazegraph jnl file.  

We use the OLS-autocomplete widget. We make modifications to the js so that we can send the autocompete dropdown list selection to a form that queries for the selection in our blazegraph server. The unmodified code can be found at [EBISPOT](https://github.com/EBISPOT/OLS-autocomplete)

We also use a Owlery to expand our searches to include related terms. We use the Owlery docker ( [@github](https://github.com/phenoscape/owlery/tree/master/Docker) [@dockerhub](https://hub.docker.com/r/phenoscape/owlery)). We have our own docker image, owlery-plana that pulls in this docker image as a base ([@github](https://github.com/srobb1/owlery-plana) [@dockerhub](https://hub.docker.com/r/srobb1/owlery-plana) )
