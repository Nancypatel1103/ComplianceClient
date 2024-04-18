

## Problem

We have several graphs in our dashboard, and the data is shown according to the API calls. So, for that, we should use some plugins to integrate our graphs into the
application. To integrate the graphs in angular applications, numerous libraries are available. For example, apex charts, Ngx charts, D3.js, and the Apache Echart Library. Because the data is updated continuously, we have to access the API every 5 seconds to render the graphs. Each API call increases the rendering and chart loading times. Furthermore, we ought to deal with each library, and the many libraries also led to an increase in package size.

## Solution
A novel method for generating a dashboard based on several datasets is necessary to address the aforementioned issue. You must set up the Grafana server using the Grafana plugin and set up your Grafana account.

Please click this link to install Grafana, then configure the Grafana server on your Ubuntu computer. (https://grafana.com/docs/grafana/latest/setup-grafana/installation/debian/)

- To start your Grafana server, Please run the following steps in the terminal,
  - sudo systemctl start grafana-server (start Grafana server)
  - Now, open your browser (Google Chrome, Firefox, etc. and open the URL. (http://127.0.0.1:3000/)


After setting up the Grafana, you can see the welcome page of the Grafana.  (Note: The default credentials username is **admin** and the password is **admin**).
The screen to create your data source and dashboards is now visible to you.


1. **Add your first data source:** To create the dashboard, you must choose the backend database and link our database.
2. ** Create your first dashboard:** This option is used to create a dashboard using several panels and charts that are dependent on our database queries.

- The options to create a new dashboard and import an existing dashboard are located in the right-hand corner.
- When you click on the **Add your first data source**, Graphana allows you to select the data source from the options to select one of the available data sources.
- I have added a new data source called **Infinity** in order to generate dashboards utilizing an API. You can choose **Add new connection** from the left panel and search for infinite among the available options to install an infinite data source. Now, you can start creating a dashboard using the **Build a dashboard** option.
- You can modify the plugin's parameters after choosing the Infinity plugin. You can set **headers & URL parameters, Authentication, and Other API options**.
- You can find the created/imported dashboard under the dashboard options.
- Clicking on any dashboard in the list will take you to a screen with a variety of panels that display different kinds of charts.
- For the panel, there are several alternatives available. To edit a single panel and view the graphs in the Grafana editor, use the **Edit** option.
- There are several choices available in the Grafana editor to modify the type of graph.
- In the Right Side Panel,
   - **Visualizations:**  To view the data, choose any of the charts.                     
   - **Suggestions:**  Grafana automatically generated graph suggestions.
   - **Library Panels:**  All the libraries that you’ve created for the graphs.
- Here, we can assign the variables like [[here_use_your_api_starting_point]]. You now have a query regarding how to provide that variable's value. Don't worry, I'll be giving the processes for initializing variables below.
   - Go to **Dashboard Settings** > **Go to Variables** > Click on **New Variables**
   > Select the variable type > Provide the data of the variable and click on Apply

- We've created the graph panel now. We now have several ways to distribute the Grafana panel.
- To see our panel in the Grana, select the **Embed** option and utilize the iframe.







