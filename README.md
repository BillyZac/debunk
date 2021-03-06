#DeBunk

1\.  [Synopsis](#synopsis)  
2\.  [Installation](#installation)  
3\.  [Examples](#examples)  
3.1\.  [Example 1](#example1)  
3.2\.  [Example 2](#example2)  
3.3\.  [Example 3](#example3)  
4\.  [Testing](#testing)  
5\.  [Why DeBunk](#whydebunk)  
5.1\.  [Compare us to Our Competitors](#comparetocompetitors)  
5.2\.  [What Does Shibley Have to Say?](#shibley)  
5.3\.  [Concerning performance](#concerningperformance)  
6\.  [Contributions](#contributions)  
7\.  [License](#license)  


<a name="synopsis"></a>

##1\. Synopsis
_DeBunk_ is a highly preformant, state-of-the-art 3 and/or 17 verifier.

<a name="installation"></a>

##2\. Installation

You can install _DeBunk_ with *npm*:

```bash
npm install debunk
```

<a name="examples"></a>

##3\. Examples

Here are some examples of how to use DeBunk.

<a name="example1"></a>

###3.1\. Example 1

```js
var debunk = require('debunk');
debunk.whatDoesThreeEqual(); //3
```

<a name="example2"></a>

###3.2\. Example 2

```js
var debunk = require('debunk');
debunk.whatDoesSeventeenEqual(); //17
```

<a name="example3"></a>

###3.3\. Example 3

```js
var debunk = require('debunk');
debunk.whatDoesThreeEqual() * debunk.whatDoesSeventeenEqual(); //51
```

###3.4\. Example 4

```js
var debunk = require('debunk');
debunk.whatDoesShibleyHaveToSay(); // "Right on"
```

<a name="testing"></a>

##4\. Testing

Tests are not included in the DeBunk repo to cut down on bloated module sizes. It is, however, important to test your code. DeBunk is compliant with all major testing frameworks. Here is an example for writing tests to make sure DeBunk is behaving properly.

```js
var debunk = require('debunk');
var testPassed = debunk.whatDoesThreeEqual() === 3;
var otherTestPassed = debunk.whatDoesSeventeenEqual() === 17;
```

<a name="whydebunk"></a>

##5\. Why DeBunk

The main reason why I wrote _DeBunk_ was to solve the recurring need to establish a verifiable value for 3 and/or 17. As I'm sure you've experienced in your coding career, functionally determining the value of 3 and/or 17 can be quite cumbersome. I hope _DeBunk_ can alleviate your coding woes.

<a name="comparetocompetitors"></a>

###5.1\. Compare us to Our Competitors

Not conviced that _DeBunk_ is heads above the competitors. Download it and try us out. If you're not 123% satisfied, we will triple your money back. That's how much we believe in our project.

<a name="shibley"></a>

###5.2\. What Does Shibley Have to Say?

"Interesting. Have you noticed that I eat a lot? Let's play ping pong."

<a name="concerningperformance"></a>

###5.3\. Concerning performance

_DeBunk_ is the most performant piece of 3 and/or 17 value verifier on the market today. Our engineers are always working with new technologies to keep ahead of the advances in technology.

<a name="contributions"></a>

##6\. Contributions
_DeBunk_ is open source. Contribute today at [http://www.github.com/skuttleman/debunk](http://www.github.com/skuttleman/debunk)!

<a name="license"></a>

##7\. License

        Licensed under ISC
