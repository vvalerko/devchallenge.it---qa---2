Repository includes JSON files with the tests and Bugs.xlsx filt with the bug reports
To run the tests your should set up Postman(https://www.getpostman.com/apps)
After Postman run import JSON files to it(Import as a file)
Click on Runner and select a folder with the test scenarios you want to run:
- Pet creation-updating-deleting.postman_collection.json - Smoke scenario for checking the main functionality
- Create-update a pet with invalid data.postman_collection.json - Negative scenario for checking server response after request with invalid data 
- Pet creation-updating-deleting by unauthorized user.postman_collection.json/Updating-Deleling by another user.postman_collection.json - Negative scenario for checking server response after activities without the rights
- Image uploading.postman_collection.json - Checking uploading images feature
- Delete an order by another user.postman_collection.json - Bonus task for checking major user activity witout rights
Select runing parameters and run the tests
After tests is finished you will able to see test results

For running tests from csenario Image uploading.postman_collection.json you should have test files for uploading(1111.jpg and test.txt)
Unfortunately I did not have time to fully study working exported tests with the files for Postman. To check this tests you should run them separately without runner. For tests "uploads an image by the first user", "uploads an image by another user" and "uploads an image by unauthorized user" you should upload 1111.jpg file on the body tab. For test "uploads not image by the first user" you should upload test.txt file on the body tab and send request.
