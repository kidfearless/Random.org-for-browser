# Random.org for browser
 
A simple object oriented wrapper for random.org's random number generator API.

## Usage
To use you can import it as a module or include it in a script tag.
```
let api = new RandomAPI("your-random.org-api-key-here");
let randomInts = await api.GenerateIntegers({min: 0, max: 100, n: 100});
let randomDoubles = await api.GenerateDecimals({n: 1000, decimalPlaces: 14});
```

If you like this repo and want to support me you can always buy me a pizze 😁
<a href="https://www.buymeacoffee.com/kidfearless" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-violet.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>