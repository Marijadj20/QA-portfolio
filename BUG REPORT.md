**BUG REPORT **

**ID: Cosmetic shop/1**

**Summary:** Sale page, the discounted price of the product “Flamingo hairbrush” is higher than the regular price. \
** Description:** The product “Flamingo hairbrush” shows an action (discounted) price that is greater than its regular price. \
 **Environment:** Desktop, Windows 11, Google Chrome, Version 136

**Precondition:**

**1.** 	The product “Flamingo hairbrush” is available on that page

**2.**  	The product has both a regular price and a discounted price defined

**Steps to Reproduce:**

1. Go to the Sale page

2. Locate the product “Flamingo hairbrush”

3. Compare the displayed regular price and the action price \
** Expected Results:** The action price should be less than the regular price. \
** Actual Results: **The action price is higher than the regular price. The **action price** is listed as **749 RSD**, while the **regular price** is **699 RSD**. Despite being marked as a promotional/discounted price, the action price is actually **50 RSD higher** than the original price. \
** Severity: **Low \
 **Priority: **High

**ID: Cloth shop/1**

**Summary**: Dresses page - Product images load with visible delay (5+ seconds)

**Description: **Dresses page , the product images take significantly longer to load compared to other pages. This issue may discourage users from staying on the page or completing a purchase, as products are not immediately visible.

**Environment:** Desktop, Windows 11, Google Chrome, Version 136

**Steps to Reproduce:**

1.     Click on Womens cloth - dress

2.      Scroll down to the product image gallery on the product detail page.

3. Wait 5 seconds for all images to load.

** **

**Expected Results: **Images should load promptly (within 1-2 seconds), providing a smooth browsing experience.

**Actual Results: **Images take 5+ seconds to load, or appear with a visible delay, even after the rest of the page has fully loaded.

**Severity: **Low to Medium

**Priority: **Medium to High

 

**ID: Cloth shop/2**

**Summary: **Only 800 out of 832 products are displayed on the page, even after scrolling to the bottom.

**Description: **On the Dresses page, the product listing consistently stops at 800 items, although the page indicates there are 832 products in total. The remaining 32 products are never loaded, even after scrolling down or refreshing the page. This issue may be caused by a limitation in pagination or lazy loading logic and results in incomplete product display**. \
 Environment: **Desktop, Windows 11, Google Chrome, Version 136

**Precondition**

1.      The total product count is 832 (as displayed on the page)

2.      User is accessing the page on a stable internet connection

3.      No filters or search criteria are applied

** **

**Steps to Reproduce:**

1.      Open the page Dresses that displays 832 products

2.      Scroll down to load more items


 \
** Expected Results:** All 832 products should be displayed as the user scrolls or navigates through the list.

 \
** Actual Results: **Only 800 products are displayed; the remaining 32 are never loaded**. \
 Severity**: Medium \
** Priority: **Medium

 \