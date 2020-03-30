This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Author : Ashok Bollikonda

- Api source : https://lamppoststudios.api-us1.com/api/3
- Dependencies : React , axios 
- Testing Framework : Jest

### Assumptions 

- Contact table will always display Location as " Chicago, IL, USA" since api response did not return any location details. 
- Total value in contact table is sum of scoreValues array from api response.
- Contact name would be displyed "John Doe", If the first name & last name are an empty strings.
- Deals value in contact table is taken from "https://lamppoststudios.api-us1.com/api/3/contacts/{id}/deals"
- Tags value in contact table is taken from "https://lamppoststudios.api-us1.com/api/3/contacts/{id}/contactTags"

### Challenge

Tried hosting this application on netlify or sandbox, despite using CORS-ANYWHERE api retuns CORS error.

## Available Scripts

In the project directory, you can run:

### `npm start`
### `npm test`
