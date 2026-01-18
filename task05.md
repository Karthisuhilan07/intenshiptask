# **Task-05: Automation Testing for E-Commerce Demo Website**

### **Objective**

The objective of this task is to analyze an e-commerce demo website and understand how automation testing can be designed using **Playwright**. The task focuses on evaluating user flow, identifying automation-ready areas, and documenting limitations found during testing.

---

### **Tools & Framework**

* Playwright
* Node.js
* Demo Online Shopping Website

**Note:**
No automation scripts were executed in this task. The activity was limited to analysis, observation, and test planning.

---

### **Website Analysis & Manual Review**

The demo website was manually reviewed to understand its structure and behavior. The following observations were recorded:

* Website loads without performance issues
* Product listings are visible with correct details
* Navigation menu works correctly
* Items are displayed but cannot be purchased
* Checkout and payment options are unavailable

As a result, a complete order process could not be tested.

---

### **Observed Constraints**

1. Checkout feature is disabled in the demo environment
2. End-to-end purchase flow is not supported
3. Embedded location/map section fails to render

These are considered demo limitations and not functional defects.

---

### **Proposed Automation Flow (Using Playwright)**

If automation testing were to be implemented, the following workflow would be followed:

1. Launch the demo e-commerce website
2. Validate homepage load and navigation menu
3. Verify product list, images, and prices
4. Check Add to Cart button state
5. Open cart page and validate contents
6. Confirm checkout option is unavailable
7. Validate UI consistency across pages
8. Log demo limitations as informational results

This ensures automation scripts remain stable and meaningful.

---

### **Test Observations**

* Pages load consistently without UI issues
* Product information is displayed correctly
* Navigation between sections works smoothly
* Demo restrictions block checkout testing
* External map component does not load

---

### **Conclusion**

This task enhanced my understanding of how automation testing can be planned even when a website does not allow full transactional testing. Instead of reporting failures, known demo constraints were identified and documented clearly.

Task-05 helped me understand practical testing approaches, test planning, and automation strategy design using **Playwright** in real-world demo environments.
