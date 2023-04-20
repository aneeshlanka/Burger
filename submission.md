<table><tr><td> <em>Assignment: </em> IS601 - Mini Project 2 - Burgers</td></tr>
<tr><td> <em>Student: </em> Aneesh Lanka (al762)</td></tr>
<tr><td> <em>Generated: </em> 4/20/2023 1:40:47 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-004-S23/is601-mini-project-2-burgers/grade/al762" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a new branch per the desired branch name below</li><li>Add the baseline files from the following link:&nbsp;<a href="https://gist.github.com/MattToegel/028db0e3fd2b20c1fb8e284b341292bb">https://gist.github.com/MattToegel/028db0e3fd2b20c1fb8e284b341292bb</a>&nbsp;</li><li>Put them into a subfolder in your repository folder (I called my folder BurgerMachine)</li><li>git add .</li><li>git commit -m "baseline files"</li><li>git push origin (name of desired branch below)</li><li>You can go to github and open the pull request for evidence capturing later (don't close/merge the pull request until you're done with the assignment)</li><li>Do the below tasks and fill in the below entries</li><ol><li>git add/commit after any significant changes to build up history</li></ol><li>Save the input and generate the submission markdown file (copy to clipboard or download the file)</li><li>Name it something relevant to the assignment if it's not named already</li><li>git add the submission file</li><li>git commit the submission file</li><li>git push the submission file</li><li>Complete the pull request to dev</li><li>Create a pull request from dev to prod</li><li>Go to the prod branch on github, navigate to the submission file</li><li>Paste that link to Canvas</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Code Changes - Add the calculate_cost() implementation </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of the updated method calculate_cost()</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113073/228092397-152433e2-bbff-4139-9bad-5ce268439554.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>updated method calculate_cost()<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain the approach to implementing the calculation</td></tr>
<tr><td> <em>Response:</em> <p>The approach to implementing the calculation is to loop through each item in<br>the inprogress_burger array and multiply the price of each item by the quantity<br>to get the total cost of each item. Then, the total cost of<br>each item is added to the total cost of the burger. Finally, the<br>cost of the burger is formatted in currency and outputted to the user.<br>The currency formatting is handled by using the &#39;{:,.2f}&#39; format string to format<br>the total cost in the desired currency format.<br><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Exception Handling </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of adjusted code to handle exceptions</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113073/228093394-cb2e56d3-3002-4170-9684-40914be3fae1.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Adjusted code to handle expections<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113073/228093449-c44558d8-00ac-4790-a918-54c650db6a03.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Adjusted code to handle expections<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113073/228093503-6dd44007-083d-4f75-8201-cc3f153fa0e3.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Adjusted code to handle expections<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113073/228093654-13efc2cd-bcc5-4242-ad89-e61499007243.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Adjusted code to handle expections<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Summarize each exception handling process</td></tr>
<tr><td> <em>Response:</em> <p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;">The OutOfStockException is handled by displaying<br>an error message to the user informing them that the item they selected<br>is out of stock and prompting them to make another selection.&nbsp;</p><p class="MsoNormal" style="margin:<br>0in 0in 8pt; line-height: 16.8667px;">The NeedsCleaningException is handled by asking the user to<br>type "clean" to clean the machine, and then printing a message to indicate<br>whether or not the machine was cleaned.&nbsp;</p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height:<br>16.8667px;">The InvalidChoiceException is handled by displaying an error message to the user informing<br>them that the choice they selected is invalid and prompting them to make<br>another selection.</p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;">The ExceededRemainingChoicesException is handled by<br>displaying an error message to the user informing them that they have exceeded<br>the number of choices allowed and prompting them to move to the next<br>stage.</p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;">&nbsp;Lastly, the InvalidPaymentException is handled by<br>displaying an error message to the user informing them that the payment they<br>entered is invalid and prompting them to enter a valid payment amount.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Test Cases </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Screenshot(s) of test cases per the checklist</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113073/228096320-f4ec0708-d007-4242-9a87-22ae1000010f.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of test 1 and 2<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113073/228095271-287763f8-1a70-43f0-9e4d-721e5ec7cf80.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of test 3 and 4<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113073/228095384-a0994830-2649-4052-a8d0-5c80218d2b64.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of test 5 and 6<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113073/228095547-e9834cbe-a5ff-451f-80bd-6085e142af81.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of test 7<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113073/228095681-779abf46-96f6-46f2-9f6c-325616e96d34.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Screenshot of test 8<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Summarize each test case logic</td></tr>
<tr><td> <em>Response:</em> <p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;"><font face="Calibri, sans-serif"><span style="font-size: 14.6667px;">Test 1<br>- ensures that a bun selection is required before adding patties and toppings.&nbsp;</span></font></p><p<br>class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;"><font face="Calibri, sans-serif"><span style="font-size: 14.6667px;">Test&nbsp;</span></font><span style="font-size: 14.6667px;<br>font-family: Calibri, sans-serif;">2 - ensures that patties can only be added if they<br>are in stock.&nbsp;</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;"><span style="font-size: 14.6667px; font-family:<br>Calibri, sans-serif;">Test 3 - ensures that toppings can only be added if they<br>are in stock.&nbsp;</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;"><span style="font-size: 14.6667px; font-family:<br>Calibri, sans-serif;">Test 4 - ensures that up to 3 patties of any combination<br>can be added.&nbsp;</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;"><span style="font-size: 14.6667px; font-family:<br>Calibri, sans-serif;">Test 5 - ensures that up to 3 toppings of any combination<br>can be added.&nbsp;</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;"><span style="font-family: Calibri, sans-serif;<br>font-size: 14.6667px;">&nbsp;Test 6 - ensures that the cost must be calculated properly based<br>on the choices.&nbsp;</span></p><p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;"><span style="font-size: 14.6667px; font-family:<br>Calibri, sans-serif;">Test 7 - ensures that the total sales must be calculated properly.</span></p><p<br>class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;"><span style="font-family: Calibri, sans-serif; font-size: 14.6667px;">Test 8<br>- ensures that the total burgers should properly increment for each purchase.</span></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add pull request for the assignment</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/aneeshlanka/IS601/pull/10">https://github.com/aneeshlanka/IS601/pull/10</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain any issues/difficulties or something you learned while doing this assignment</td></tr>
<tr><td> <em>Response:</em> <p class="MsoNormal" style="margin: 0in 0in 8pt; line-height: 16.8667px;">I have learned a lot while<br>doing this assignment. I have learned to create multiple test cases to thoroughly<br>test a program. I have also learned how to create pull requests on<br>GitHub. Additionally, I have gained a better understanding of how to debug code<br>and identify errors. One difficulty I encountered was understanding how to use the<br>pytest library to write test cases. However, I eventually learned how to use<br>it and was able to complete the assignment.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshots of successful output</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/123113073/228101485-4757a3c7-27b3-4914-aa9a-7b9b9aacf0f1.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>output<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IS601-004-S23/is601-mini-project-2-burgers/grade/al762" target="_blank">Grading</a></td></tr></table>