# MOBILE PROGRAMMING I

1.  Briefly explain the following as used in mobile application development:

        i. widgets
        ii. Content Providers
        ii. Fragments
        iv. Wire frames
        v. Intent filters

2.  Describe the meaning of the term killable states in the context of mobile programming. Give one example ofa killable state

3.  Describe `TWO` differences between Progressive web applications and Hybrid application development

4.  Create an Android XML layout for a login screen with two EditText fields for username and password,and a Button for login.

5.  Create an Android activity that receives a username from the previous activity using an Intent and displays a welcome message.

6.  Provide a brief description on the contents of the following key folders in android studio:

        i. Src
        ii. gen
        iii. bin
        iv. res/vaues
        v. res/layout

7.  Using the android code extract to answer the following questions;

```
private void firebaseAuth With Google(String idToken){
AuthCredential credential = GoogleAuthProvider.getCredential(idToken, null);
mAuth.signlnWithCredential(credential){
    .addOnCompleteListener(this, new OnCompleteListener<AuthResult>(){
    @Override
    public void onComplete(@NonNullTask<AuthResult>task) {
        if (task.isSuccessful()) {
            //Sign-in succesS
            FirebaseUser user =MAuth.getCurrentUser();
            //Update UI with the signed-in user's information
            updateUI(user);
            }else{
            // Sign-in failed
            Log.w(TAG, "signln WithCredential:failure",task.getException());
            Toast.makeText(MainActivity.this, "Authentication failed.",
                Toast.LENGTH SHORT).show():
            updateUI(null);
            }
        }
    });
}
```

i. Explain what the above code achieves

ii. Explain the role of the google-services.json file in a Firebase project? How is it generated and used in an Android application?

iii. Explain the significance of the mAuth object in the provided code. How is it
initialized,and what role does it play in Firebase authentication?

8. Explain the importance of using Kotlin as programming languages for iOS and Android
   development,respectively.

9. Compare SQLite and Shared Preferences for data storage in Android.

10. Explain the difference between Java and Kotlin in the context of Android development.

11. Explain the benefits of integrating Firebase into a mobile application.

12. Write an XML layout for an Android app containing a LinearLayout with two buttons horizontally aligned.

13. Create an Android activity that launches a second activity using an explicit intent. Pass data between the activities

14. What is an Intent in Android? When would you use each type? Provide an example of an explicit and implicit Intent.

15. Explain each of the lines of the following android code extract;

```
GoogleSignlnOptions gso = new
GoogleSignlnOptions. Builder(GoogleSignlnOptions.DEFAULT_SIGN_IN)
    .requestldToken(getString(R.string.default_web_client_id))
    .requestEmail()
    .build();
```

i. What does the above code achieve?

ii. What is the purpose of the requestldToken() method in the GoogleSignlnOptions configuration?

## Additional Questions

16. Describe the Android activity lifecycle and explain the role of each ofthe following
    methods:

            i. onResume()
            ii. onPause()
            iii. onStop()
            iv. onStart()

17. Explain any `FOUR` building blocks of an android application

18. Briefly explain `two` functions of Android Manifest.xml file in Mobile Programming

19. Explain the purpose of the RecyclerView in Android and describe its advantages over ListView.

20. Write a brief code snippet demonstrating how to save instance state in an Android
    activity.

21. Differentiate between the Views and View Groups in Mobile Programming. Cite examples in each case.

22. Elaborate the difference between the android emulator and the actual android device citing the importance in each case.

23. Explain the purpose of the following input controls in the context ofandroid platform. Write a sample XML or java code for defining each term;

        i. Spinner
        ii. Edit Text

24. Describe the purpose `ofoncreate()` method as used in android applications. Write a simple java code that demonstrates its implementation.

25. Discuss the role of Intent Filters in Android development. How do they enable components to receive Intents? Provide a scenario where Intent Filters are used.

26. Explain the purpose of the `onSavelnstanceState()` method and describe a scenario where it is used. Also, explain how you would restore the saved state.
