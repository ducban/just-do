# Just - Just do one thing.

## Emoji Commit

Commit Type             | Emoji
----------------------- | -------------
Initial Commit          | :tada: `:tada:`
Structure               | :art: `:art:`
Documentation           | :memo: `:memo:`
New Idea                | :bulb: `:bulb:`
New Feature             | :sparkles: `:sparkles:`
Bug                     | :bug: `:bug:`
Version Tag             | :bookmark: `:bookmark:`
Performance             | :racehorse: `:racehorse:`
Tooling                 | :wrench: `:wrench:`
Tests                   | :rotating_light: `:rotating_light:`
Deprecation             | :poop: `:poop:`
Work In Progress (WIP)  | :construction: `:construction:`
Upgrading               | :arrow_up: `:arrow_up:`

Example:

> ":tada: Initial Commit"

## Packages

- <a href="#just-type">just-type</a>

## Usage

<a name="just-type"></a>
### just-type

type checking.

```js
import type from 'just-type';

function hello() {
    console.log('hello type');
}

type(); // undefined
type(undefined); // undefined
type(null); // null
type(''); // string
type('hello'); // string
type(0); // number
type(true); // boolean
type({}); // object
type([]); // array
type(hello); // function
type(/\./); // regexp
```
