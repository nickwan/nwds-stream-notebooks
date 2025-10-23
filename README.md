# nwds-stream-notebooks
notebooks from my stream

# Yo, it's nw 
I am uploading all my notebooks from stream here. Commonly you'll see this snippet of code at the top: 

```
def increase_font():
  from IPython.display import Javascript
  display(Javascript('''
  for (rule of document.styleSheets[0].cssRules){
    if (rule.selectorText=='body') {
      rule.style.fontSize = '24px'
      break
    }
  }
  '''))
get_ipython().events.register('pre_run_cell', increase_font)
```

This is strictly for stream. It was to increase output size for font and make displaying results on stream easier for viewers. You can literally not run this and everything works. So if you are walking through any of these notebooks and see that at the top (usually in a H1 header that I minimized while streaming), feel free to run it or ignore it completely or delete it. Will not effect any of the code or outputs after it. :)  
