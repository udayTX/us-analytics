# Getting Started with data visualization (Grafana + Prometheus)

**A robust data visualization solution to monitor high-transactional I.T. systems running on kuberenetes cluster (microservices based deployment). Import the code and get started!!**

<img width="897" alt="01" src="https://user-images.githubusercontent.com/93224640/152591974-abd570a8-2b4e-453a-9d02-52788f5c9150.PNG">

(A sample panel included in the attached json template - it has the necessary PromQL queries, scripted accordingly to pull accurate prometheus metrics from the databse, and use operators and functions to display the visualizations attached in the repository. More on that : https://prometheus.io/docs/prometheus/latest/querying/basics/)

Instructions to setup grafana and import dashboards.

# Prerequisites & steps:

1. A target system with kubernetes pods up and running (to be monitored)

2. Grafana, Prometheus installed and pods up and running in the monitoring cluster

3. Dashboard JSON codes : Kubernetes cluster monitoring.json

4. Prometheus datasource added in Grafana : https://prometheus.io/docs/visualization/grafana/


![image](https://user-images.githubusercontent.com/93224640/152584110-def3fd28-fc79-4386-a84c-3ea567180966.png)


Once grafana is logged in, use the Import tool from side menu to import the dashboards (**Kubernetes cluster monitoring.json**) : https://grafana.com/docs/grafana/latest/dashboards/export-import/

![image](https://user-images.githubusercontent.com/93224640/152584055-9e203b02-07ea-4f72-92f3-dbacffb286a4.png)


Give appropriate names and titles to the dashboards and all panels should be visible

# Attractive graphs that can dispay tons of info in a single dashboard

<img width="910" alt="02" src="https://user-images.githubusercontent.com/93224640/152583958-787369e7-a538-4d5d-bda7-ae7d10860814.PNG">

Save the dashboard.

Share / Export to different external users within your organization : https://grafana.com/docs/grafana/latest/sharing/

_Happy visualizing!!_

(more advanced projects with Python modules on the way..)
