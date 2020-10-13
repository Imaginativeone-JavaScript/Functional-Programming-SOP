Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@Imaginativeone 
Imaginativeone-JavaScript
/
Udemy-Max-Vue-3
1
0
0
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
Udemy-Max-Vue-3
/
SOP.md
 

Spaces

2

Soft wrap
1
# Vue Study: Standard Operating Procedure
2
​
3
## Paper
4
- [ ] Have paper checklist on hand
5
​
6
## Visual Studio Code
7
- [ ] Launch the App
8
- [ ] Tend to the Extension Host if necessary
9
- [ ] Locate Progress on Vue-3-Notes.md
10
​
11
### Git
12
- [ ] Verify VSC Terminal Location
13
  ```git
14
  git status
15
  ```
16
  - [ ] I expect to be on a "Video Branch, navigate to the correct one"
17
  ```git
18
  git branch
19
  ```
20
    - [ ] I expect to see a "Section Branch" and the "main" branch in the list of branches
21
    
22
  ## Workflow
23
  
24
  ### Create a New Section Branch
25
  - git checkout -b <Section Branch>
26
  
27
  ### Create a New Video Branch
28
  - Identify Section Branch
29
  - Use this command (with the format) to create the branch
30
  ```git
31
  git checkout -b VNNN-[This video number][Total videos in this section]-Topic-Name-tMMSS
32
  ```
33
  ```git
34
  git push
35
  ```
36
  - To set the upstream, copy and paste resulting command. For example: 
37
  ```git
38
  git push --set-upstream origin V013-0202-Creating-and-Connecting-Vue-App-Instances-t0840
39
  ```
40
  
41
  ### Update Section Branch
42
  - Verify that Video Branch has been fully saved, added, committed, and pushed
43
  - Copy the Section Branch name to the clipboard if necessary
44
  - git checkout <Section Branch>
45
  - git merge newly completed Video Branch
@Imaginativeone
Commit changes
Commit summary
Update SOP.md
Optional extended description
Add an optional extended description…
 Commit directly to the main branch.
 Create a new branch for this commit and start a pull request. Learn more about pull requests.
 
© 2020 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
