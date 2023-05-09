# MDM Deploy Notification

This action is used to send a notification to Microsoft Teams when a deployment finished

## Usage

```yaml
- name: Send notification to Microsoft Teams
  uses: freenet-actions/mdm-deploy-notification@main
  with:
    webhook: URI of the webhook # should be stored as secret
    env: Name of the environment
    application: Name of the application
    version: Version of the application
```
