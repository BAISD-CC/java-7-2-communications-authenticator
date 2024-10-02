# Communications Security System

We have been having an issue with our communications from ground control to the astronauts being intercepted by our competitors and spies from Agrabah trying to use our technology to make their flying carpets go orbital. To ensure secure communication, we need your help completing the security authentication system.

## Step 1

Complete the `SecurityAuthenticator` class. This class should have one integer array and one method:

- The integer array should be named `valid` and contain the following values:
  - 5658845, 4520125, 7895122, 8777541, 8451277, 1302850, 8080152, 4562555, 5552012, 5050552, 7825877, 1250255, 1005231, 6545231, 3852085, 7576651, 7881200, 4581002

- The method should be named `isValid` and have one integer parameter for the user's input to be validated. The method should take that input and compare it to each of the elements within the `valid` array using a sequential search. If there is a match, `isValid` should return `true`; otherwise, it should return `false`.

## Step 2

Complete the `CommunicationsPanel` class. This class is for the user to interact with. It should do the following things in order:

1. Create a `SecurityAuthenticator` object named `authenticator`.
2. Ask the user to "Enter your security authentication number: " and get the input.
3. Use the `isValid` method from the `authenticator` object to validate whether the number is valid or not:
   - If it is, let the user know "That's a valid security authentication number."
   - If it isn't, let the user know "That's an INVALID security authentication number."
4. Exit the program.

By completing these two steps, you'll help us ensure that sensitive data is kept secure from prying eyes.

Thank you for your help in keeping our communications secure!
