# Authorization Code Sample Application

This application is a sample for how you can set up your own application that uses an authcode grant type. The application is written in java and uses Spring Cloud Security for the SSO flow.

## Creating authcode aka Web App client in Pivotal Single Sign-On Service

1. Navigate to your app in Apps Manager and bind it to the Pivotal Single Sign-On Service.
2. Navigate to the service bindings for your application and click on credentials. Copy the `APP_ID`, `APP_SECRET` and `ID_SERVICE_URL`.
3. Go back to Apps Manager and follow the steps [here] (https://github.com/pivotal-cf/identity-sample-apps#step-3-update-oauth-client-information-in-the-application)

