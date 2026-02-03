# n8n Automations 🚀

A collection of custom n8n workflows designed to streamline CRM processes, eCommerce operations, and general business utilities.

## 📂 Project Structure

* **`workflows/`**: The core logic of the repository.
    * `crm/`: Workflows for HubSpot, Salesforce, etc. (includes the *After-Call Work Optimizer*).
    * `ecommerce/`: Shopify, WooCommerce, or inventory logic.
    * `social-media/`: Automation for LinkedIn, Twitter, or Meta.
    * `utilities/`: Helper flows like data cleaning or system health checks.
* **`docs/`**: Detailed setup guides and credential requirements.
* **`examples/`**: Sample JSON files and dummy data for testing.

## 🛠️ How to Import Workflows

1.  Navigate to the `workflows/` directory.
2.  Open the desired `.json` file.
3.  Copy the entire content of the file.
4.  In your **n8n canvas**, simply press `Ctrl + V` (Windows) or `Cmd + V` (Mac).
5.  Configure your specific credentials in the nodes that require them.

## 📝 Prerequisites

* An active **n8n** instance (Desktop, Self-hosted, or Cloud).
* API access for the services involved (e.g., HubSpot API Key, OpenAI API Key).

## 🤝 Contribution
Feel free to fork this repository and submit pull requests for any interesting automations you've built!