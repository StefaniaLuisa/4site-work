# 4Site Promotions Plugin A/B Testing 
a/b test code for 4Site promotions plugin

To run a 4Site Promotions Plugin A/B test. 

### 3 ENgrid forms need to be created 
1. for Control or Variation A
2. For Test or Varaiton B
3. For Ad_blocker - Bryan built this in - it bypasses visitor's adblockers and shows them the adBlocker version which is the control

### 4 Promotions need to be created. 
1. RAW that runs immediately
2. Control that runs on javascript
3. Test that runs on javascript
4. Ad_blocker also triggered on javascript

When running these tests - it is very important to update the promo to "javascript" instead of immediately. This can be forgotten easily especially when showing the client the working 

