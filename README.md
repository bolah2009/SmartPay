# SmartPay ALC 4 Challenge

## ALC 4.0: Phase 1 Challenge - Mobile Web

### Description:

> This challenge is aimed at having you roll up your sleeves and do some real coding practice based on what you’ve learnt from the contents available to you on the Pluralsight platform. The hands-on project will gauge your ability to apply the knowledge you’ve acquired and also challenge you in this learning journey.

#### The objective is to build a SmartPay interface using HTML, CSS and Javascript (Strictly ES6).

- Stage 1 of 4 (Build & Style The UI)

Build the HTML structure of the credit card component and a button that allows a user to make payment and style the app to improve the look and feel using CSS.

Screenshot of stage 1

![Stage 1 of 4](https://user-images.githubusercontent.com/36057474/62360214-384a2c00-b510-11e9-830f-ecf148e0f8d7.png)

For more details about stage one, see [PR #1](https://github.com/bolah2009/SmartPay/pull/1)

- Stage 2 of 4 (Get Total Bill )

Get Total Bill using the fetch API to make HTTP request, buyer data is fetched from an API endpoint, summed up using 'reduce' and formatted into buyer country currency using 'toLocaleString' and the formatted data is displayed appropriately using the 'querySelector'

Screenshot of stage 2

![Stage 2 of 4](https://user-images.githubusercontent.com/36057474/62460218-4ea6f080-b779-11e9-9c5b-0122d983f5e8.png)

For more details about stage two, see [PR #2](https://github.com/bolah2009/SmartPay/pull/2)

- Stage 3 of 4 (Handle simple validation)

Handle simple validation using `.classList`, the card holder's name and expiry date are validated by adding or removing `invalid` CSS class to mark the field as invalid or not.

Screenshot of stage 3

|                                                           Valid                                                            |                                                           Invalid                                                            |
| :------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: |
| ![valid step 3 of 4](https://user-images.githubusercontent.com/36057474/62462798-325a8200-b780-11e9-9571-85aaea80a348.png) | ![invalid step 3 0f 4](https://user-images.githubusercontent.com/36057474/62462799-325a8200-b780-11e9-969e-1e00b189b0e3.png) |

##### Validations:

- The card's expiry date field should be in the _MM/YY_ format. with _YY_ a being future value (Value greater than the present year)
- The card's holder name field should be 2 names separated by space. Each name should be at least 3 characters long.

For more details about stage three, see [PR #3](https://github.com/bolah2009/SmartPay/pull/3)

- Stage 4 of 4 (Validate Payment Details)

Implement smart typing by displaying temporarily for half a second as the user types and disallow invalid entries (non-integers) in the four-card number fields. Displays a Visa or MasterCard logo depending on the card number entered and Implement the The Luhn Algorithm to validate 16-digit credit card numbers

Screenshot of stage 4

|                                                         Valid Card Number                                                         |                                                     Invalid Card Number                                                      |
| :-------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: |
|  ![valid visa step 4 of 4](https://user-images.githubusercontent.com/36057474/62469746-d51afc80-b790-11e9-9b70-ca22f823ac77.gif)  |    ![invalid visa](https://user-images.githubusercontent.com/36057474/62469741-d4826600-b790-11e9-9e86-f173b74227c5.png)     |
| ![valid master step 4 of 4](https://user-images.githubusercontent.com/36057474/62469745-d51afc80-b790-11e9-9466-13c403c846fa.gif) | ![invalid master card](https://user-images.githubusercontent.com/36057474/62469744-d4826600-b790-11e9-99de-d2b1a5fcbe30.png) |

##### Validations:

- Disallow non-integers
- Uses Luhn Algorithm to validate 16-digit credit card numbers

For more details about stage four, see [PR #4](https://github.com/bolah2009/SmartPay/pull/4)

---

#### Author

- [@bolah2009](https://github.com/bolah2009/)

#### Contact

- [Web](https://bolabuari.com/) - [Twitter](https://twitter.com/bolah2009) - [GitHub](https://github.com/bolah2009/) - [GitLab](https://gitlab.com/bolah2009/) - [LinkedIn](https://www.linkedin.com/in/bolah2009/)
