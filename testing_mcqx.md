gitbook-plugin-mcqx
===

<!--sec data-title="Introduction" data-id="intro" ces-->
This page is implemented using the two plugins developed by me: ```gitbook-plugin-mcqx``` and ```gitbook-plugin-sectionx```. You can use the two plugins separately, but they can also be integrated for more interactivity.

Please check the [Github repo](https://github.com/ymcatar/gitbook-plugin-mcqx) for the syntax, changelog of the plugin ```gitbook-plugin-mcqx```. Syntax too complicated? Use the code generator in the [plugin homepage](http://ymcatar.github.io/gitbook-plugin-mcqx/).

The source code for this page is available [here](https://raw.githubusercontent.com/ymcatar/gitbook-test/master/testing_mcqx.md) for your reference.
<!--endsec-->

<!--sec data-title="Example" data-id="q2" data-show=true ces-->

Question attempted will be disabled, however, you can open a new tab in Incognto Mode (Chrome), Private Window (Firefox), or clear your cookies if you want to try to answer this question again.

The ```random``` option is enabled for the question, you might find the order of the questions to be different when you refresh the page.

{%mcq ans="o4", random=true%}
{%title%}
Which of the following is not a planet in the Solar System?
{%o1%} Jupiter
{%o2%} Earth
{%o3%} Mars
{%o4%} Pluto
{%hint%} Poor Pluto ...
{%endmcq%}

The ```random``` option is disabled for the question.

{%mcq ans="o3"%}
{%title%} Just click option C to continue.
{%o1%} Don't click me. I'm A.
{%o2%} Don't click me. I'm B.
{%o3%} Click me.
{%o4%} Don't click me. I'm C.
{%hint%} It is so hard to come up with placeholder question ...
{%endmcq%}

You can use ```count``` to only displayed a certain number of options. You can try to see all the options by refreshing the page, or if you are smart, just take a look of the source code of this page.

{%mcq ans="o4", count=7%}
{%title%} Just find the number "42" and click it.
{%o1%} ```689```
{%o2%} 30626700^23
{%o3%} 30624770
{%o4%} 42
{%o5%} 1234
{%o6%} 99999
{%o7%} 1
{%o8%} -3
{%hint%} It is so hard to come up with placeholder question ...
{%endmcq%}

You can add a ```{%message%}``` sub-block. The message will be displayed only after the user has answered the question correctly, useful for outputing answer explanation.

{%mcq ans="o4", random=true%}
{%title%} Just find the number ```42``` and click it.
{%o1%} 31
{%o2%} 13
{%o3%} 689
{%o4%} 42
{%message%} This message is only visible to those who answered this question correctly ...
{%endmcq%}

<!--endsec-->
