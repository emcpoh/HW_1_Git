# HW_1_Git
Here are the results of my first homework on Git.
## JSON
### 1. Create an external repository named JSON:
    In browser:
    https://github.com/emcpoh?tab=repositories -> New -> JSON
### 2. Clone the JSON repository to the local computer:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/
    $ git clone https://github.com/emcpoh/JSON
    Cloning into 'JSON'...
    remote: Enumerating objects: 3, done.
    remote: Counting objects: 100% (3/3), done.
    remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
    Receiving objects: 100% (3/3), done.
### 3. Create a file inside the local JSON repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git
    $ cd JSON/
    touch new.json
### 4. Add a file to Git:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git add .
### 5. Commit this file:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git commit -m 'new.json was added'
### 6. Send the file to an external GitHub repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git push
### 7. Edit the contents of the file “new.json” - write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ cat > new.json
    {
    "Full name": "Sergei Kaplienko",
    "Age": 23,
    "Pets quantity": 5,
    "Future desired salary": 75000
    }
### 8. Send changes to an external repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git commit -a -m 'Add info about me in new.json'
    git push
### 9. Create a preferences.json file:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ touch preferences.json
### 10. To the file preferences.json add information about your preferences (Favorite movie, favorite TV series, favorite food, favorite time of year, party you would like to visit) in JSON format:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ cat > preferences.json
    {
    "Fav_movie": "Seven",
    "Fav_TV_series": "Big Bang Theory",
    "Fav_food": "Lahmacun",
    "Fav_season": "Summer",
    "Country_I'd_like_to_visit": "USA"
    }
### 11. Create a file skills.json and add information about the skills that will be studied in the course in JSON format:
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
### 12. Send 2 files to an external repository at once:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git add .
    git commit -m 'preferences.json and skills.json are added'
    git push
### 13. Create a bug_report.json file on the web interface:
    In browser:
    https://github.com/emcpoh/JSON -> Add file -> Create new file -> bug_report.json
### 14. Make Commit changes (save changes) on the web interface:
    Step 13 -> Commit new file
### 15. Modify the bug_report.json file on the web interface, add a bug report in json format:
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
### 16. Make Commit changes (save changes) on the web interface:
    In browser:
    Step 15 -> Commit changes
### 17. Synchronize external and local JSON repository:
    kapli@mcpoh MINGW64 ~/Desktop/QA/Git/JSON
    $ git pull
