dta1 = c(1,rnorm(100,0,0.05)) #Length = 100, Mean = 0, s.d = 0.05  
dta2 = dta1 + 1  
dta3 = cumprod(dta2)  

par(mfrow = c(1,1))  
plot(dta3, type = "l",  
&nbsp; &nbsp; &nbsp; &nbsp; main = "MCMC Simulation",  
&nbsp; &nbsp; &nbsp; &nbsp; xlab = "Time Step",  
&nbsp; &nbsp; &nbsp; &nbsp; ylab = "Index Level",  
&nbsp; &nbsp; &nbsp; &nbsp; xlim = c(0,100),  
&nbsp; &nbsp; &nbsp; &nbsp; ylim = c(0,3),  
&nbsp; &nbsp; &nbsp; &nbsp; col = 1,   
&nbsp; &nbsp; &nbsp; &nbsp; lty = 1) 
     
i=1  
while(i<5){  
&nbsp; &nbsp; &nbsp; &nbsp; i = i + 1  
&nbsp; &nbsp; &nbsp; &nbsp; dta1 = c(1,rnorm(100,0,0.05))  
&nbsp; &nbsp; &nbsp; &nbsp; dta2 = dta1 + 1  
&nbsp; &nbsp; &nbsp; &nbsp; dta3 = cumprod(dta2)  
&nbsp; &nbsp; &nbsp; &nbsp; lines(dta3,col = i, lty = i)  
}  
#Number of paths = 5
