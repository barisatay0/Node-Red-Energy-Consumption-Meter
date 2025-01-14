
# Node-Red Random Energy Consumption Meter

This project is an example for beginners who want to work with charts and PostgreSQL on Node-RED.



**How to Run:**

1. **Install Node-RED:**  
   First, make sure you have Node-RED installed on your system. You can install it by following the instructions on the [Node-RED official website](https://nodered.org/docs/getting-started/).

2. **Start Node-RED:**  
   Open a terminal (or command prompt) and run the following command to start Node-RED:
   
   ```
   node-red
   ```

3. **Open Node-RED Editor:**  
   Once Node-RED is running, open your browser and go to:
   
   ```
   http://localhost:1880
   ```

4. **Import the JSON file:**  
   - In the Node-RED editor, click on the menu (three horizontal lines) in the top-right corner.
   - Select **Import**.
   - Copy the JSON file contents and paste it into the import window, or directly upload the JSON file.
   - Click **Import** to load the flow.

5. **Configure PostgreSQL:**  
   If the flow uses a PostgreSQL database, make sure you have PostgreSQL installed and running.  
   You may need to configure the database credentials (host, port, username, password) in the Node-RED flow. Double-click on the relevant nodes in the flow to enter the correct database settings.

6. **Deploy the Flow:**  
   After importing and configuring the flow, click the **Deploy** button in the top-right corner to activate it.

7. **Check the Dashboard or Output:**  
   If the flow includes charts or dashboards, navigate to the Node-RED dashboard URL to see the visualization (typically `http://localhost:1880/ui`).

---



  
## Requirements

**For Dashboards:**@flowfuse/node-red-dashboard ( Also you can use Grafana )

**For Database:** node-red-contrib-postgresql


  
