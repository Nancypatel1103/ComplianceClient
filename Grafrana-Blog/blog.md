

## Problem

We have several graphs in our dashboard, and the data is shown according to the API calls. So, for that, we should use some plugins to integrate our graphs into the
application. For the purpose of integrating the graphs in angular applications, numerous libraries are available. For example, apex charts, Ngx charts, D3.js, and the Apache Echart Library. Because the data is updated continuously, we have to access the API every 5 seconds to render the graphs. Each API call increases the rendering and chart loading times. Furthermore, we ought to deal with each library, and the many libraries also led to an increase in package size.

## Solution
