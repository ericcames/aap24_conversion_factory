The Ansible Automation Platform 2.4 conversion factory
=============

**Getting started**
1. [Get Automation Hub Token](https://console.redhat.com/ansible/automation-hub/token/ "Load Token")<br>
2. Ensure that we have a certified credential
    - Name
    ```
    Automation Hub - certified
    ```
    - Credential type
    ```
    Ansible Galaxy/Automation Hub API Token
    ```
    - Galaxy Server URL
    ```
    https://console.redhat.com/api/automation-hub/content/published/
    ```
    - Auth Server URL
    ```
    https://sso.redhat.com/auth/realms/redhat-external/protocol/openid-connect/token
    ```
    - API Token

![alt text](https://github.com/ericcames/aap24_conversion_factory/blob/main/images/aap24cred.png "certified")

3. Ensure that we have a validated credential
    - Name
    ```
    Automation Hub - validated
    ```
    - Credential type
    ```
    Ansible Galaxy/Automation Hub API Token
    ```
    - Galaxy Server URL
    ```
    https://console.redhat.com/api/automation-hub/content/validated/
    ```
    - Auth Server URL
    ```
    https://sso.redhat.com/auth/realms/redhat-external/protocol/openid-connect/token
    ```
    - API Token

4. Ensure the Galaxy credentials are related to the Default Organization
![alt text](https://github.com/ericcames/aap24_conversion_factory/blob/main/images/aap24orgcreds.png "Default Organization")