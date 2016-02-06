# FlowChartSVG

> Fork from [http://flowchart.js.org/](http://flowchart.js.org/)

## What you should do

#### 1. Edit index.html file
replace the code in the `<pre class="flow"><code>`
####2. Preview
Open index.html in browser.

## Grammer

```
tag=>type: content:>url
```

**type:**
- start
- end
- operation
- subroutine
- condition
- inputoutput

content is what it will show in the diagram.

url is a hypertext reference.

pay attention to the blank between `type:` and `content`.

connect two element is so easy like this `tag1->tag2`; just a little difference for type of condition : `cond1(yes)->tag3` and `cond1(no)->tag4`