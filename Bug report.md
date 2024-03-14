**Bug reports**<hr>


**1.**

**Summary: Contact Form | Data isn’t passed to server after filling form with valid data.**

**BugID:** AcademyBugs#001

**Type of bug:** Functional

**Steps to reproduce:**

1. Visit page https://academybugs.com/contact-us-form/ .
2. Fill input fields with valid data.
3. Click ‘Send’ button.

**Expected result:** When user fills contact form with valid data and clicks ‘Send’ button that data should be passed to server and message should be displayed that the process was successful.

**Actual result:** When the text field was filled by a user and the ‘Send’ button was clicked, only error message was displayed but data isn’t send to server.

**Environment:** Desktop OperaGX(Version 107.0.5045.37), Desktop Chrome(122.0.6261.111/112) 

**Priority:** Medium

**Severity:** Medium

**Repro rate:** 100%

**Attachment:**

![Slika1](https://github.com/markonrt/QA-Project/assets/95719771/e599bcc9-8c3b-4ecf-bd6d-36dd5b0ec869)
![Slika2](https://github.com/markonrt/QA-Project/assets/95719771/868b6aa6-5811-42e1-a743-be749fca8851)




<hr>





**2.**

**Summary: Cart | Grand Total of the cart isn’t equal to the price of the products that are placed in the cart.**

**BugID:** AcademyBugs#002

**Type of bug:** Functional

**Steps to reproduce:**

1. Visit page https://academybugs.com/contact-us-form/ .
2. Click on ‘Add to cart’ for several products.
3. Press on the appeared green button ‘Checkout now’.

**Expected result:** Grand Total should be equal to summed prices of products that were added to cart.

**Actual result:** Grand Total of the added products isn’t equal to the sum of the products.

**Environment:** Chrome on Xiaomi Mi 12 Lite (Chrome version 122.0.6261.105) 

**Priority:** Medium

**Severity:** High

**Repro rate:** 100%

**Attachment:**
![Slika3](https://github.com/markonrt/QA-Project/assets/95719771/0caf0f07-14b0-4fc1-a045-bfda94bfd3b4)



<hr>





**3.**

**Summary: Cart | Return to store button has spelling mistake.**

**BugID:** AcademyBugs#003

**Type of bug:** Visual

**Steps to reproduce:**

1. Visit page https://academybugs.com/contact-us-form/ .
2. Click on ‘Add to cart’ for several products.
3. Press on the appeared green button ‘Checkout now’.
4. After being redirected to the cart, remove items from cart by clicking ‘X’ button on the left side of the product.

**Expected result:** After removing all the products from the cart blue button should appear with the text ‘RETURN TO STORE’

**Actual result:** When user emptied cart, button is displayed with the text that has spelling mistake ‘RETURN TO STOR	E’.

**Environment:** Any browser 

**Priority:** Low

**Severity:** Low

**Repro rate:** 100%

**Attachment:**
https://drive.google.com/file/d/1jinBPVjy7hvyX8L-aEB258aDgZQkHTfY/view?usp=sharing
<br>
![Slika4](https://github.com/markonrt/QA-Project/assets/95719771/92ead406-8014-43f5-ab00-c38a4b972c04)



<hr>





**4.**

**Summary: Account page | Text isn’t written in English.**

**BugID:** AcademyBugs#004

**Type of bug:** Content

**Steps to reproduce:**

1. Visit page https://academybugs.com/account/ .
2. Navigate to the ‘New user’ section.

**Expected result:** All text should be written in English since it is the main language of the website.

**Actual result:** Text in ‘New user’ section isn’t displayed in English language.

**Environment:** Any browser 

**Priority:** Low

**Severity:** Low

**Repro rate:** 100%

**Attachment:**
<br>
![Slika5](https://github.com/markonrt/QA-Project/assets/95719771/dae59963-768d-484c-bd68-a467e0e23a38)



<hr>





**5.**

**Summary: Anchor Bracelet page | Page is loading infinitely after opening the page.**

**BugID:** AcademyBugs#005

**Type of bug:** Performance

**Steps to reproduce:**

1. Open any product on the page.
2. Open the product on the ‘Hot item’ section named ‘Anchor Bracelet’.

**Expected result:** After opening the product page it should load immediately.

**Actual result:** Spinner is spinning infinitely.

**Environment:** Any browser 

**Priority:** Medium

**Severity:** Medium

**Repro rate:** 100%

**Attachment:**
https://drive.google.com/file/d/1wATjybG203Jc7fVYCmUIEc2Z9_Wb7Flj/view?usp=sharing



<hr>





**6.**

**Summary: Items Page | Page freezes and is unresponsive after selecting currency in dropdown that is not USD.**

**BugID:** AcademyBugs#006

**Type of bug:** Functional

**Steps to reproduce:**

1. Visit url https://academybugs.com/find-bugs/.
2. Select any product.
3. Select any other currency in currency dropdown menu that is not equal to USD.

**Expected result:** Price of every product should have new selected currency and it should be displayed in dropdown menu.

**Actual result:** After changing currency in dropdown menu of any product from USD to any other currency page freezes completely. Also currency is not changed when going through products.

**Environment:** Windows 10 | OperaGX(Version 107.0.5045.37) 

**Priority:** Medium

**Severity:** Medium

**Repro rate:** 100%

**Attachment:**
![bugreport](https://github.com/markonrt/QA-Project/assets/95719771/4fc392de-63ed-4f03-9e22-894eb3a92286)

