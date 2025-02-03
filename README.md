# Terraform Azure - Simple VM Setup

This repository contains an practice made to learn how to configurate **Terraform** to provision a **Virtual Machine (VM)** in **Azure**.

## 🚀 Getting Started

Follow the instructions below to run the project locally:

### Prerequisites

Make sure you have the following tools installed on your environment:

- [Terraform](https://www.terraform.io/downloads.html)
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
- An **Azure** account with permissions to create resources.

### Setup Instructions

1. **Clone this repository:**

    ```bash
    git clone https://github.com/YourUsername/TerraformAzure.git
    cd Terraform-Azure
    ```

2. **Configure Azure credentials:**

    Make sure you're logged in to Azure via CLI:

    ```bash
    az login
    ```

3. **Initialize Terraform:**

    The following command will download the necessary providers and set up the Terraform state:

    ```bash
    terraform init
    ```

4. **Check the execution plan:**

    The following command will show the execution plan and the changes Terraform will make:

    ```bash
    terraform plan
    ```

5. **Apply the configuration:**

    If you're satisfied with the plan, apply the changes:

    ```bash
    terraform apply
    ```

    Confirm with `yes` to create the resources in Azure.

6. **Destroy resources (optional):**

    To remove all the resources created, you can use:

    ```bash
    terraform destroy
    ```

## 🛠️ Project Structure

- `main.tf`: Main Terraform configuration file.
- `.terraform/`: Directory where Terraform keeps state and plugins.
- `variables.tf`: Defines variables to customize the configuration.
- `outputs.tf`: Defines the Terraform outputs (such as VM IP addresses).


This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for more details.

---

### 🔗 Useful Links

- [Terraform Documentation](https://www.terraform.io/docs)
- [Azure Documentation](https://docs.microsoft.com/en-us/azure/)
