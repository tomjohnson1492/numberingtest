---
layout: page
title: About
permalink: /about/
---

## Example using fenced code blocks {#fenced}

1.  This is step one. There are several lines of instruction, and so this phrase will repeat multiple times. There are several lines of instruction, and so this phrase will repeat multiple times. There are several lines of instruction, and so this phrase will repeat multiple times.

    And now here’s a new line of info.

    ```xml
     <property>
     <name>property-name goes here</name>
     <value>True</value>
     </property>

     <property>
     <name>another property-name goes here</name>
     <value>the value</value>
     </property>
    ```

    Here’s a bit more info.

1.  This should be step two, but it ends up as step one becasue of the code
   that’s between steps one and two.

    ```
    service daemon-name restart
    ```

1.  Repeat step 1 and 2 on every node.


## Example using highlight tag {#highlight}

<ol>
<li>This is step one. There are several lines of instruction, and so this phrase will repeat multiple times. There are several lines of instruction, and so this phrase will repeat multiple times. There are several lines of instruction, and so this phrase will repeat multiple times.

<p>And now here’s a new line of info.</p>

    {% highlight xml %}
     <property>
     <name>property-name goes here</name>
     <value>True</value>
     </property>

     <property>
     <name>another property-name goes here</name>
     <value>the value</value>
     </property>
    {% endhighlight %}

  <p>Here’s a bit more info.</p>
</li>
<li>This should be step two, but it ends up as step one becasue of the code

   <p>that’s between steps one and two.</p>

    {% highlight bash %}
    service daemon-name restart
    {% endhighlight %}

</li>
<li> Repeat step 1 and 2 on every node.</li>
</ol>
