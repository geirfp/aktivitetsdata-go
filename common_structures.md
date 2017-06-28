# Common Structures 
Common Structures gives guidance on the way statements following the profile may be structured, including the use of extensions.

* [Actor](#actor)
* [Verb](#verb)
* [Object](#object)
* [Result](#result)
* [Context](#context)
* [Extensions](#extensions)

<a name="actor"></a>
## Actor
The profile supports both Agent and Group as objectType of Actor.

### Agent 

##### Dataporten
A user account on Dataporten. More information on Dataporten [UserIDs](https://docs.dataporten.no/docs/userid/).

``` Javascript
"actor": {
	"objectType": "Agent",
	"account": {
		"homepage": "https://auth.dataporten.no",
		"name": "76a7a061-3c55-430d-8ee0-6f82ec42501f"
	}
}
```

### Group

##### Dataporten
An identified group on Dataporten. More information on Dataporten [Groups](https://docs.dataporten.no/docs/groups/).

``` Javascript
"actor": {
	"objectType": "Group",
	"account": {
		"homepage": "https://groups-api.dataporten.no",
		"name": "fc:adhoc:8878ae43-965a-412a-87b5-38c398a76569"
	}
}
```

<a name="verb"></a>
## Verb
The verbs permitted in the profile are listed on the [vocabulary](vocabulary.md) page. 

``` Javascript
"verb": {
	"id": "http://adlnet.gov/expapi/verbs/attempted",
	"display": {
		"en": "attempted",
		"no": "forsøkte"
	}
}
```

<a name="object"></a>
## Object
The objectType of Object is restricted to Activity in the profile. The activity types permitted in the profile are listed on the [vocabulary](vocabulary.md) page.

... 

<a name="result"></a>
## Result
...

<a name="context"></a>
## Context
...

<a name="extensions"></a>
## Extensions

### Grep
Alignments to [Grep](http://grepwiki.udir.no/), the national educational framework and curriculum for K-12. Structured as extensions for inclusion in (Object/Context?). The structure draws upon the Grep [Ontology](http://psi.udir.no/ontologi/Kl06/) and facilitates [SPARQL endpoint](http://data.udir.no/kl06/sparql) and JSON retrieval. 
 
##### Compentence aim
``` Javascript
Alt:
"extensions": {
	"http://schema.org/educationalAlignment": {
		...
		"http://schema.org/targetUrl": "http://data.udir.no/kl06/K15095"
	}
}

Alt:
"extensions": {
	"http://psi.udir.no/ontologi/kl06/grep-type": "http://psi.udir.no/ontologi/kl06/kompetansemaal",
	"http://psi.udir.no/ontologi/kl06/uri": "http://psi.udir.no/kl06/K15095",
	"http://psi.udir.no/ontologi/kl06/url-data": "http://data.udir.no/kl06/K15095"
}

Alt:
"extensions": {
	"http://psi.udir.no/ontologi/kl06/url-data": "http://data.udir.no/kl06/K15095"		
}
```
