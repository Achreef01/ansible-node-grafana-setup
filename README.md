
Overview

Our project provides a streamlined solution for deploying monitoring tools such as Prometheus and Grafana in a Kubernetes cluster provisioned through OpenStack Magnum. Leveraging Ansible playbooks and roles, we have automated the deployment process, making it easy to set up and manage monitoring infrastructure. The playbooks facilitate the installation of Prometheus and Grafana, along with the Node Exporter, ensuring comprehensive monitoring capabilities across the cluster. With our solution, users can quickly and efficiently establish a monitoring environment tailored to their needs, enhancing observability and enabling better management of Kubernetes workloads.

## Testing

To test the playbooks

```bash
  ansible-playbook -i master playbook_name
```

