# Testing Project for www.eMAG.ro
    
    The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application
    
    Application under test: www.eMAG.ro
    
    Tools used: Jira, Zephyr Squad.

## Functional specifications:
    The below stories were created in Jira and describes the functional specifications of the "nume_modul" module, for which the final project is performed upon.
    
      1. BMTT-1 "Testing the functionality of sections "Produse", "Oferta Zilei", "Ofertele eMAG" and search button “Începe o nouă căutare”, as a NON-REGISTERED USER.
      2. BMTT-2 "Testing the functionality of sections "Produse", "Oferta Zilei", "Ofertele eMAG" and search button “Începe o nouă căutare” as a REGISTERED USER.
![BMTT2](https://github.com/bmarcel20/Testare-Manuala-eMAG/assets/157144973/90915970-a3b7-46c6-b592-9627e3266d27)
![BMTT1](https://github.com/bmarcel20/Testare-Manuala-eMAG/assets/157144973/251b7c8e-3f90-41e7-a648-21a8c1a58384)


Here you can find the release that was created for this project:
![Release test eMAG](https://github.com/bmarcel20/Testare-Manuala-eMAG/assets/157144973/94295f24-d9d1-48af-afae-9b3a37075208)


## Testing process
    The test process was performed based on the standard test process as described below.

### 1.1 Test planning
    The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.
    
    The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (inserati link catre documentul cu planul de testare)

#### 1.1.1. Roles asigned to the project and persons allocated

      Project manager - MOLDOVAN STEFAN
      Product owner -  MUNTEAN MARIUS
      Software developer - POP IOAN 
      QA Engineer - BOROTA MARCEL GHITA IONEL

#### 1.1.2 Entry criteria defined

      1."PC Desktop / Laptop"
      2.Operating Sistem "Windows 10 Home".
      3.web browser "Google Chrome (Version 122.0.6261.95)"
      4.The user should have access to the website www.eMAG.ro
      5.The user should be logged in with the existing user credentials email “borotamarcel@yahoo.com” and password “SM209279a”.

#### 1.1.3 Exit criteria defined

      1. Stability and Performance:
         - The web page should be stable and function without major errors or crashes.
         - Page load time should be under 3 seconds for each page.
      
      2. Browser Compatibility:
         - The web page should be compatible with the latest versions of Google Chrome, Mozilla Firefox, and Microsoft Edge.
         - User interface should display and function properly on the latest versions of mobile browsers.
      
      3. Security:
         - The web page should be protected against known security vulnerabilities such as SQL injections and XSS.
         - All HTTP requests should be encrypted using HTTPS.
      
      4. Web Standards Compliance:
         - The web page should follow the latest HTML and CSS standards, ensuring it's built using modern web technologies.
         - The website should be accessible to people with disabilities, meeting the accessibility requirements.
      
      5. Functionality:
         - All key functionalities such as the contact form and search functionality should work as per specifications.
         - Internal and external links should lead to the correct destination and be valid.

#### 1.1.4 Test scope
    Tests in scope:
    
      1).Testing the functionality of the sections, "Incepe o noua cautare", Produse”, “Oferta Zilei” și “Ofertele eMAG” for a eMAG Registered user and a Non-registered user. 
      2).Testing the functionality of the buttons “Contul meu”, “Coșul meu” and “Favorite’.


    Tests not in scope:
    
      1.Testing the functionalities of the sections: "Genius Deals", "Genius", "Rabla", "Cardul cu milioane de idei" and "eMAG Help".
      2.Testing the functionalities of the sections above via Mobile App "eMAG".

#### 1.1.5 Risks detected
    Project risks:
      1.Low Budget risk.
      2.New team members.
      3.Lack of communication between teams.
      4.Hardware not corresponding to software testing needs 
    
    Product risks:
      1. Product not corresponding to clints needs.
      2. Website not User-friednly/ too complicated for the client.
      3. Functionality problems.

#### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control


### 1.3 Test Analysis

    The testing process will be executed based on the application requirements. (The requirements analysis has been done in order to implement the early testing test principle and the results can be found here 
    
    The following test conditions were found:


### 1.4 Test Design
    Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here (inserati linkul catre fisierul cu testele, in format pdf, word sau csv)

### 1.5 Test Implementation
    The following elements are needed to be ready before the test execution phase begins:
      Test Plan: 
      Test Cases: 
      Test Environment:
      Testing Tools: 
      Test Documentation: 
      Resource Allocation: 
      Communication Channels: 
      Approval and Sign-off: 

### 1.6. Test Execution
    Test cases are executed on the created test Cycle summary: (Ad hoc)

    Bugs have been created based on the failed tests. The complete bug reports can be found here: 
    The following is a summary of the bugs that have been found 
      1. BMTT-14- "Searching the specific product "LENOVO LEGION 5" using directly the search button "Începe o nouă căutare" returns not only this product but other product brands too."
      2. BMTT-13 -"Website does not return specific error for user connecting with unexisting E-mail adress credentials on website "www.eMAG.ro"."

    Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

    The traceability matrix was generated and can be found here: 
    
    Test execution chart was generated and can be found below.


    The final report shows that a number 2 tests have failed of a total of 22
      Total executed:22

    A number of 2 total bugs were found, from which the priority is: both are medium.
      1. BMTT-14- "Searching the specific product "LENOVO LEGION 5" using directly the search button "Începe o nouă căutare" returns not only this product but other product brands too."
      2. BMTT-13 -"Website does not return specific error for user connecting with unexisting E-mail adress credentials on website "www.eMAG.ro"."

      In total a number of 11 testcases were created, 5 for testing the story BMTT-1 and 6 for the story BMTT-2, all considered to be medium priority. After the execution of the 11 testcases, a number of 2 bugs where identified, BMTT-13 ans BMTT-14, both considered to be medium priority. All the 11 test cases created covered 100% the initial scope that they were created.  It is important to note that these bugs, while rated as medium risk, do not appear to have a significant impact on the overall functionality of the application. However, they might affect the user experience to some extent or create minor inconveniences in certain usage scenarios. Accordingly, we recommend fixing these bugs in a future patch or app update to ensure the smoothest and most reliable experience for users. Also, retesting and regression testing will be done after fixing the defects.
