# Oluseyi Taiwo - QA Portfolio

## About Me

Detail-oriented QA Tester with experience in mobile application testing, exploratory testing, and security validation.


## Skills

- Exploratory Testing
- Functional Testing
- Mobile App Testing (Android)
- Bug Reporting
- Test Case Execution
- Security & OTP Validation


## Sample Bug Report

### Title:-Search Page - Properties gets randomly displayed when selecting Rating : low to high


### Environment:
Android 13 - Redmi Note 11S


### Steps to Reproduce:

1. Open the Booking mobile app
2. Enter Abeokuta in the destination search field.
3. Select valid arrival and departure dates.
4. Tap Search to view available properties.
5. Tap Sort on the results page.
6. Select Property Rating: Low to High

### Actual Result:

After selecting Property Rating: Low to High, properties without any rating are displayed within the sorted list of rated properties. Unrated properties appear between properties that have ratings, resulting in an inconsistent ordering of results and making it difficult for users to clearly assess listings based on rating order.

### Expected Result:

Properties should be listed by rating from Low to High, with no unrated properties mixed in.

### Bug Type:
Functional

### Frequency:
Every time

### priority:
High 

![Image](https://github.com/user-attachments/assets/5a5676f0-ba65-413f-af0e-6660d637aeb1)


https://github.com/user-attachments/assets/45c22f53-3dd4-4d72-8c88-72b38a558a36
