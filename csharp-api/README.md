# Address Book API Challenge

The aim of this challenge is to take this minimal solution and implement a API for managing a users address book that can support the following operations:

1. Create a new address
2. Update an existing address
3. Delete an existing address
4. List all addresses for the user
5. Get a single address for the user

Users should only be able to access their own addresses. For the sake of simplicity only UK addresses are required. Their is no need to implement all operations in full but an end to end on one of the update operations would be helpful.

What we're looking for is an understanding of how you would implement the following capabilities:

1. Token based authentication
2. Validation of the inputs
3. Error handling
4. Consumption of secrets
5. Appropriate use of HTTP verbs and responses
6. Exposure of the OpenAPI specification in development mode
7. Logging
8. Testing

To implement and demonstrate these capabilties please feel free to use NuGet packages of your choice. With regards to token based authentication there is no need to connect to (or implement!) a token provider - we're looking for you to show us how you would "do the wiring".

If you can please use ASP.Net Core 8 or later.

A sample address model along with the validation rules can be found in Model/UkAddress.cs.