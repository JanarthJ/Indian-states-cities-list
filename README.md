# Indian-states-cities-list
Repo consist of Indian-state array , state wise cities list
##Table of content
* [Intro](#intro)
* [Setup](#setup)
* [Usage](#usage)


## General info
This Package provide a list of Indian-states and state-wise cities.

## Setup
Simply add this package by using
```
$ npm install Indian-states-cities-list

```
## Usage
```
import INDIAN_STATES_AND_UT_ARRAY from "Indian-states-cities-list";

console.log(STATE_WISE_CITIES.AndamanandNicobar);

//output
/*
    [
    { value: 'Nicobar', label: 'Nicobar' },
    {
      value: 'North and Middle Andaman',
      label: 'North and Middle Andaman'
    },
    { value: 'South Andaman', label: 'South Andaman' }
    ]
*/

```

```
import STATES_OBJECT from "Indian-states-cities-list";

console.log(STATES_OBJECT);

//output
/*
    [
    {label: "Andaman and Nicobar Islands",value: "Andaman and Nicobar Islands",name: "AndamanandNicobar"},
    {label: "Andhra Pradesh",value: "Andhra Pradesh",name: "AndhraPradesh"},
    ....,
    {label: "West Bengal",value: "West Bengal",name: "WestBengal"}
    ]
*/

```
