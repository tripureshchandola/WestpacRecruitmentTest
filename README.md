# WestpacRecruitmentTest
This repository has been created for a westpac recruitment test. It contains a postman collection that has a few tests verifying the oxford dictionary api from: https://developer.oxforddictionaries.com/documentation#!/Entries/get_entries_source_lang_word_id

To proceed:
1. Install GIT from https://git-scm.com/downloads
2. Clone this repository, by running `git clone https://github.com/tripureshchandola/WestpacTest.git` on command prompt
or download zip, to access the collection's json file “WestpacTestForOxfordDictionary_Tripuresh.postman_collection.json” 
 
In order to run the tests locally using command line:
1. Install Node.js >= v6 via package manager https://nodejs.org/en/download/
2. After you install Node.js, install Newman from npm globally on your system `npm install -g newman`
3. After installing newman, you can run the collection from command prompt. Make sure you are in the same directory that has collection's JSON file and run command `newman run WestpacTestForOxfordDictionary_Tripuresh.postman_collection.json`
4. You should see the test results and summary. 

Alternatively, in order to run the tests using postman test runner, or to view the test scripts and assertions, follow these steps: 
1. Download postman from https://www.getpostman.com/downloads/
2. Open postman (you might be asked to create a free account, if you dont have already)
3. Use ‘Import’ option from top left corner to import the downloaded collection's json file
4. Now you can view all the tests under the collection, along with the assertions.
5. Click on 'Runner' on the top nav and select the imported collection in the runner window, and click 'Run'
6. This will run the collection for you and display the results.
