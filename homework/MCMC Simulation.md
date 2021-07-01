dta1 = rnorm(100,0,0.05)  
dta2 = dta1 + 1  
dta3 = cumprod(dta2)  
plot(dta3, type = "l",  
     main = "MCMC Simulation",  
     xlab = "Nunmber of Units",  
     ylab = "Cumulative Return Path from $1",  
     xlim = c(0,100),  
     ylim = c(0,3),  
     col = 405,  
     pch = "o",  
     lty = 1)  
i=1  
while(i<5){  
  i = i + 1  
  dta1 = rnorm(100,0,0.05)  
  dta2 = dta1 + 1  
  dta3 = cumprod(dta2)  
  lines(dta3,col = floor(runif(2, min=367, max=657)))  
}
