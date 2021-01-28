---
layout: essay
type: essay
title: It is Important to Know
date: 2021-01-27
labels:
  - Software Engineering
  - Educational
  - Stack Overflow
---
## Introduction

According to Eric Raymond, "English is the working language of the internet." The internet is filled with forums, websites, and operations that allow users to find answers to questions. Although, sometimes questions can be either smart or not so smart. Eric Raymond's essay <i> "How To Ask Questions The Smart Way" </i> gives its readers insight on how to approach asking a question to get the answers you seek. In one way, a "smart" question leads to efficient and effective help. In another way, a "not so smart" question leads to the opposite. Im sure we've all been there, we thought our questions were smart because we received an answer, though what if you can elevate that question to receive a better answer than you expected. Before asking a technical question, do these following tips that Eric wrote:
<blockquote>
  1. Try to find an answer by searching the archives of the forum or mailing list you plan to post to.
  <br>2. Try to find an answer by searching the web.
  <br>3. Try to find an answer by reading the manual.
  <br>4. Try to find an answer by reading a FAQ.
  <br>5. Try to find an answer by inspection or experimentation.
  <br>6. Try to find an answer by asking a skilled friend.
  <br>7. If you're a programmer, try to find an answer by reading the source code.
</blockquote>
If you had no success at the mentioned tips, then next is the easy part, but that depends on what your goals are and what you expect out of them.

## The Smart Way

First off, "smart" questions are successful on the internet. If you produce a smart question, then you wouldn't be considered as a time sink like Raymond says in his essay. In order to produce such a question; do not be blind and fire off many questions at once. Such questions are filtered out and can lead to a potential block from the forum leader. It is vital that when forming a question, do your research prior to it. Not only does it help with the formation, but you may also find an answer. A question can be answered effectively if done on the right forum. One forum used by many "hackers" or programmers described by Raymond is Stack Overflow. This website has a Stack Exchange community where your smart questions can be answered. For example, a smart question like How to check whether a string contains a substring in JavaScript? was viewed over 6.4m times and the details proved that whomever asked the question certainly did their research. The details of the question said this:
<blockquote> "Usually I would expect a String.contains() method, but there doesn't seem to be one. What is a reasonable way to check for this?." </blockquote> Not only was it brief to read since time is of the essence for developers. It is also identifable that there was research done prior and even tried executing the String.contains() method in his own JS editor. Of the many answers, one answer got 14327 votes and has a green checkmark meaning that it was effective and efficient help. The answer was structured as such: 
ECMAScript 6 introduced String.prototype.includes: 
```
      const string = "foo";
      const substring = "oo";

      console.log(string.includes(substring));
```
includes doesn’t have Internet Explorer support, though. In ECMAScript 5 or older environments, use String.prototype.indexOf, which returns -1 when a substring cannot be found:
```
    var string = "foo";
    var substring = "oo";

    console.log(string.indexOf(substring) !== -1);
```
As you can see the answer was effective; the solution had the type of language version and also gave code example as well as another example if the user was using Internet Explorer. Based on Raymond's essay, the smart question was answered in a gentle way with enough help. 
It included research that demonstrated those skills rather than just trying to use words to explain. <img class="ui small right floated rounded image" src="../images/show.jpg">

<br>A smart question like this one finds much better results opposed to one that isn't smart. 

## The Not...So Smart Way
<img class="ui small right floated rounded image" src="../images/question.jpg">
<p>As preferred, no developer wants to answer an ignorant question because they don't want to waste their time and efforts. However, they don't want to mislead others. You could go about telling the questioner to RTFM or STFW as Raymond puts it, but some that wouldn't be fair for the questioner and other potential people who have a similar question. For example in the forum Stack Exchange community, one question that could've easily been filtered out, but wasn't is this one; How to check if the string is empty?. The one thing that is wrong with such a question is it answers itself and can be copy and pasted to the web. In the questioners detailed explanation below:</p>
  Does Python have something like an empty string variable where you can do:
      ```
        if myString == string.empty:
      ``` 
  Regardless, what's the most elegant way to check for empty string values? I find hard coding "" every time for checking an empty string not as good.
 
