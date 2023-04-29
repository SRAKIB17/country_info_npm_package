# version 1.0.0

```
npm i country_full_info
```

```javascript
import {country_info, country_info_by_name, country_info_by_capital} from 'country_full_info';

const test1 = country_info
// return a array of country list

// **********************************
const test2 = country_info_by_name({country_name:"Afghanistan"})
 {
        "dial_code": "+93",
        "code": "AF",
        "emoji": "🇦🇫",
        "phLength": 9,
        "country": "Afghanistan",
        "capital": "Kabul",
        "language": {
            "code": "ps",
            "name": "Pashto"
        },
        "currency": {
            "code": "AFN",
            "name": "Afghan afghani",
            "symbol": "؋"
        }
    }

const test3 = country_info_by_name({capital:"Kabul"})
 {
        "dial_code": "+93",
        "code": "AF",
        "emoji": "🇦🇫",
        "phLength": 9,
        "country": "Afghanistan",
        "capital": "Kabul",
        "language": {
            "code": "ps",
            "name": "Pashto"
        },
        "currency": {
            "code": "AFN",
            "name": "Afghan afghani",
            "symbol": "؋"
        }
    }


```
