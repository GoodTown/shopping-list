shopping-list v1

An absolute bare-bones web app.

Installation

Install dart

https://dart.dev/tutorials/web/get-started 


1-Install Dart

choco install dart-sdk

Restart your shell


2-Get CLI tools or an IDE (or both)

dart pub global activate webdev



3-Run the app

cd quickstart
webdev serve


Install flutter


4.pull flutter in a different directory 

git clone https://github.com/flutter/flutter.git -b stable



5.Update your path

From the Start search bar, enter ‘env’ and select Edit environment variables for your account.
Under User variables check if there is an entry called Path:

If the entry exists, append the full path to flutter\bin using ; as a separator from existing values.

If the entry doesn’t exist, create a new user variable named Path with the full path to flutter\bin as its value.


6.Run flutter doctor

flutter doctor


