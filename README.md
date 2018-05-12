Repository includes JSON files with the tests and Bugs.xlsx filt with the bug reports
To run the tests your should set up Postman(https://www.getpostman.com/apps)
After Postman run import JSON files to it(Import as a file)
Click on Runner and select a folder with the test scenarios you want to run:
- Pet creation-updating-deleting.postman_collection.json - Smoke scenario for checking the main functionality
- Create-update a pet with invalid data.postman_collection.json - Negative scenario for checking server response after request with invalid data 
- Pet creation-updating-deleting by unauthorized user.postman_collection.json/Updating-Deleling by another user.postman_collection.json - Negative scenario for checking server response after activities without the rights
