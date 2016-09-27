  _[View the demo](https://google.com)_

# \<polymer-pokedex\>

👋👋 `polymer-pokedex` is a custom element built with Polymer that displays info about your favourite Pokemon.

Example:
```html
<polymer-pokedex pokemon-name="pikachu"></polymer-pokedex>
```

Also you have the `polymer-pokedex-data` which is an element for requesting pokemon data. It uses `iron-ajax` and `app-localstorage` together, 
so the guys from [PokeApi](https://pokeapi.co) don't get angry.

Example of the data element:
```html
<polymer-pokedex-data pokemon-name="snorlax" data="{{data}}"></polymer-pokedex-data>
```

Enjoy 🎉

### Run the app

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.