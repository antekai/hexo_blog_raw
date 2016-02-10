---
title: testr
date: 2016-02-08 19:19:30
tags: rtest
---

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

{%math%} math \frac{|ax + by + c|}{\sqrt{a^{2}+b^{2}}} {%endmath%}
	
	You can also embed plots, for example:

![](images/unnamed-chunk-2-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.


``` r
for (i in 1:15){
paste ("hi")}
a=coredata(x2m[[1]])
plot(x2m[[1]])
ac=CasesSeries(a,1)
ac$d.ylag1=ac[,2]/ac[,1]
ac$d.ylag1[is.nan(ac$d.ylag1)]=0
ac$p=ac$d.ylag1*ac$lag1
ts.plot(ts(ac$y),ts(ac$p))

x2015=calcSol(39,BTd=fBTd(mode="serie",year=2015))@solI #synthetic data
```


{% blockquote [author[, source]] [link] [source_link_title] %}
content
{% endblockquote %}

{% blockquote %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque hendrerit lacus ut purus iaculis feugiat. Sed nec tempor elit, quis aliquam neque. Curabitur sed diam eget dolor fermentum semper at eu lorem.
{% endblockquote %}


{% blockquote Seth Godin http://sethgodin.typepad.com/seths_blog/2009/07/welcome-to-island-marketing.html Welcome to Island Marketing %}
Every interaction is both precious and an opportunity to delight.
{% endblockquote %}


{% textcolor danger %}Donec ullamcorper nulla non metus auctor fringilla.{% endtextcolor %}