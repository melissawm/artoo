# artoo

Personal automations.

## Testing locally

1. Install nektos/act
2. Make sure docker service is running:
    ```bash
    $ sudo systemctl status docker.service
    ```
3. Run 
    ```bash
    $ sudo act
    ```
4. For authentication, with the GitHub CLI installed, run
    ```bash
    $ sudo act -s WORKFLOW_PAT="$(gh auth token)"
    ```
