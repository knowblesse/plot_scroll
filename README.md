# plot_scroll
Draw multiple plots with subplot function with scroll bar
# Syntax
`plot_scoll(X)`

`[fig,Axes] = plot_scroll(X)`

`[fig,Axes] = plot_scroll(__, Name, Value)`
# Description
plot_scroll(X) creates a figure with multiple subplots and scroll bar. 

X should be numeric 2D array.

X which has mxn dimension will be divided into mx1 arrays and result n subplots.

##
Possible Name Value pairs are below

Name | Value | Default | Meaning
------------ | ------------- | -------------| -------------
'PlotFunction' | function handle | @plot | Plotting function to use

# License 
@Knowblesse 2018




