Prerequisites:
    - register your or test app for decode token with claims(https://learn.microsoft.com/uk-ua/azure/active-directory-b2c/tutorial-register-applications)
    - Add signing and encryption keys for Identity Experience Framework applications(https://learn.microsoft.com/uk-ua/azure/active-directory-b2c/tutorial-create-user-flows?pivots=b2c-custom-policy#register-the-proxyidentityexperienceframework-application)
    - register IdentityExperienceFramework app (https://learn.microsoft.com/uk-ua/azure/active-directory-b2c/tutorial-create-user-flows?pivots=b2c-custom-policy#register-identity-experience-framework-applications)
    - register ProxyIdentityExperienceFramework app (https://learn.microsoft.com/uk-ua/azure/active-directory-b2c/tutorial-create-user-flows?pivots=b2c-custom-policy#register-the-proxyidentityexperienceframework-application)
    - replace ProxyIdentityExperienceFramework_populate_by_value and IdentityExperienceFramework_populate_by_value by AppIds
    - replace b2c-extensions-app_clientId_populate_by_value and b2c-extensions-app_clientId_populate_by_value by values from default app b2c-extensions-app. Do not modify. Used by AADB2C for storing user data.

For Local Accounts follow:
https://learn.microsoft.com/uk-ua/azure/active-directory-b2c/tutorial-create-user-flows?pivots=b2c-custom-policy

For CustomPolicyOverview
https://learn.microsoft.com/en-us/azure/active-directory-b2c/custom-policies-series-overview

useful links:
https://learn.microsoft.com/en-us/community/content/working-with-azure-ad-b2c-custom-policies