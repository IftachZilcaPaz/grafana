
# Grafana

## Overview

This project contains a Grafana dashboard configuration for monitoring Kubernetes namespaces and nodes using Prometheus as the data source. The dashboard includes various panels and visualizations to help you track the performance and status of your Kubernetes cluster.

## Features

- **Namespace Monitoring**:
  - Gauge to monitor the number of pod restarts in a namespace.
  - Graph to visualize CPU usage in a namespace.
  - Gauge to display the number of running pods in a namespace.
  - Gauge to show the number of deployments in a namespace.
  - Time series to track network traffic (transmit and receive) in a namespace.
  - Time series for memory usage in a namespace.

- **Node Monitoring**:
  - Stat panel to monitor the number of pods running on a node.
  - Time series to track CPU usage by cores.
  - Bar gauge for CPU usage by percentage.

- **Pod Monitoring**:
  - Gauge for CPU usage by pod.
  - Bar gauge for CPU usage percentage by pod.
  - Time series for disk I/O (read and write) by pod.
  - Time series for network traffic (transmit and receive) by pod.
  - Time series for average memory usage by pod.
  - Gauge for pod age.

- **Container Monitoring**:
  - Time series to monitor CPU and memory usage by container.
 
--------

&nbsp;
&nbsp;
&nbsp;
&nbsp;

--------

## Installation

## Clone the Repository:
   ```sh
   https://github.com/IftachZilcaPaz/grafana.git
   ```
## Import the Dashboard

   - Open Grafana and navigate to the dashboards.
   - Click on "Import" and upload the JSON file `proj-1718112364380.json` from the repository.


## Configure Data Sources

- Ensure Prometheus is configured as a data source in Grafana.
-  Adjust the data source settings in the dashboard to match your Prometheus configuration if necessary.

## Usage

### Select the Variables

- Use the dropdowns at the top of the dashboard to select the namespace, node, pod, and container you want to monitor.

### View the Panels

- Explore the various panels to get insights into your Kubernetes cluster's performance, such as CPU usage, memory usage, pod restarts, network traffic, and more.

## Customization

### Adding New Panels

- You can add new panels by clicking on the "Add Panel" button in Grafana and configuring it as needed.

### Editing Existing Panels

- To edit an existing panel, click on the panel title, select "Edit", and modify the panel settings.

### Changing Data Source

- If you need to change the data source, go to the "Settings" of the dashboard, navigate to the "Variables" section, and update the data source configuration.

## Contributing

We welcome contributions! Please follow these steps to contribute to the project:

### Fork the Repository

- Click the "Fork" button on the top right of this page to create a copy of this repository in your GitHub account.

### Create a Branch

- Create a branch in your forked repository to work on your feature or fix:
  ```sh
  git checkout -b feature-or-fix-name
  ```

### Commit Your Changes

- Commit your changes with a descriptive commit message:
  ```sh
  git commit -m "Description of the feature or fix"
  ```

### Push to the Branch

- Push your changes to the branch:
  ```sh
  git push origin feature-or-fix-name
  ```


### Open a Pull Request

- Open a pull request from your branch to the `main` branch of this repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.






  
