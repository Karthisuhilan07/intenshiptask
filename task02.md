***Task-02: Compatibility Testing for Basic Web Page***

**Website Tested**
E-commerce Demo Website (ShopEase)

**Test Environment**

**Browsers Tested**
Mozilla Firefox (Desktop)

**Devices Tested**
Desktop
Tablet (Responsive Mode)

**Overview**
Compatibility testing was performed to verify consistent behavior of the website across different browsers and device views. Testing focused on layout consistency, navigation links, product search, footer sections, and core user actions such as browsing products and adding them to the cart.

---

## **Test Findings**

### **TC_001:**

Verify website behavior on Firefox Desktop

**Expected Result:**
Website should load completely with proper layout and smooth scrolling

**Actual Result:**
Website loads correctly with proper layout and smooth scrolling

**Status:**
**“Pass”**

---

### **TC_002:**

Verify header navigation – Categories menu

**Expected Result:**
Categories menu should display the list of product categories

**Actual Result:**
Categories menu opens but takes longer to respond

**Status:**
**“Fail”**

---

### **TC_003:**

Verify header navigation – Deals menu

**Expected Result:**
Deals menu should redirect to the offers page

**Actual Result:**
Deals menu redirects to a blank page

**Status:**
**“Fail”**

---

### **TC_004:**

Verify header search bar functionality

**Expected Result:**
Search bar should display matching products based on keywords

**Actual Result:**
Search bar accepts input but does not display results

**Status:**
**“Fail”**

---

### **TC_005:**

Verify Add to Cart and checkout functionality

**Expected Result:**
Items should be added to the cart and checkout process should complete successfully

**Actual Result:**
Add to Cart works correctly and checkout completes without errors

**Status:**
**“Pass”**

---

### **TC_006:**

Verify footer navigation links

**Expected Result:**
Footer links such as Privacy Policy, Terms, Support, and Contact should be accessible

**Actual Result:**
Footer links are visible but only some links are clickable

**Status:**
**“Fail”**

---

### **TC_007:**

Verify responsiveness on tablet view

**Expected Result:**
Website should adapt to tablet resolution without layout distortion

**Actual Result:**
Website adjusts correctly with proper spacing and no alignment issues

**Status:**
**“Pass”**

---

## **Issues Identified**

1. Categories menu has delayed response
2. Deals menu redirects to a blank page
3. Search functionality does not return results
4. Some footer links are not clickable

---

## **Recommendations**

* Improve performance and responsiveness of header menus
* Fix broken routing for the Deals page
* Enable functional search result handling
* Ensure all footer links redirect to valid pages
* Extend testing across more browsers and devices

---

## **Conclusion**

The website maintains good layout responsiveness and checkout functionality across desktop and tablet views. However, multiple navigation and search-related issues were identified. Resolving these issues will improve compatibility, usability, and overall user experience.
