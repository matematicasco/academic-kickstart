+++
date      = 2023-05-18
draft     = false
tags      = ["Borrar"]
title     = "Borrar"
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


```{r}
plot(c(-1,1), enamine$y[1:2],type="b",ylim=c(70,95),xlim=c(-1.5,2.1), pch=16,
     xlab="Amount of Formic acid",xaxt="n",
     ylab="Yield of bornylmorpholine %",main="Gráfico de Interacción")
axis(1,at=c(-1,1),labels=c("1 mol/mol","1.5 mol/mol"))
lines(c(-1,1),enamine$y[3:4],lty=2); points(c(-1,1),enamine$y[3:4],pch=16)
legend(x = 1.1, y = 85, legend = c("-","+"), lty=1:2, title="Temperature")

```





```{r}
conversion <- data.frame(A=gl(2,3,12,c("-","+")),
                         B=gl(2,6,12,c("-","+")),
                         Yield=c(28,25,27,36,32,32,18,19,23,31,30,29) )
n <- 3
sum(coded(conversion$A)*conversion$Yield)/(2*n)
```


```{r}

```

