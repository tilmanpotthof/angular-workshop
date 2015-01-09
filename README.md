# Angular Einführung und Workshop

## Plunker Projekt

* [Plunker Angular 1.3 Template](http://plnkr.co/edit/tpl:rfqcl9AHEoJZEEJxyNn2)


### Beispiel Daten 

[json-generator](http://www.json-generator.com/)

	[
	  '{{repeat(100)}}',
	  {
	    guid: '{{guid()}}',
	    isActive: '{{bool()}}',
	    picture: 'http://lorempixel.com/80/80/cats/',
	    age: '{{integer(20, 40)}}',
	    name: '{{firstName()}} {{surname()}}',
	    gender: '{{gender()}}',
	    company: '{{company().toUpperCase()}}',
	    email: '{{email()}}',
	    phone: '+1 {{phone()}}',
	    address: '{{integer(100, 999)}} {{street()}}, {{city()}}, {{state()}}, {{integer(100, 10000)}}',
	    about: '{{lorem(1, "paragraphs")}}',
	    registered: '{{date(new Date(2014, 0, 1), new Date(), "YYYY-MM-ddThh:mm:ss Z")}}',
	    tags: [
	      '{{repeat(integer(1,5))}}',
	      '{{lorem(1, "words")}}'
	    ],
	    skills: [
	      '{{repeat(integer(1,5))}}',
	      '{{random("c++","java","javascript","perl","php","ruby","scala")}}'
	    ],
	    contacts: [
	      '{{repeat(3)}}',
	      {
	        name: '{{firstName()}} {{surname()}}'
	      }
	    ]
	  }
	]

### Fertiges Beispiel-Projekt

* [Plunker Beispiel: Benutzerliste mit Filter](http://plnkr.co/edit/XU786GR3ZaIV2BFeLXRu?p=preview)

## Links

* [API Reference](https://docs.angularjs.org/api)
* [Seed Projekt inlk. Tests](https://github.com/angular/angular-seed)
* [Angular Pagination](tilmanpotthof.github.io/angular-st-pagination)
* 