# what is the error looks like   
for some labtop, it need to open RStudio as administrator.   
at first setup a set of data and key in some numbers.    
>        >data <- data.frame( x=numeric(0), y=numeric(0) )   
>        >data <- edit(data)
>          -x  -y
>          -1  -2
>          -2  -4
>          -3  -6
>          -4  -8
>          -5  -10
>          -6  -12
>          -7  -14
>          -8  -16
![seted data set](https://github.com/tuxiaoyue/fix-plot-error-in-RStudio/blob/master/set%20data.JPG)    
>        > plot(data)
    
then error occur
>         Error in gzfile(file, "wb") : cannot open the connection
>         In addition: Warning message:
>         In gzfile(file, "wb") :
>             cannot open compressed file 'C:/Users/????/AppData/Local/Temp/Rtmp4M1uVV/rs-graphics-2423e4a9-b452-491c-808e-bccdbc9a08bf/464bbd85-6afd-4130-ae7e-b04b67700634.snapshot', probable reason 'Invalid argument'
>           Graphics error: Plot rendering error    


# fix the error
for fix this error, we need chang a 
