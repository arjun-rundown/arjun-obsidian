---
title: Headers Code
draft: false
tags: []
---
 
 
# Related Notes
#### Translucent Header with Blur BG effect####
```
selector.elementor-sticky--effects{ 
   background-color: rgba(0,0,0,0.4)!important; 
   backdrop-filter: saturate(180%) blur(20px);
   -webkit-backdrop-filter: saturate(180%) blur(20px);
}
selector{ 
   transition: background-color 1s ease !important;
}
selector.elementor-sticky--effects >.elementor-container{
   min-height: 70px;
}
selector > .elementor-container{
   transition: min-height 1s ease !important;
}
```

Additional conditions for above code: Make sure bottom Margin is -135 or at least -100 set Z index to 10 the copy paste below code
# Research

# Reference Links

# Reference Videos