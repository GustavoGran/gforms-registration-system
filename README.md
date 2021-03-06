# gforms-registration-system

Google forms is an awesome tool. It enables you to create simple and very reliable forms for your business and other initiatives.

This project aims to extend google forms into a registration system (of a customer, a vendor, etc) where users can preload previously submited records and update it's values by making another submission. 

In order to do that, we will use html, css and javascript to create some user interfaces to be used as side bars or pop-up alerts

## Some history
In the past I've already tried to solve this problem using only default features of google forms and google data studio. The form user would submit a vendor information on the forms and check data in a google data studio dashboard. To change some field information about a vendor, the user could use the edit link sent by e-mail on form submission or could send another form response using the same vendor name.

The upsides of this approach are very clear. There is no need to write a line of code and maintenance can be easily done by non-developers, as well as adding new features. On the other hand, this approach presents some big user experience downsides.

It can be really hard for users to know which e-mail link to use after submitting 3 or 4 new vendors in a row. The other option would be copy the exact name of the vendor to link with the previous response and copy all fields that you don't want to change. This can be really tricky when it comes to files uploaded by the user and in a commom use scenario the user may have to be switching from 3 to 4 tabs in the browser as well as clicking in a lot of e-mail links that look all the same.

## Objectives
We want to build a simple, nice looking and useful user interface that enables us to:
1. List all customers / vendors previoously submited
2. Edit responses by preloading all current values in form responses
3. Delete responses without having admin access to form responses

## Main features

### Registration of a new customer / vendor

### Edit registry of a current customer / vendor

### Deactivating a current customer / vendor

### Visualizing all customers / vendors registry informations

### Visualizing one customer / vendor registry informations

### References
[Edit Form Responses In Google Forms](https://digitalegghead.com/index.php/2018/03/06/edit-google-form-responses/)