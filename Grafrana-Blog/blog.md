# Grafana - Free open source analytics & monitoring tool
Grafana is a free open-source analytics & monitoring tool with multi-language support. This allows users to create dynamic dashboards, monitoring the application
performance.

## Problem

We have several graphs in our dashboard, and the data is shown according to the API calls. So, for that, we should use some plugins to integrate our graphs into the
application. To integrate the graphs in angular applications, numerous libraries are available. For example, apex charts, Ngx charts, D3.js, and the Apache Echart Library. Because the data is updated continuously, we have to access the API every 5 seconds to render the graphs. Each API call increases the rendering and chart loading times. Furthermore, we ought to deal with each library, and the many libraries also led to an increase in package size.

## Solution
A novel method for generating a dashboard based on several datasets is necessary to address the aforementioned issue. You must set up the Grafana server using the Grafana plugin and set up your Grafana account.

Please click this link to install Grafana, then configure the Grafana server on your Ubuntu computer. (https://grafana.com/docs/grafana/latest/setup-grafana/installation/debian/)

- To start your Grafana server, Please run the following steps in the terminal,
  - sudo systemctl start grafana-server (start Grafana server)
  - Now, open your browser (Google Chrome, Firefox, etc. and open the URL. (http://127.0.0.1:3000/)

  ![image-1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/5b89b1fa-b129-4507-9c2a-0241e6fcf039)



- After setting up the Grafana, you can see the welcome page of the Grafana.  (Note: The default credentials username is **admin** and the password is **admin**).
The screen to create your data source and dashboards is now visible to you.

  ![image-2](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6fefd1b1-6da1-41e0-9368-538ba15f2871)


1. **Add your first data source:** To create the dashboard, you must choose the backend database and link our database.
2. **Create your first dashboard:** This option is used to create a dashboard using several panels and charts that are dependent on our database queries.

- The options to create a new dashboard and import an existing dashboard are located in the right-hand corner.

  ![image-3](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/4c978209-110c-4582-abeb-edcb3af6be8b)

- When you click on the **Add your first data source**, Graphana allows you to select the data source from the options to select one of the available data sources.

  ![image-4](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/d54bfc54-a62d-4afc-a9d1-f472c27b1b65)
 
- I have added a new data source called **Infinity** in order to generate dashboards utilizing an API. You can choose **Add new connection** from the left panel and search for infinite among the available options to install an infinite data source. Now, you can start creating a dashboard using the **Build a dashboard** option.

  ![image-5](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/fc496c46-bfb0-47d6-b814-f4012c4d6bd0)

  ![image-6](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/39311ebd-ce61-4e73-8009-b05e600d320a)


- You can modify the plugin's parameters after choosing the Infinity plugin. You can set **headers & URL parameters, Authentication, and Other API options**.

  ![image-7](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c7251ce1-5efe-400d-a4af-f30e1b5db22f)

- You can find the created/imported dashboard under the dashboard options.

  ![image-8](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/7aa01f45-f1f5-4b0b-8276-cd361a91647a)

- Clicking on any dashboard in the list will take you to a screen with a variety of panels that display different kinds of charts.

  ![image-9](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/6b489b2e-b5b0-40be-aaab-2ecc11c179ad)

- For the panel, there are several alternatives available. To edit a single panel and view the graphs in the Grafana editor, use the **Edit** option.

  ![image-10](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/63083b86-9e2b-436b-a663-78d7ee20085c)

- There are several choices available in the Grafana editor to modify the type of graph.
- In the Right Side Panel,
   - **Visualizations:**  To view the data, choose any of the charts.                     
   - **Suggestions:**  Grafana automatically generated graph suggestions.
   - **Library Panels:**  All the libraries that you’ve created for the graphs.
- Here, we can assign the variables like [[here_use_your_api_starting_point]]. You now have a query regarding how to provide that variable's value. Don't worry, I'll be giving the processes for initializing variables below.
   - Go to **Dashboard Settings** > **Go to Variables** > Click on **New Variables**
   > Select the variable type > Provide the data of the variable and click on Apply

  ![image-11](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/c6aeeb53-8cf1-4dbd-b365-f7643e65b157)

- We've created the graph panel now. We now have several ways to distribute the Grafana panel.

  ![image-11 1](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/1c40673c-2db1-4e7c-9062-cf2b3abb0250)
  
- To see our panel in the Grana, select the **Embed** option and utilize the iframe.

  ![image-12](https://github.com/Nancypatel1103/ComplianceClient/assets/153616269/ceaf2e40-4a97-41aa-9859-904801d61b98)







