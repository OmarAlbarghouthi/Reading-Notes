
# **API Design Best Practices**

### Q1. What does REST stand for? 

**Representational State Transfer**.

### Q2. REST APIs are designed around a ____ . 

 **resource**.

### Q3. What is an identifer of a resource?

refers to the unambiguous reporting of research resources such as genes, organisms, tools, and reagents (such as antibodies). Preferably, authors should provide the full, descriptive name of the resource, its source and a unique identifier.

**ex** : https://adventure-works.com/orders

### Q4. What are the most common HTTP verbs?


- GET
- POST
- PUT
- PATCH
- DELETE

### Q5. What should the URIs be based on?

**URIs** should be based on **nouns**.

### Q6. Give an example of a good URI. 

**ex**: https://blog.hubspot.com/website/application-programming-interface-api

### Q7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

There will be a larg number of small resources for the API, which will result in load on the server

### Q8. What status code does a successful GET request return?

 **HTTP status code 200 (OK)**.

### Q9. What status code does an unsuccessful GET request return?

 **404 (Not Found)**.

### Q10. What status code does a successful POST request return?

 **HTTP status code 201 (Created)**.

### Q11. What status code does a successful DELETE request return?

 **HTTP status code 204 (No Content)**.