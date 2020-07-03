# Username and password app for the Microsoft Graph in Python
This project is based on the following Microsoft sample app:

https://github.com/Azure-Samples/ms-identity-python-desktop/tree/master/1-Call-MsGraph-WithUsernamePassword

See the README in the original repo for details.

Very important:

The User.ReadBasic.All permission will only allow the user to see a few
profile attributes for other users _even using the beta API_:

```
displayName
givenName
mail
surname
userPrincipalName
```

To see the rest (such as postal addresses), you need to have a (Global tenant) admin assign
User.Read.All and consent to its application across the tenant.
