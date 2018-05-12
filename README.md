Repository includes JSON files with the tests, Bugs.xlsx file with the bug reports, test files and readme file.
To run the tests your should set up Postman(https://www.getpostman.com/apps)
After Postman run import JSON files to it(Import as a file)
Click on Runner and select a folder with the test scenarios you want to run:
- 01.Pet creation-updating-deleting.postman_collection.json - Smoke scenario for checking the main functionality
- 02. Create-update a pet with invalid data.postman_collection.json - Negative scenario for checking server response after request with invalid data 
- 03. Pet creation-updating-deleting by unauthorized user.postman_collection.json/04. Updating-Deleling by another user.postman_collection.json - Negative scenario for checking server response after activities without the rights
- 05. Image uploading.postman_collection.json - Checking uploading images feature
- 06. Delete an order by another user.postman_collection.json - Bonus task for checking major user activity witout rights
Select runing parameters and run the tests
After tests is finished you will able to see test results

For running tests from csenario 05. Image uploading.postman_collection.json you should have test files for uploading(1111.jpg and test.txt)
Unfortunately I did not have time to fully study working exported tests with the files for Postman. To check this tests you should run them separately without runner. For tests "uploads an image by the first user", "uploads an image by another user" and "uploads an image by unauthorized user" you should upload 1111.jpg file on the body tab. For test "uploads not image by the first user" you should upload test.txt file on the body tab and send request.
