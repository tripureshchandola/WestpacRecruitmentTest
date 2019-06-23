# WestpacRecruitmentTest
This repository has been created for a westpac recruitment test. It contains a postman collection that has a few tests verifying the oxford dictionary api from: https://developer.oxforddictionaries.com/documentation#!/Entries/get_entries_source_lang_word_id

For complete setup/pre-requisites:
1. Install GIT from https://git-scm.com/downloads
2. Clone the repository, by running `git clone https://github.com/tripureshchandola/WestpacRecruitmentTest.git` on command prompt
or download zip, to access the collection's json file “WestpacTestForOxfordDictionary_Tripuresh.postman_collection.json”
3. Install Node.js >= v6 via package manager https://nodejs.org/en/download/
4. Install Newman from npm globally on your system `npm install -g newman`
5. Download and install postman from https://www.getpostman.com/downloads/ (you might be asked to create a free account, if you dont have already)

In order to run the tests locally using command line: 
1. On comand line, make sure you are in the same directory that has collection's JSON file and run command `newman run WestpacTestForOxfordDictionary_Tripuresh.postman_collection.json`
2. You should see the test results and summary

Alternatively, in order to run the tests using postman test runner, or to view the test scripts and assertions, follow these steps: 
1. Open postman and use ‘Import’ option from top left corner to import the downloaded collection's json file
3. Now you can view all the tests under the collection, along with the assertions.
4. Click on 'Runner' on the top nav and select the imported collection in the runner window, and click 'Run'
5. This will run the collection for you and display the results.
