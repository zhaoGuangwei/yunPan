
Product name: baidu yunpan client for android
Author: Zhao Guangwei
Student ID: 13126175

Summary
1.1 product introduce
　　Baidu yunpan is an excellent tool for cloud storage. Especially in mobile client, it can upload the photo and video files in synchronization, also telephone book. It can bake up the SMS and call logs.
1.2 scope
　　Upload and download files.
　　Upload the photo and video files in synchronization.
　　Upload the telephone book in synchronization
　　Bake up the SMS
　　Bake up the call logs
1.3 limitation
　　The test plan is limited to content and time submitted by product developers. According to the actual situation of the module submitted by developers, this plan will make the appropriate modifications.
1.4 reference
　　Baidu yun’s manual
2 agreement
2.1 test target
　　Through testing, to achieve the following objectives:
　　Test whether the product has achieved the designed requirements, including whether to implement each function point, the business process is correct.
　　Stable operation and running required by the product.
　　Bug control number and the defect rate is acceptable.
2.2 resource and tool
2.2.1 resource
　　The android client of baidu yun.
2.2.2 tool
　　Bug management tools used in the test is improved bug management tools.
　　Automated testing tools to be determined.
2.4 No. Rules
　　The number of rules associated with the test plan are as follows:
　　The number of test cases,  the function name + interface name + Code
　　For example:  The first use case of “upload file” is: UPLOAD_FILE_001.
　　Test file naming rules of test case, the module name + test.
　　For example: share module is: SHARE_TEST.
Test type and test standards
3.1 test type
　　Plans to complete the following types of tests
　　Functional test
　　Business test
　　Stress test
　　Installation test
　　Acceptance test
3.2 Test methods and standards
3.2.1 Functional test
3.2.1.1 Function
　　System can implement each function of the modules in accordance with the design requirements, the data should be completed, beautiful interface, easy to operate. Specific reference to the test focus of this document and the order section.
3.2.1.2 Interface test
　　Detailed interface test can refer to interface testing related file.
3.2.1.3 Data entry test
　　Alphanumeric data items are correctly echoed, and entered into the system.
　　Graphics mode data items(e.g. sliders) is working properly?
　　Are able to identify illegal data?
　　Whether the data input message comprehensible?
3.2.1.4 Help document test
　　Whether the document is an accurate description of how to use various usage patterns?
　　Describe the interaction order is accurate?
　　Examples are accurate?
　　Terminology, menu descriptions and system response is consistent with the actual program?
　　Are able to easily locate the document guide?
　　Are able to use the document to exclude wrong?
　　Contents and index of documents are accurate and complete?
　　Documents design (layout, indentation, and graphics) are easy to understand?
　　Display an error message to the user if there is a more detailed explanation of the document?
　　If you use the hyperlink, the hyperlink is accurate and complete?
3.2.2 business test
　　Conduct business te	st after the function test is completed, business test is concerned with business process, and the correctness of data streams flowing from one module to another module in the software.
3.2.3 Stress test
3.2.3.1 Stress test description
　　The stress test includes performance tests in accordance with the actual situation, focusing on multi-user tests simulate customers. Stress test has a 8:2 principle. Eighty percent of business volume is input in twenty percent of the time. For example: there are 100 new data normal daily data input 80 test within two hours. We can’t know the volume of business users, so that only the use of existing resources, a large amount of test data.
3.2.3.2 Stress testing tool
　　Pending.
3.2.3.3 Stress test methods and standards
　　Methods of stress tests and standard reference stress test related files.
3.2.4 Installation test
3.2.4.1 installation test description
　　In addition to the embedded software, the installation is the first software product to achieve its function, not properly installed simply mention the correct execution, so for installation testing is particularly important.
3.2.4.2 Testing methods and standards in installation
　　To android application, the installation is easy to complete. Here don’t talk about it. When install it in wins, we should test it carefully.
4 test priority and order
4.1 Predict risk
　　The testing process, the risk may arise as follows:
　　Fix the bug situation
　　Achievement of the module function
　　The achievement of the overall system functions
　　Writing quality of the code 
　　Staff experience and familiarity with the software
　　Developers, testers agreed on the implementation of the project
　　Personnel adjustments resulted in the development cycle delay
　　Shorten development time cause some test plan cann’t be executed
4.2 Test focus
4.2.1 Functional test
　　Here the focus is only described the test, the specific test methods and content, see test case.
4.2.1.1 upload files
　　upload a file properly.
　　Upload many files at the same time.
　　Automatic resume after exception.
4.2.1.2 download files
　　download a file properly.
　　Download many files (or folder) at the same time.
　　Automatic resume after exception.
4.2.1.3 Upload the photo and video files in synchronization
　　Choose the photo folders for synchronization.
　　Take many photos by the camera.
　　Take a video by the camera.
　　Check that the files of photos and videos have been uploaded.
4.2.1.4 back up the SMS
　　hit the button of “SMS backup”, then back up to the cloud.
　　Link the website “http://yun.baidu.com/” in the computer, then hit the button of “SMS”, check that all SMS records uploaded to the cloud.
4.2.1.4 upload the contact list in synchronization
　　hit the button of “contact list synchronization”, then set up it automatically.
　　Add one record in contact list by android phone.
　　Link the website “http://yun.baidu.com/” in the computer, then hit the button of “contact list”, check that the new record uploaded to the cloud.
Testing tasks and schedule
　　Pending.
6 Test submissions
　　After the test is completed submission of materials: 
　　Test plan
　　Test case
　　Test bug sheet
　　Test summary
　　Test analysis report
