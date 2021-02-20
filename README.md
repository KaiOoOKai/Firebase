# Firebase
## Authentication
### There are two main categories of Authentication.
#### The first one is called Drop-in authentication solution.
FirebaseUI provides a drop-in auth solution that handles the UI flows for signing in users with email addresses and passwords, phone numbers, and with popular federated identity providers, including Google Sign-In and Facebook Login.

Implementation paths
1. Set up sign-in methods
2. Customize the sign-in UI
3. Use FirebaseUI to perform the sign-in flow

#### The second one is called Firebase SDK Authentication. It includes 
* Email and password based authentication, 
* Federated identity provider integration(Google, Facebook, Twitter, and GitHub accounts.), 
* Phone number authentication, 
* Custom auth system integration(Connect your app's existing sign-in system to the Firebase Authentication SDK and gain access to Firebase Realtime Database and other Firebase services.) and 
* Anonymous auth(Use features that require authentication without requiring users to sign in first by creating temporary anonymous accounts. If the user later chooses to sign up, you can upgrade the anonymous account to a regular account, so the user can continue where they left off.)

Implementation paths
1. Set up sign-in methods
2. Implement UI flows for your sign-in methods
3. Pass the user's credentials to the Firebase Authentication SDK

### Experiment
I'll use the Firebase Authentication SDK to do an experiment. 
