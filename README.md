# WSearch

Just a little frontend searching engine. 

In my example it can give you some information about a few Harry Potter characters but you can modify the code for your purposes.


## Installation

Clone the Repository with this command:

```bash
git clone https://github.com/Ortrx/WSearch.git
```

or simply download the .zip file.
## Demo

I hosted the site here: https://wsearchdemo.netlify.app

## Usage/Examples

You can modify the results or add your own characters by adding their names in the harryPotterCharacters const and adding some information about them in the getCharacterInfo(name) function. (Both in script part of index.html file)

It could look like this:

```javascript

const harryPotterCharacters = [
			"Harry Potter",
		];


function getCharacterInfo(name) {
    case "Harry Potter":
      			return {
        			name: "Harry Potter",
        			description: "Harry Potter is the main character.",
        			stats: {
          				age: 17,
          				house: "Gryffindor",
          				wand: "11\" Holly, Phoenix feather core",
          				patronus: "Stag",
        			},
      			};
}
```
