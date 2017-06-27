# Common Structures 
Common Structures gives guidance on the way statements following the profile may be structured, including the use of extensions.

## Actor
The profile supports both Agent and Group as objectType of Actor.

### Agent 
A user account on Dataporten. More information on [UserIDs](https://docs.dataporten.no/docs/userid/).

```
{ 
	"actor": {
		"account": {
			"homepage": "https://auth.dataporten.no",
			"name": "76a7a061-3c55-430d-8ee0-6f82ec42501f"
		}
	}
	"objectType": "Agent"
}
```

### Group
An identified group on Dataporten. More information on [Groups](https://docs.dataporten.no/docs/groups/).

```
{
	"actor": {
		"account": {
			"homepage": "https://groups-api.dataporten.no",
			"name": "fc:adhoc:8878ae43-965a-412a-87b5-38c398a76569"
		}
	}
	"objectType": "Group"
}
```

## Verb
The verbs permitted in the profile are listed on the [vocabulary](vocabulary.md) page. 

```
{
	"verb": {
		"id": "http://adlnet.gov/expapi/verbs/attempted",
		"display": {
			"en": "attempted",
			"no": "forsøkte"
		}
	}
}
```

## Object
The objectType of Object is restricted to Activity in the profile. The activity types permitted in the profile are listed on the [vocabulary](vocabulary.md) page.

... 

## Context
...
