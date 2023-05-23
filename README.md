# HW_1_Git
Here are the results of my first homework on Git.
## 1. [JSON](https://github.com/emcpoh/JSON)
### 1.1. Create an external repository named JSON:
    In browser:
    https://github.com/emcpoh?tab=repositories -> New -> JSON
### 1.2. Clone the JSON repository to the local computer:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/
    $ git clone https://github.com/emcpoh/JSON
    Cloning into 'JSON'...
    remote: Enumerating objects: 3, done.
    remote: Counting objects: 100% (3/3), done.
    remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
    Receiving objects: 100% (3/3), done.
### 1.3. Create a file inside the local JSON repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git
    $ cd JSON/
    touch new.json
### 1.4. Add a file to Git:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git add .
### 1.5. Commit this file:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git commit -m 'new.json was added'
### 1.6. Send the file to an external GitHub repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git push
### 1.7. Edit the contents of the file “new.json” - write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ cat > new.json
    {
    "Full name": "Sergei Kaplienko",
    "Age": 23,
    "Pets quantity": 5,
    "Future desired salary": 75000
    }
### 1.8. Send changes to an external repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git commit -a -m 'Add info about me in new.json'
    git push
### 1.9. Create a preferences.json file:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ touch preferences.json
### 1.10. To the file preferences.json add information about your preferences (Favorite movie, favorite TV series, favorite food, favorite time of year, party you would like to visit) in JSON format:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ cat > preferences.json
    {
    "Fav_movie": "Seven",
    "Fav_TV_series": "Big Bang Theory",
    "Fav_food": "Lahmacun",
    "Fav_season": "Summer",
    "Country_I'd_like_to_visit": "USA"
    }
### 1.11. Create a file skills.json and add information about the skills that will be studied in the course in JSON format:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ cat > skills.json
    {
    "First skill": "Terminal Linux",
    "Second skill": "SQL",
    "Third skill": "Git",
    "Fourth skill": "Postman",
    "Fifth skill": "Client-server architecture",
    "Sixth skill": "Mobile testing"
    }
### 1.12. Send 2 files to an external repository at once:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git add .
    git commit -m 'preferences.json and skills.json are added'
    git push
### 1.13. Create a bug_report.json file on the web interface:
    In browser:
    https://github.com/emcpoh/JSON -> Add file -> Create new file -> bug_report.json
### 1.14. Make Commit changes (save changes) on the web interface:
    Step 1.13 -> Commit new file
### 1.15. Modify the bug_report.json file on the web interface, add a bug report in json format:
    In browser:
    https://github.com/emcpoh/JSON/blob/main/bug_report.json -> Edit this file ->
    {
       "ID":"1234",
       "Summary":"Button not working on checkout page",
       "Environment":{
          "Browser":"Google Chrome",
          "Version":"111.0.5563.147",
          "Operating System":"Windows 11 64-bit"
       },
       "Steps to reproduce":[
          "1. Go to checkout page",
          "2. Click on 'Complete Order' button",
          "3. Nothing happens"
       ],
       "Expected result":"The order should be processed and a confirmation page should appear",
       "Actual result":"Nothing happens when the button is clicked",
       "Attachments":[
          {
             "Type":"Screenshot",
             "URL":"https://example.com/screenshot.png"
          }
       ]
    }
### 1.16. Make Commit changes (save changes) on the web interface:
    In browser:
    Step 1.15 -> Commit changes
### 1.17. Synchronize external and local JSON repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git pull
## 2. [XML](https://github.com/emcpoh/XML)
### 2.1. Create an external repository named XML:
    In browser:
    https://github.com/emcpoh?tab=repositories -> New -> XML
### 2.2. Clone the XML repository to the local computer:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/
    $ git clone https://github.com/emcpoh/XML
    Cloning into 'XML'...
    remote: Enumerating objects: 3, done.
    remote: Counting objects: 100% (3/3), done.
    remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
    Receiving objects: 100% (3/3), done.
### 2.3. Create a file inside the local XML repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git
    $ cd XML/
    touch new.xml
### 2.4. Add a file to Git:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/XML
    $ git add .
### 2.5. Commit this file:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/XML
    $ git commit -m 'new.xml was added'
### 2.6. Send the file to an external GitHub repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/XML
    $ git push
### 2.7. Edit the contents of the file “new.xml” - write information about yourself (full name, age, number of pets, future desired salary). Write everything in XML format:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/XML
    $ cat > new.xml
    <About_me>
            <Full_name>Sergei Kaplienko</Full_name>
            <Age>23</Age>
            <Pets_quantity>5</Pets_quantity>
            <Future_desired_salary>75000</Future_desired_salary>
    </About_me>
### 2.8. Send changes to an external repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/XML
    $ git commit -a -m 'Add info about me in new.xml'
    git push
### 2.9. Create a preferences.xml file:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/XML
    $ touch preferences.xml
### 2.10. To the file preferences.xml add information about your preferences (Favorite movie, favorite TV series, favorite food, favorite time of year, party you would like to visit) in XML format:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/XML
    $ cat > preferences.xml
    <My_preferences>
        <Fav_movie>Seven</Fav_movie>
        <Fav_TV_series>Big Bang Theory</Fav_TV_series>
        <Fav_food>Lahmacun</Fav_food>
        <Fav_season>Summer</Fav_season>
        <Country_I_would_like_to_visit>USA</Country_I_would_like_to_visit>
    </My_preferences>
### 2.11. Create a file skills.xml and add information about the skills that will be studied in the course in XML format:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/XML
    $ cat > skills.xml
    <My_skills>
        <1st_skill>Terminal Linux</1st_skill>
        <2nd_skill>SQL</2nd_skill>
        <3rd_skill>Git</3rd_skill>
        <4th_skill>Postman</4th_skill>
        <5th_skill>Client-server architecture</5th_skill>
        <6th_skill>Mobile testing</6th_skill>
    </My_skills>
### 2.12. Make a one-line commit:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/XML
    $ git add . && git commit -m 'preferences.xml and skills.xml are added'
### 2.13. Send 2 files to an external repository at once:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/XML
    $ git push
### 2.14. Create a bug_report.xml file on the web interface:
    In browser:
    https://github.com/emcpoh/XML -> Add file -> Create new file -> bug_report.xml
### 2.15. Make Commit changes (save changes) on the web interface:
    Step 2.14 -> Commit new file
### 2.16. Modify the bug_report.xml file on the web interface, add a bug report in XML format:
    In browser:
    https://github.com/emcpoh/XML/blob/main/bug_report.xml -> Edit this file ->
    <bug_report>
      <description>When attempting to save changes to a user's profile, an error occurs and the changes are not saved.</description>
      <steps>
        <step1>Log in to the application.</step1>
        <step2>Navigate to the user's profile page.</step2>
        <step3>Edit the user's profile information.</step3>
        <step4>Click the 'Save' button.</step4>
      </steps>
      <expected_result>The changes to the user's profile should be saved successfully.</expected_result>
      <actual_result>An error message appears and the changes are not saved.</actual_result>
      <environment>
        <os_version>Windows 11</os_version>
        <app_version>2.1.1</app_version>
        <language>English</language>
      </environment>
      <additional_info>The error message displayed is 'Unable to save changes to user profile. Please try again later.'</additional_info>
    </bug_report>
### 2.17. Make Commit changes (save changes) on the web interface:
    In browser:
    Step 2.16 -> Commit changes
### 2.18. Synchronize external and local JSON repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git pull
## 3. [TXT](https://github.com/emcpoh/TXT)
### 3.1. Create an external repository named TXT:
    In browser:
    https://github.com/emcpoh?tab=repositories -> New -> TXT
### 3.2. Clone the TXT repository to the local computer:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/
    $ git clone https://github.com/emcpoh/TXT
    Cloning into 'TXT'...
    remote: Enumerating objects: 3, done.
    remote: Counting objects: 100% (3/3), done.
    remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
    Receiving objects: 100% (3/3), done.
### 3.3. Create a file inside the local TXT repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git
    $ cd TXT/
    touch new.txt
### 3.4. Add a file to Git:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/TXT
    $ git add .
### 3.5. Commit this file:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/TXT
    $ git commit -m 'new.txt was added'
### 3.6. Send the file to an external GitHub repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/TXT
    $ git push
### 3.7. Edit the contents of the file “new.txt” - write information about yourself (full name, age, number of pets, future desired salary). Write everything in TXT format:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/TXT
    $ cat > new.txt
    About me:
        My full name - Sergei Kaplienko
        My age - 23 years
        The quantity of my pets is 5. They're all cats.
        My future desired salary - 75000 RUB per month.
### 3.8. Send changes to an external repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/TXT
    $ git commit -a -m 'Add info about me in new.txt'
    git push
### 3.9. Create a preferences.txt file:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/TXT
    $ touch preferences.txt
### 3.10. To the file preferences.txt add information about your preferences (Favorite movie, favorite TV series, favorite food, favorite time of year, party you would like to visit) in TXT format:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/TXT
    $ cat > preferences.txt
    My preferences:
        My favorite movie - Seven, by David Fincher.
        My favourite TV series - Big Bang Theory.
        My favorite food - Lahmacun.
        My favorite season - Summer.
        Country I'd like to visit is USA.
### 3.11. Create a file skills.txt and add information about the skills that will be studied in the course in TXT format:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/TXT
    $ cat > skills.txt
    My skills:
        My 1st skill - Terminal Linux.
        My 2nd skill - SQL.
        My 3rd skill - Git.
        My 4th skill - Postman.
        My 5th skill - Client-server architecture.
        My 6th skill - Mobile testing.
### 3.12. Make a one-line commit:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/TXT
    $ git add . && git commit -m 'preferences.txt and skills.txt was added'
### 3.13. Send 2 files to an external repository at once:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/TXT
    $ git push
### 3.14. Create a bug_report.TXT file on the web interface:
    In browser:
    https://github.com/emcpoh/TXT -> Add file -> Create new file -> bug_report.txt
### 3.15. Make Commit changes (save changes) on the web interface:
    Step 3.14 -> Commit new file
### 3.16. Modify the bug_report.txt file on the web interface, add a bug report in TXT format:
    In browser:
    https://github.com/emcpoh/TXT/blob/main/bug_report.txt -> Edit this file ->
    ID: 1234
    Summary: Button not working on checkout page
    Environment:
        Browser: Google Chrome
        Version: 111.0.5563.147
        Operating System: Windows 11 64-bit
    Steps to reproduce:
        1. Go to checkout page
        2. Click on 'Complete Order' button
        3. Nothing happens
    Expected result: The order should be processed and a confirmation page should appear
    Actual result: Nothing happens when the button is clicked
    Attachments:
        Type: Screenshot
        URL: https://example.com/screenshot.png
### 3.17. Make Commit changes (save changes) on the web interface:
    In browser:
    Step 3.16 -> Commit changes
### 3.18. Synchronize external and local JSON repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/TXT
    $ git pull
