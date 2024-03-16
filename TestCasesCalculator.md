**Decision table**



***Test cases***

<br>
<hr>
<br>

**TC#ID:** TC#1 <br>
**Req#ID:** Req1 <br>
**Test scenario:** Valid input for price and weight. <br>
**Test case title:** Verify calculator with valid price and valid weight.<br>
**Description:** <br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|5.0|Price field is populated.|
|2\.|Enter provided value in the weight field.|6|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Total price is calculated with provided data and 10% discount should be included.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#2 <br>
**Req#ID:** Req1 <br>
**Test scenario:** Invalid input for price. <br>
**Test case title:** Verify calculator with in-valid price and valid weight.<br>
**Description:** <br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|-4|Price field is populated.|
|2\.|Enter provided value in the weight field.|55|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Value of the price should not be accepted and error message should pop up.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#3 <br>
**Req#ID:** Req1 <br>
**Test scenario:** Invalid input for weight. <br>
**Test case title:** Verify calculator with valid price and invalid weight.<br>
**Description:** <br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|55.2|Price field is populated.|
|2\.|Enter provided value in the weight field.|abc|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Value of the weight should not be accepted and error message should pop up.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#4 <br>
**Req#ID:** Req1 <br>
**Test scenario:** Invalid input for weight. <br>
**Test case title:** Verify calculator with valid price and invalid weight.<br>
**Description:** <br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|35.2|Price field is populated.|
|2\.|Enter provided value in the weight field.|-4|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Value of the weight should not be accepted and error message should pop up.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#5 <br>
**Req#ID:** Req1 <br>
**Test scenario:** Verify 10% discount. <br>
**Test case title:** Verify 10% Price Reduction<br>
**Description:** Verify that the customer receives a 10% price reduction when the price of the goods exceeds 200 euros.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|245|Price field is populated.|
|2\.|Enter provided value in the weight field.|4|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Discount should be included and total price should be reduced by 10%.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#6 <br>
**Req#ID:** Req1 <br>
**Test scenario:** Verify 10% discount. <br>
**Test case title:** Verifying 10% Price Reduction Just Below Threshold<br>
**Description:** Ensure that the system does not apply the price reduction when the price of the goods is just below the threshold of 200 euros.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|199.9|Price field is populated.|
|2\.|Enter provided value in the weight field.|15|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Discount should not be included and total price should not be reduced by 10%|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#7 <br>
**Req#ID:** Req1 <br>
**Test scenario:** Verify 10% discount. <br>
**Test case title:** Verify 10% Price Reduction at Threshold<br>
**Description:** Ensure that the system correctly applies the price reduction when the price of the goods reaches exactly the threshold of 200 euros.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|200|Price field is populated.|
|2\.|Enter provided value in the weight field.|8|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Discount should not be included and total price should not be reduced by 10%|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#8 <br>
**Req#ID:** Req1 <br>
**Test scenario:** Verify 10% discount. <br>
**Test case title:** Verify 10% Price Reduction Just Above Threshold<br>
**Description:** Ensure that the system correctly applies the price reduction when the price of the goods exceeds the threshold of 200 euros.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|200.1|Price field is populated.|
|2\.|Enter provided value in the weight field.|41|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Discount should be included and total price should be reduced by 10%|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#9 <br>
**Req#ID:** Req2 <br>
**Test scenario:** Verifying free delivery. <br>
**Test case title:** Verifying free delivery.<br>
**Description:** <br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|73|Price field is populated.|
|2\.|Enter provided value in the weight field.|3|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Total price should not include price of delivery.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#10 <br>
**Req#ID:** Req2 <br>
**Test scenario:** Verifying free delivery. <br>
**Test case title:** Verify Free Delivery Just Below Weight Threshold<br>
**Description:** Ensure that the system applies free delivery when the total weight of the goods is below the threshold of 5 kilograms.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|87|Price field is populated.|
|2\.|Enter provided value in the weight field.|4.9|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Total price should not include price of delivery.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#11 <br>
**Req#ID:** Req2 <br>
**Test scenario:** Verifying free delivery. <br>
**Test case title:** Verify Free Delivery at Weight Threshold<br>
**Description:** Ensure that the system calculates the delivery cost when the total weight of the goods is 5 kilograms or above.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|64|Price field is populated.|
|2\.|Enter provided value in the weight field.|5|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Total price should include price of delivery.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#12 <br>
**Req#ID:** Req2 <br>
**Test scenario:** Verifying free delivery. <br>
**Test case title:** Verify Delivery Cost Just Above Weight Threshold<br>
**Description:** Ensure that the system calculates the delivery cost when the total weight of the goods exceeds the threshold of 5 kilograms.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|33|Price field is populated.|
|2\.|Enter provided value in the weight field.|5.1|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Total price should include price of delivery.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#13 <br>
**Req#ID:** Req2 <br>
**Test scenario:** Verifying price of delivery. <br>
**Test case title:** Verifying delivery cost using weight larger than 5. <br>
**Description:** Ensure that the system calculates the delivery cost when the total weight of the goods exceeds the threshold of 5 kilograms. Delivery cost is equal to the weight.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|5|Price field is populated.|
|2\.|Enter provided value in the weight field.|15|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Delivery should be equal to sum of price and weight.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#14 <br>
**Req#ID:** Req3 <br>
**Test scenario:** Verifying free delivery with price over 100e. <br>
**Test case title:** Verify Delivery Cost for Price Above Threshold<br>
**Description:** <br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|106|Price field is populated.|
|2\.|Enter provided value in the weight field.|16|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Total price should not include price of delivery.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#15 <br>
**Req#ID:** Req3 <br>
**Test scenario:** Verifying free delivery with price over 100e. <br>
**Test case title:**  Verify Free Delivery for Price Just Below Threshold<br>
**Description:** Ensure that the system calculates the delivery cost when the price of the goods is 100 euros or below of the threshold.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|99.9|Price field is populated.|
|2\.|Enter provided value in the weight field.|50|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Total price should include price of delivery.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#16 <br>
**Req#ID:** Req3 <br>
**Test scenario:** Verifying free delivery with price over 100e. <br>
**Test case title:**  Verify Free Delivery at Price Threshold<br>
**Description:** Ensure that the system calculates the delivery cost when the price of the goods is 100 euros or below of the threshold.  <br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|100|Price field is populated.|
|2\.|Enter provided value in the weight field.|96.6|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Total price should include price of delivery.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#17 <br>
**Req#ID:** Req3 <br>
**Test scenario:** Verifying free delivery with price over 100e. <br>
**Test case title:** Verify Delivery Cost for Price Just Above Threshold<br>
**Description:** Ensure that the system applies free delivery when the price of the goods exceeds the threshold of 100 euros.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|100.1|Price field is populated.|
|2\.|Enter provided value in the weight field.|86|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Total price should not include price of delivery.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#18 <br>
**Req#ID:** Req4 <br>
**Test scenario:** Verifying 3% discount. <br>
**Test case title:** Verify 3% Price Reduction with Credit Card Payment <br>
**Description:** Ensure that the system applies a 3% price reduction when the customer prepays with a credit card.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|100.1|Price field is populated.|
|2\.|Enter provided value in the weight field.|86|Weight field is populated.|
|3\.|Check 'Pay with credit card' checkbox.||Checkbox should be checked.|
|4\.|Click the button ‘Next step’.||Discount should be included and total price should be reduced by 3%.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#19 <br>
**Req#ID:** Req4 <br>
**Test scenario:** Verifying 3% discount. <br>
**Test case title:** Verify 3% Price Reduction with Credit Card Payment leaving price and weight empty.<br>
**Description:** <br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Check 'Pay with credit card' checkbox.||Checkbox should be checked.|
|2\.|Click the button ‘Next step’.||Error message should pop up with the message that fields are empty.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#20 <br>
**Req#ID:** Req4 <br>
**Test scenario:** Verifying 3% discount with delivery. <br>
**Test case title:**  Verify 3% Price Reduction with Credit Card Payment provind price and weight for free delivery.<br>
**Description:** <br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|32|Price field is populated.|
|2\.|Enter provided value in the weight field.|5.6|Weight field is populated.|
|3\.|Check 'Pay with credit card' checkbox.||Checkbox should be checked.|
|4\.|Click the button ‘Next step’.||Discount of 3% should be included and also price of delivery should be included.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#21 <br>
**Req#ID:** Req5 <br>
**Test scenario:** Verifying 15% discount. <br>
**Test case title:**  Verify 15% Price Reduction for Credit Card Payment, Price at Threshold, and Weight Under Limit<br>
**Description:** Ensure that the system applies a 15% price reduction when the price reaches 200 euros, the customer pays with a credit card, and the weight is under 5 kg.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|202|Price field is populated.|
|2\.|Enter provided value in the weight field.|4.3|Weight field is populated.|
|3\.|Check 'Pay with credit card' checkbox.||Checkbox should be checked.|
|4\.|Click the button ‘Next step’.||Discount should be included and total price should be reduced by 15%.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#22 <br>
**Req#ID:** Req5 <br>
**Test scenario:** Verify 0.1 difference. <br>
**Test case title:**  Verify No Price Reduction without Credit Card Payment<br>
**Description:** Ensure that the system does not apply a 15% price reduction when the customer does not pay with a credit card, even if the price reaches 200 euros and the weight is under 5 kg.<br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|32|Price field is populated.|
|2\.|Enter provided value in the weight field.|5.8|Weight field is populated.|
|3\.|Check 'Pay with credit card' checkbox.||Checkbox should be checked.|
|4\.|Click the button ‘Next step’.||13% discount should be included (10% + 3%) and delivery should be included.|

<br>

**Actual result:**
<br>

**Status:**
--------------------------------------------------------------------------------------------------------------------
<br>
<hr>
<br>

**TC#ID:** TC#23 <br>
**Req#ID:** Req5 <br>
**Test scenario:** Verify 0.1 difference. <br>
**Test case title:**  Verify 0.1 difference.<br>
**Description:** <br>
**Precondition:** User has browser opened and is located on page https://exercises.test-design.org/price-calculation/ <br>
**Test steps** 
<br>

||Test Steps|Test Data|Expected Result|
|:-|:-|:-|:-|
|1\.|Enter provided value in the price field.|88.1|Price field is populated.|
|2\.|Enter provided value in the weight field.|50.76|Weight field is populated.|
|3\.|Click the button ‘Next step’.||Total price should not be round number, it should include 1 decimal.|

<br>

**Actual result:**
<br>

**Status:**
