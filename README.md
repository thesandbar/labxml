# labxml
An xml-based modeling language to formally describe lab processes, and some proof-of-concept tools to demonstrate value.

Motivation: Documentation can be surprisingly useful. 
However, it's hard to predict exactly what documentation will be needed in the future, so usually, it's good to produce a lot of documentation and sort through it later.
Making a lot of documentation is frankly, tedious, repetitive, error-prone, time consuming, and annoying. Reading through a pile of documentation is similar.
Computers, however, are really good at doing tasks that are unpleasant for those specific reasons.

So, my goal here is to make a way for it easy for chemists to create and use useful documentation relating to lab processes and lab work in a way that's even easier than just writing it down in a lab notebook.

This is, of course, all kind of a proof of concept.

Goals:
  1) Conceptual model for lab processes. Most likely, something recursive, where "processes" are something done to 1 or more input materials, with 1 or more output materials, and materials are defined by the processes that create them.
    
    a) An XSD schema that defines this conceptual model
    
    b) A couple examples of how a lab process can be represented within this schema. Or a cooking recipe. 
      
      i) Recursive recipe (perpetual stew/sourdoughs), list recipes (casserole), repeat-until-condition (purification), more when discovered
     
  2) A way to make the XML for a process human-readable
    
    a) Visual display - static
    
    b) Data analytics. 
    
    c) Conversion to instructions
  
  3) A way to make the XML human-writable on the fly
  
    a) Basic tree editor
    
    b) Basic custom process creator
    
    c) Basic library creator
    
    d) Combined dynamic visual display + editor
