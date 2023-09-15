# KubeGPT

AI powered Kubernetes assistant!

## Setup

Follow the steps below to set up the project:

1. **Create a Python Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
  ```

2. **Install Poetry**
  ```bash
   pip install poetry
  ```

3. **Install Dependencies using Poetry**
  ```bash
   poetry install
  ```

## Environment Variables

To run the project, you need to set the following environment variables:

1. `KUBEGPT_AUTH_TOKEN`: Your OpenAI API key. Example:

  ```bash
   export KUBEGPT_AUTH_TOKEN="openai-api-key"
  ```

2. `KUBEGPT_PREFIX`: Your kubectl command. Example:

  ```bash
   export KUBEGPT_PREFIX="AWS_PROFILE=saml KUBECONFIG=~/.kube/config_placeable /usr/local/bin/kubectl1.21 -n placeable-qa"
  ```
  
## Contributing

Feel free to contribute to the project by creating issues or pull requests.

