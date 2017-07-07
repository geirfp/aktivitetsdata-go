# Common Structures 
Common Structures gives guidance on the way statements following the profile may be structured, including the use of extensions.

* [Actor](#actor)
* [Verb](#verb)
* [Object](#object)
* [Result](#result)
* [Context](#context)
* [Extensions](#extensions)
* [Example Statements](#examples)

<a name="actor"></a>
## Actor

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
Verbs in the profile are listed on the [vocabulary](vocabulary.md) page. 

``` Javascript
"verb": {
	"id": "http://adlnet.gov/expapi/verbs/launched",
	"display": {
		"en": "launched",
		"no": "begynte"
	}
}
```

<a name="object"></a>
## Object

<a name="activity"></a>
### Activity
Activity Types in the profile are listed on the [vocabulary](vocabulary.md) page. More information on Activity [extensions](#activityExtensions).

``` Javascript
"object": {
	"objectType": "Activity",
	"id": "https://www.nrk.no/skole/?mediaId=19864",
	"definition": {
		"name": "Kosmos",
		"type": "http://adlnet.gov/expapi/activities/media",
		"extensions": {
			"http://schema.org/educationalAlignment": {
				"http://schema.org/educationalFramework": "Kunnskapsløftet",
				"http://schema.org/targetDescription": "beskrive universet og ulike teorier for hvordan det har utviklet seg",
				"http://schema.org/targetName": "K15097",
				"http://schema.org/targetUrl": "http://data.udir.no/kl06/K15097"
			},
			"http://schema.org/publisher": {
				"http://schema.org/identifier": "https://api.feide.no/2/sp/96213",
				"http://schema.org/name": "NRK Skole"
			}
		}
	}
}
```

#### Metadata
Hosted metadata...

<a name="result"></a>
## Result
...

<a name="context"></a>
## Context
More information on Context [extensions](#contextExtensions).

``` Javascript
"context": {
	"extensions": {
		"http://schema.org/affiliation": [
		{
        		"http://schema.org/identifier": "http://data.brreg.no/enhetsregisteret/enhet/976820037",
        		"http://schema.org/legalName": "Oslo kommune Utdanningsetaten"
        	}, {
        		"http://schema.org/identifier": "http://data.brreg.no/enhetsregisteret/underenhet/974589710",
			"http://schema.org/legalName": "Bryn skole"
		}]
	}
}

```

<a name="extensions"></a>
## Extensions

<a name="activityExtensions"></a>
### Activity

#### Educational alignment
An alignment to an established educational framework. Makes use of the [educationalAlignment](http://schema.org/educationalAlignment) *property* and the [AlignmentObject](http://schema.org/AlignmentObject) *type* from [LRMI](http://lrmi.dublincore.net) and [Schema.org](http://schema.org). 

##### Grep
An alignment to [Grep](https://www.udir.no/om-udir/data/kl06-grep/). More information on [GrepWiki](http://grepwiki.udir.no/).
 
###### Compentence aim
``` Javascript
"extensions": {
	"http://schema.org/educationalAlignment": {
		"http://schema.org/educationalFramework": "Kunnskapsløftet",
		"http://schema.org/targetDescription": "beskrive universet og ulike teorier for hvordan det har utviklet seg",
		"http://schema.org/targetName": "K15097",
		"http://schema.org/targetUrl": "http://data.udir.no/kl06/K15097"
	}
}
```

#### Publisher
The publisher of an [Activity](#activity) (learning resource). More information on [Feide API](https://docs.feide.no/api/).

```Javascript
"extensions": {
	"http://schema.org/publisher": {
		"http://schema.org/identifier": "https://api.feide.no/2/sp/96213",
		"http://schema.org/name": "NRK Skole"
	}
}
```

<a name="contextExtensions"></a>
### Context

#### Affiliation

An organization that the [Actor](#actor) is affiliated with. More information on [Feide API](https://docs.feide.no/api/) and [Register for Legal Entities API](http://data.brreg.no/oppslag/enhetsregisteret/).

##### School owner and school

``` Javascript
"extensions": {
	"http://schema.org/affiliation": [
		{
			"http://schema.org/identifier": "http://data.brreg.no/enhetsregisteret/enhet/976820037",
			"http://schema.org/legalName": "Oslo kommune Utdanningsetaten"
		}, {
			"http://schema.org/identifier": "http://data.brreg.no/enhetsregisteret/underenhet/974589710",
			"http://schema.org/legalName": "Bryn skole"
		}
	]
}
```

``` Javascript
"extensions": {
	"http://schema.org/affiliation": [
		{
			"http://schema.org/identifier": "https://api.feide.no/2/org/86",
			"http://schema.org/legalName": "Oslo kommune Utdanningsetaten"
		}, {
			"http://schema.org/identifier": "http://data.brreg.no/enhetsregisteret/underenhet/974589710",
			"http://schema.org/legalName": "Bryn skole"
		}
	]
}
```

<a name="examples"></a>
## Example Statements

### Example 1: ...
``` Javascript
{	
	"actor": {
		"objectType": "Agent",
		"account": {
			"homepage": "https://auth.dataporten.no",
			"name": "76a7a061-3c55-430d-8ee0-6f82ec42501f"
		}
	},
	"verb": {
		"id": "http://adlnet.gov/expapi/verbs/launched",
		"display": {
			"en": "launched",
			"no": "begynte"
		}
	},
	"object": {
		"objectType": "Activity",
		"id": "https://www.nrk.no/skole/?mediaId=19864",
		"definition": {
			"name": "Kosmos",
			"type": "http://adlnet.gov/expapi/activities/media",
			"extensions": {
				"http://schema.org/educationalAlignment": {
					"http://schema.org/educationalFramework": "Kunnskapsløftet",
					"http://schema.org/targetDescription": "beskrive universet og ulike teorier for hvordan det har utviklet seg",
					"http://schema.org/targetName": "K15097",
					"http://schema.org/targetUrl": "http://data.udir.no/kl06/K15097"
				},
				"http://schema.org/publisher": {
					"http://schema.org/identifier": "https://api.feide.no/2/sp/96213",
					"http://schema.org/name": "NRK Skole"
				}
			}
		}
	},
	"context": {
		"extensions": {
			"http://schema.org/affiliation": [
				{
					"http://schema.org/identifier": "http://data.brreg.no/enhetsregisteret/enhet/976820037",
					"http://schema.org/legalName": "Oslo kommune Utdanningsetaten"
				}, {
					"http://schema.org/identifier": "http://data.brreg.no/enhetsregisteret/underenhet/974589710",
					"http://schema.org/legalName": "Bryn skole"
				}
			]
		}
	}
}	
```
