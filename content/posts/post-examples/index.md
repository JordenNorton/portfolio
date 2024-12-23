---
title: "Post Examples"
date: 2024-12-02
draft: false
description: "a post with example text"
#tags: ["example", "tag", "russian"]
tags:
  - russian

---
 Post example
# This is a heading
## This is a subheading
### This is a subsubheading
#### This is a subsubsubheading
{{< highlight go >}} A bunch of code here {{< /highlight >}}

{{< alert icon="fire" cardColor="#e63946" iconColor="#1d3557" textColor="#f1faee" >}}
This is an error!
{{< /alert >}}

{{< chart >}}
type: 'bar',
data: {
labels: ['Tomato', 'Blueberry', 'Banana', 'Lime', 'Orange'],
datasets: [{
label: '# of votes',
data: [12, 19, 3, 5, 3],
}]
}
{{< /chart >}}

{{< github repo="JordenNorton/poly-prompt-backend" >}}

{{< keywordList >}}
{{< keyword icon="github" >}} Lorem ipsum dolor. {{< /keyword >}}
{{< keyword icon="code" >}} **Important** skill {{< /keyword >}}
{{< /keywordList >}}

{{< keyword >}} *Standalone* skill {{< /keyword >}}

#### CV Example?
{{< timeline >}}

{{< timelineItem icon="github" header="header" badge="badge test" subheader="subheader" >}}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus non magna ex. Donec sollicitudin ut lorem quis lobortis. Nam ac ipsum libero. Sed a ex eget ipsum tincidunt venenatis quis sed nisl. Pellentesque sed urna vel odio consequat tincidunt id ut purus. Nam sollicitudin est sed dui interdum rhoncus.
{{< /timelineItem >}}


{{< timelineItem icon="code" header="Another Awesome Header" badge="date - present" subheader="Awesome Subheader" >}}
With html code
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
{{< /timelineItem >}}

{{< timelineItem icon="star" header="Shortcodes" badge="AWESOME" >}}
With other shortcodes
{{< gallery >}}
<img src="gallery/01.jpg" class="grid-w33" />
<img src="gallery/02.jpg" class="grid-w33" />
<img src="gallery/03.jpg" class="grid-w33" />
<img src="gallery/04.jpg" class="grid-w33" />
<img src="gallery/05.jpg" class="grid-w33" />
<img src="gallery/06.jpg" class="grid-w33" />
<img src="gallery/07.jpg" class="grid-w33" />
{{< /gallery >}}
{{< /timelineItem >}}

{{< timelineItem icon="code" header="Another Awesome Header">}}
{{< github repo="nunocoracao/blowfish" >}}
{{< /timelineItem >}}

{{< /timeline >}}


This is a paragraph with **bold** and *italic* text.
Check more at [Blowfish documentation](https://blowfish.page/)
undefined