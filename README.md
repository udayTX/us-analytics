# A simple data visualization solution to monitor high-transactional I.T. systems running on kuberenetes cluster (microservices based deployment).

Instructions to setup grafana and import dashboards.

# Prerequisites & steps:
1. A target system with kubernetes pods up and running (to be monitored)

2. Grafana, Prometheus installed and pods up and running in the monitoring cluster

3. Prometheus datasource added in Grafana : https://prometheus.io/docs/visualization/grafana/

![image](https://user-images.githubusercontent.com/93224640/152584110-def3fd28-fc79-4386-a84c-3ea567180966.png)


Once grafana is logged in, use the Import tool from side menu to import the dashboards (**Kubernetes cluster monitoring.json**) : https://grafana.com/docs/grafana/latest/dashboards/export-import/

![image](https://user-images.githubusercontent.com/93224640/152584055-9e203b02-07ea-4f72-92f3-dbacffb286a4.png)


Give appropriate names and titles to the dashboards and all panels should be visible

<img width="910" alt="02" src="https://user-images.githubusercontent.com/93224640/152583958-787369e7-a538-4d5d-bda7-ae7d10860814.PNG">

Save the dashboard.

Share / Export to different external users within your organization : https://grafana.com/docs/grafana/latest/sharing/

Happy visualizing!!
