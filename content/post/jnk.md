+++
date      = 2023-05-18
draft     = false
tags      = ["Borrar"]
math      = true
authors = ["admin"]
+++


```{r}
enamine <- data.frame(x1=gl(2,1,4,labels=c("-","+")),
                      x2=gl(2,2,4,labels=c("-","+")),
                      y=c(80.4,72.4, 94.4, 90.6))

coded <- function(x,v="+"){
  if(missing(v))
    out= x==x[1]
  else
    out= x==v
  return(2*out-1)
}

sum(coded(enamine$x1)*enamine$y)/2
sum(coded(enamine$x2)*enamine$y)/2
sum(coded(enamine$x1)*coded(enamine$x2)*enamine$y)/2
```
