# QA-portfolio
Examples of bug reports, test cases, and API tests for Manual QA.

---

## Bug Reports Samples (SauceDemo)

### Bug #1: [UI] Incorrect product images displayed under problem_user

- **Environment:** Windows 11 / Chrome v128 / Resolution: 1920x1080
- **Severity:** Medium
- **Priority:** Medium

**Steps to Reproduce:**
1. Log in as 'problem_user' with password 'secret_sauce'.
2. Observe the main inventory page (/inventory.html).

**Actual Result:** All product items display the same image (a dog picture) instead of their respective product photos.  
**Expected Result:** Each product displays its unique, correct image.

<img width="1912" height="998" alt="image" src="https://github.com/user-attachments/assets/fd3319f6-dedf-4df7-b63e-c556cb5fe3fa" />

---

### Bug #2: [Functional] Product sorting filter does not reorder items

- **Environment:** Windows 11 / Chrome v128 / Resolution: 1920x1080
- **Severity:** Medium
- **Priority:** Medium

**Steps to Reproduce:**
1. Log in as 'problem_user' with password 'secret_sauce'.
2. Click on the product filter dropdown in the top right corner.
3. Select any non-default sorting option (e.g., 'Price (low to high)' or 'Name (Z to A)').

**Actual Result:** The product list remains unchanged and does not sort according to the selected option.  
**Expected Result:** Products are reordered immediately based on the selected sorting criteria.
<img width="1084" height="626" alt="bug functional" src="https://github.com/user-attachments/assets/c428a487-3477-4777-b20f-20963204132e" />

---

### Bug #3: [Functional] Unresponsive "Add to cart" and "Remove" buttons

- **Environment:** Windows 11 / Chrome v128 / Resolution: 1920x1080
- **Severity:** High
- **Priority:** High

**Steps to Reproduce:**
1. Log in as 'problem_user' with password 'secret_sauce'.
2. Click "Add to cart" on the 1st or 2nd item and attempt to click "Remove".
3. Attempt to click "Add to cart" on items #3, #4, or #6.

**Actual Result:** Items #1 and #2 cannot be removed after adding; "Add to cart" buttons for items #3, #4, and #6 do not respond to clicks.  
**Expected Result:** All "Add to cart" buttons add items to the cart, and added items can be successfully removed.

<img width="1084" height="775" alt="bug functional high" src="https://github.com/user-attachments/assets/d1606dd2-be4d-4804-99a2-77dc400799c2" />

