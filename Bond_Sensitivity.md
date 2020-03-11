Bond Sensitivity
================

Given that present value of bond is estimated by

$$PV = \\frac{PMT}{r}(1- \\frac{1}{(1+r)^{T}}) + \\frac{Face Value}{(1+r)^{T}}$$

and the sensitivity of bond value to change in discount rate can be derived from partial derivative of PV, which is

$$\\frac{\\partial PV}{\\partial r} = PMT(- \\frac{1}{r^{2}} + \\frac{1}{r^{2}(1+r)^{T}} - \\frac{T}{r(1+r)^{T+1}}) - \\frac{FV \\times T}{(1+r)^{T+1}}$$

and the percentage of change can be written as

$$\\frac{(\\frac{\\partial PV}{\\partial r})}{PV} = f(r,T,PMT,FV) = \\frac{PMT(- \\frac{1}{r^{2}} + \\frac{1}{r^{2}(1+r)^{T}} - \\frac{T}{r(1+r)^{T+1}}) - \\frac{FV \\times T}{(1+r)^{T+1}}}{\\frac{PMT}{r}(1- \\frac{1}{(1+r)^{T}}) + \\frac{Face Value}{(1+r)^{T}}}$$

constructing function and plot different plots.

![](Bond_Sensitivity_files/figure-markdown_github/bond%20bondsens%20plot-1.png)![](Bond_Sensitivity_files/figure-markdown_github/bond%20bondsens%20plot-2.png)![](Bond_Sensitivity_files/figure-markdown_github/bond%20bondsens%20plot-3.png)
