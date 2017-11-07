# CodePathPrework-repo
Gowri Hassan - hassang@purdue.edu

Time spent: 3 hours

Still in progress 

User Stories - 

Required: Setup

 Download and install Burp - Completed
 
 Configure your browser to direct traffic through Burp - Completed
 
 Can successfully view HTTPS traffic in sa - Completed
 
 Register an account at security.shephard.com - Completed
 
 Required: Challenge 1 - HTTP Headers - Completed

 Required: Challenge 2 - Basic Routes 1 - Completed

 Required: Challenge 3 - Query Params 1 - Completed

 Required: Challenge 4 - Insecure Direct Object References (IDOR) - Completed
 
Notes: Experienced some issues configuring the proxies when working on Challenge 5 and was therefore not able to retrieve the result key. 

How to solve Challenge 5:
- Turn on intercept in Burp and go through every user in the Security Shepard's list to find the user ID for the respective users in burp. In burp, right click and click send to intruder. Go to the positions tab and change the user ID that was found initially which was '1' in this scenerio. Go to payloads and add approximately 20 different payloads. Go to the target tab and start the attack. Go to results tab and click the response tab and find the hidden users message which will also provide the results key.
 
License

Copyright [2017] [Gowri Hassan]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

