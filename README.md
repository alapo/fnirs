# fnirs
fNIRS Guide for Dunn Lab


```matlab
tic

[Data] = Setup;

toc

```
 Here is another attempt
 
 ```matlab
 function y = average(x)
if ~isvector(x)
    error('Input must be a vector')
end
y = sum(x)/length(x); 
end
```
