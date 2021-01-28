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
<br> ECMAScript 6 introduced String.prototype.includes: 
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
As preferred, no developer wants to answer an ignorant question because they don't want to waste their time and efforts. However, they don't want to mislead others. You could go about telling the questioner to RTFM or STFW as Raymond puts it, but some that wouldn't be fair for the questioner and other potential people who have a similar question. For example in the forum Stack Exchange community, one question that could've easily been filtered out, but wasn't is this one; Can't install Visual Studio 2015 Community.
The one thing that is wrong with such a question is it answers itself and can be copy and pasted to the web. The question is also not a question and more so a problem, which is a bad approach to ask a bunch of developers in Stack Exchange. The detailed explanation is below:
<blockquote> 
  I'll get straight to the point here.

I've been having loads of problems installing Visual Studio 2015 Community recently. I previously had Visual Studio 2012, but decided to uninstall it and install 2015 since I've started using 2015 at college.

Originally I was using Windows 7 Professional when I was having the issues, but it persists with Windows 10. The exact issue is that when I try to install Visual Studio, it progresses a little bit and then stops at "Microsoft Visual C++ 2015 x86 Debug Runtime - 14.0.24210" and then doesn't progress past that. It will keep installing that for as long as I let it, and when I try to stop the download, it will not close and I will have to restart my PC. See here: 1

I contacted Microsoft support, which, I have to say, is appalling, and they recommended that I try to install it after performing a clean boot. I did that, and it seemed to be working, but I got multiple other errors. See here: 2

As I need this programme to help with college work, you can see how this would be a huge inconvenience for me, and since Microsoft support is so terrible, I decided to come here to ask for help.

So, would you please help me figure this out?
</blockquote> 

The expectation from this question seems like it would be simple and it is. If Microsoft support couldn't help you and whatever you did didn't work just replace it or take it into an expert. On the internet, Raymond states that it is difficult to find answers if you are not specific. In this scenario, the questioner only received 1 answer, which the provider was helping to the best of there ability and to no avail. Here is a synopsis of what the answerer said:
0

Refer to the log file, I found the error message 'The older version of Microsoft Visual C++ 2015 x86 Debug Runtime - 14.0.24210 cannot be removed', you can have a try with the following to troubleshot this issue:

1. Make sure run the installer as administrator.
2. Go to Control Panel—Programs and Features and if you can find any versions of Visual C++ 2015 Redistributable, right-click and repair. After that, re-run the VS installer as administrator to repair. If not works, uninstall the installed Visual C++ 2015 Redistributable versions and re-run the VS installer again.
3. You can also use the MsiInv tool: https://blogs.msdn.microsoft.com/astebner/2005/07/01/using-msiinv-to-gather-information-about-what-is-installed-on-a-computer/ to obtain all 4. Windows Installer products, features and components that Windows Installer thinks are installed on your computer, then manually uninstall the Visual C++ 2015 x86 Debug Runtime - 14.0.24210 by running msiexec /x command. After that, re-run the VS installer as administrator.
5. Download the Visual C++ 2015 Redistributable from https://www.microsoft.com/en-sg/download/details.aspx?id=48145 and install it, then re-run the VS installer to repair.

Although, it was a follow along guide; the questioner was rebuttling with even more issues. At this point, the comment section died and I am unsure if it was solved. A question like this makes it a not so smart one. If nothing seems to be working on one computer, maybe it is time to try an alternative and switch laptops or even throw away your system completely like Raymond puts it. In the following question, the questioner was fed up with his computer and you can tell the comment section was on fire with attitude. Even though, whomever helped him was trying their best, another issue would occcur. So at this point, it is time to either call tech support and if they can't help you ask for a refund as that is what I would do.

## Conclusion
To conclude, a smart question is a good question and a not so smart question is a bad question. Again, "English is the working language of the internet", in order to succeed at asking questions do your research first and then further ask questions when needed. Although, don't ask meaningless pointless questions like a system error as it is not a developers job to fix this for you as it could be a software issue, it could also be a hardware issue like Raymond states. Nonetheless, the web is your friend and use it wisely. The answers you seek are found within every website or article... so long as you do your research. Finally, remember that developers take a chunk of their day when asked upon, so be thankful and grateful for there help even when they haven't solved your issue. 






