# hubot-facebook-insights

A hubot script for some facebook insights

See [`src/facebook-insights.js`](src/facebook-insights.js) for full documentation.

## Installation

In hubot project repo, run:

`npm install hubot-facebook-insights --save`

Then add **hubot-facebook-insights** to your `external-scripts.json`:

```json
[
  "hubot-facebook-insights"
]
```

**Run `fb help` to list the avaliable methods.**

## Sample Interaction

```
user1>> fb fans "Page Name or FB ID"
hubot>> 59367 fans
```

```
user1>> fb checkins "Page Name or FB ID"
hubot>> 28631 checkins
```

```
user1>> fb talking about "Page Name or FB ID"
hubot>> 5612 talking about
```

```
user1>> fb posts "Page Name or FB ID" {limit}
hubot>> 2016-05-06T09:18:19+0000
This is a post example.
```
