# Conditional Fields for Elementor Form

\=== Conditional Fields for Elementor Form - Display Conditions ===\
Contributors: coolplugins,narinder-singh,satindersingh\
Tags: conditional-logic, dynamic-visibility, elementor-form, form-builder, elementor\
Requires at least: 5.0\
Tested up to: 6.8.1\
Requires PHP: 7.2\
Stable tag: 1.3.18\
License: GPLv2 or later\
License URI: http://www.gnu.org/licenses/gpl-2.0.html\
Elementor tested up to: 3.29.0\
Elementor Pro tested up to: 3.29.0

Add conditions to Elementor form fields to hide or show a form field based on inputs from other fields, using if-else conditional logic.

\== Description ==

[**Conditional Fields for Elementor Form**](https://coolplugins.net/product/conditional-fields-for-elementor-form/?utm_source=cfef_plugin\&utm_medium=readme\&utm_campaign=get_pro\&utm_content=top_description) is an addon that extends the functionality of Elementor forms by allowing you to **show/hide** or **enable/disable** form fields based on user selections or input values using simple conditional logic.&#x20;

{% embed url="https://youtu.be/0Fbueg7DSts" %}

Conditional logic is a way to control what happens next based on certain conditions.&#x20;

**For example,** if someone selects **“Yes”** to a question, additional related fields might appear. If they choose **“No”** those fields stay hidden. This means the form adapts to the user’s responses, making it simpler and more relevant.

[**CHECK PLUGIN DEMO**](https://coolplugins.net/product/conditional-fields-for-elementor-form/?utm_source=cfef_plugin\&utm_medium=readme\&utm_campaign=demo\&utm_content=view_demos)

### Key Features

* [**Show / Hide Fields Conditionally:**](https://coolplugins.net/product/conditional-fields-for-elementor-form/?utm_source=cfef_plugin\&utm_medium=readme\&utm_campaign=demo\&utm_content=show_hide_fields) Easily add conditional logic to show or hide any field within an Elementor form based on values from other fields.&#x20;
* **If / Else Logic:** Use simple "if/else" conditions to control field visibility or state. Just enter the ID of the source field and define what should happen.\
  **Example:**\
  If **query\_type == check-order-status**, show the **“Order ID”** field; otherwise, keep it hidden.
* **Apply Multiple Conditions:** Apply multiple conditions to a form field, and actions will be triggered if all conditions are met, using AND logic.
* **No Validation Errors:** You will not encounter validation errors if a required field is hidden due to a condition.
* **Compatibility with Hello Plus:** The Conditional Fields for Elementor Form plugin is now fully compatible with the Hello Plus plugin. This means you can easily show or hide specific form fields based on user selections in forms built inside Elementor Free.

#### UPGRADE PRO FOR MORE FEATURES

* [**Conditionally Redirect After Submission**](https://coolplugins.net/product/conditional-fields-for-elementor-form/?utm_source=cfef_plugin\&utm_medium=readme\&utm_campaign=demo\&utm_content=conditionally_redirect#conditional-redirect)**:** Conditionally redirect your Elementor form to a specific URL after submission based on met conditions, such as redirecting to URL-1 if condition-1 is true, otherwise to URL-2.
* **Apply Condition on Submit Button:** Easily apply conditional logic to the Elementor form submit button to enable/disable or hide/show it based on user input values. Use this feature to block spam, such as disabling the submit button if illegal words are added in a textarea.
* [**Send Email Conditionally**](https://coolplugins.net/product/conditional-fields-for-elementor-form/?utm_source=cfef_plugin\&utm_medium=readme\&utm_campaign=demo\&utm_content=email_conditionally#conditional-email)**:** Send different emails to various user types based on their inputs in the Elementor form. Design two to three types of emails and send them to users based on conditions matching their inputs.
* **Apply Multiple Conditions (AND / OR Logic):** Apply multiple conditions to form fields using AND/OR logic. This means actions are triggered if ANY or ALL conditions are met.
* **Conditions Triggers / Compare Operators:** Compare field values using various operators such as is equal (==), not equal (!=), greater than (>), less than (<), greater than or equal to (>=), less than or equal to (<=), contains, does not contain, starts with, and ends with, as well as is empty and not empty.

[**Get Pro!**](https://coolplugins.net/product/conditional-fields-for-elementor-form/?utm_source=cfef_plugin\&utm_medium=readme\&utm_campaign=get_pro\&utm_content=get_pro)

### Check Our Other Elementor Addons

* [**Cool FormKit For Elementor Forms**](https://coolplugins.net/cool-formkit-for-elementor-forms/?utm_source=cfef_plugin\&utm_medium=readme\&utm_campaign=get_pro\&utm_content=cfkef_more_plugins)**:** Add advanced fields and features to your Elementor form widget, like **conditional fields**, **range sliders,** **country code,** and **more.**
* [**Country Code For Elementor Form Telephone Field**](https://coolplugins.short.gy/country-code)**:** Guide your visitors to select their country code while entering their mobile number, ensuring accurate and properly formatted data submissions.
* [**Input Masks for Elmentor Form:**](https://wordpress.org/plugins/form-masks-for-elementor/) Implement pre-defined formatting to form fields like **phone numbers**, **credit card details**, **dates**, and more, ensuring data is entered accurately.

\== Installation ==

#### Quick Installation

1. Navigate to **"wp-admin >> Plugins >> Add New"** on your WordPress website, search for **"Conditional Fields for Elementor Form"**, and install and activate this plugin developed by Cool Plugins.
2. Install **"Elementor PRO"** to access this plugin’s features, as the form widget is only available in the Elementor Pro version.
3. Edit a page with Elementor and create a form. In the form fields, you’ll find a conditions tab where you can easily apply conditions.

#### How to Add Conditions to Elementor Form Fields?

**Step 1:**

First, install **"Elementor Pro"**, then install **"Conditional Fields for Elementor Form"**. Since it is an addon for Elementor Pro, Elementor Pro must be installed first.

**Step 2:**

After installing both plugins, edit a page with Elementor where you intend to add a form. Create the form using the Elementor form widget and add the desired fields.

**Step 3:**

Select the field you wish to hide or show based on specific conditions.

* For example, in a contact form, you might want to show the **"Order ID"** field only if the user selects **"Order Status"** in a query-type select/option field, and hide it if **"General Query"** is selected.
* Enable conditions on a field via the **"conditions tab."**
* Choose a display mode, either **hide or show**. For example, if you select **"Show"**, the field remains hidden until the condition is met. Conversely, the **"Hide"** option keeps the field visible until the condition is met. The pro version of this addon adds two more modes: **Enable/Disable**, allowing you to enable or disable an input field based on conditions.
* Create a condition by entering the ID of the field against which you want to compare the value. For example, you might enable a condition on the **"Order ID"** field so it becomes visible if **"query-type = order-status"**.
* You can also apply multiple conditions to a field and link them using an **AND operator**, meaning the field will hide or show if all conditions are met. The pro version also supports an **OR operator**, allowing a field to hide/show if any condition is met.
* Conditions can be compared in several ways, such as **is equal to (==), is not equal to (!=), greater than (>), and less than (<)**. The pro version supports many other comparison conditions like **empty, not empty, contains, does not contain, starts with, ends with**, etc.

**Step 4:**

Save or update the page and see the results and actions!

\== Frequently Asked Questions ==

\= Which operators can I use to compare conditional field values? =

You can trigger conditions on a field by comparing values with several operators:

* **is equal (==), not equal (!=), greater than (>), less than (<)** - These are available in the free version.
* The Pro version supports additional operators: **greater than or equal to (>=), less than or equal to (<=), contains, does not contain, empty, not empty, starts with, ends with**.

\= On which form fields can I apply conditions? =

You can apply conditions on these fields of Elementor form: **text, textarea, email, tel, radio, select, file upload, HTML, and checkbox**.

\= Can I hide/show or disable/enable a form field conditionally? =

In the free version, you can hide or show form fields based on conditional triggers. The Pro version also allows you to enable or disable fields conditionally.

\= How can I apply multiple conditions on Elementor form fields? =

You can add multiple conditions to a form field and trigger them using **AND/OR logic**:

* **AND** means all conditions must be met to trigger an action on that field.
* **OR** logic, which triggers an action if any condition is met, is available in the Pro version of the Conditional Fields For Elementor plugin.

\= Can I conditionally redirect an Elementor form after submission? =

You can conditionally redirect an Elementor form to a specific URL after submission based on user input within form fields.

This feature is available in the Pro version of Conditional Fields For Elementor.

\= Can I enable/disable the form submit button conditionally? =

Yes, you can **conditionally hide/show or enable/disable the submit button of the Elementor form** based on input values from other fields.

**For example**, if a user adds illegal words in a textarea, you can disable the submit button based on that condition. This feature requires activating the Pro version of Conditional Fields For Elementor.

\= How can I implement conditional logic in Elementor Free forms? =\
Use Conditional Fields for Elementor Form to add conditional logic to Hello Plus forms in Elementor Free. This lets you show or hide form fields based on what the user selects without the need of Elementor Pro.

\= How can I report security bugs? =\
You can report security bugs through the Patchstack Vulnerability Disclosure Program. The Patchstack team help validate, triage, and handle any security vulnerabilities. [Report a security vulnerability.](https://patchstack.com/database/vdp/conditional-fields-for-elementor-form)

\== Screenshots ==

1. Conditionally show/hide Elementor form fields.
2. Enable/disable the Elementor form submit button conditionally.
3. How to add conditional logic to an Elementor form.
4. Trigger conditions using multiple comparison operators.
5. Conditionally redirect the form or send an email.

\== Upgrade Notice ==

\== Changelog ==

#### Version 1.3.18 | June 04, 2025

* **Fixed:** All fields visible on load.
* **Fixed:** Submission error when a required field was hidden.

#### Version 1.3.17 | May 21, 2025

* **Fixed:** All fields visible on load.
* **Tested upto:** Elementor Version 3.29.0
* **Tested upto:** Elementor Pro Version 3.29.0

#### Version 1.3.16 | May 16, 2025

* **Improved:** Minor code improvements.

#### Version 1.3.15 | Apr 24, 2025

* **Fixed:** Minor bug fixes and improvements.

#### Version 1.3.14 | Apr 9, 2025

* **Tested upto:** wordpress Version 6.8
* **Improved:** Independent Form Handling.

#### Version 1.3.13 | Apr 5, 2025

* **Fixed:** HTML Field issue.

#### Version 1.3.12 | Apr 1, 2025

* **Added:** Compatibilty with Hello Plus Form.
* **Fixed:** Minor bug fixes and improvements.
* **Improved:** Independent Form Handling.

#### Version 1.3.11 | Mar 21, 2025

* **Tested upto:** Elementor Version 3.28.0
* **Tested upto:** Elementor Pro Version 3.28.0

#### Version 1.3.10 | Feb 11, 2025

* **Minor Textual Changes**

#### Version 1.3.9 | Feb 06, 2025

* **Minor Textual Changes**
* **Fixed:** Field's default value removed when the condition is applied.

#### Version 1.3.8 | Jan 27, 2025

* **Tested upto:** Elementor Version 3.27.1 and Elementor Pro Version 3.27.0
* **Fixed:** Condition not working with elementor Optimization feature.

#### Version 1.3.7 | Dec 18, 2024

* **Tested upto:** Elementor Version 3.26.0

#### Version 1.3.6 | Dec 12, 2024

* **Fixed:** Load text domain issue fixed.
* **Improved:** Compatible with pro elements.

#### Version 1.3.5 | Nov 19, 2024

* **Fixed:** Minor bug fixes and improvements.

#### Version 1.3.4 | Nov 14, 2024

* **Tested upto:** WordPress 6.7 and Elementor Version 3.25.7.

#### Version 1.3.3 | Sep 19, 2024

* **Fixed:** Minor bug fixes and improvements.

#### Version 1.3.2 | Sep 17, 2024

* **Optimization:** General bug fixes and code improvements.

#### Version 1.3.1 | July 04, 2024

* **Added:** Step Field Support For Condition.

#### Version 1.3 | June 17, 2024

* **Added:** Integrated new Dashboard.
* **Fixed:** Data not sent with multiple checkbox.
* **Minor Textual Changes**

#### Version 1.2.6 | May 31, 2024

* **Fixed:** Editor side styles are not working.

#### Version 1.2.5 | May 09, 2024

* **Minor Textual Changes**

#### Version 1.2.4 | May 06, 2024

* **Fixed:** Issue with comparison when quotes are used in text.
* **Fixed:** Required acceptance field not validating properly.
* **Optimization:** General bug fixes and code improvements.

#### Version 1.2.3 | May 01, 2024

* **Fixed:** Issue where default data was sent with form fields.
* **Optimization:** General bug fixes and code improvements.

#### Version 1.2.2 | Mar 27, 2024

* **Fixed:** Conflict issue with multiple checkbox fields.
* **Optimization:** General bug fixes and code improvements.

#### Version 1.2.1 | Mar 18, 2024

* **Added:** Support for conditions on acceptance fields.
* **Optimization:** General bug fixes and code improvements.

#### Version 1.2.0 | Mar 5, 2024

* **Added:** Conditional field support for file upload fields to enhance form customization.
* **Added:** Support for multiple field conditions using the AND operator.
* **Added:** Greater than (>) and less than (<) comparison operators.
* **Added:** Options to show and hide form fields based on conditions.
* **Added:** Dynamic tags to simplify usage without needing copy and paste.
* **Fixed:** Form now correctly sends values even if a required condition is hidden.
* **Fixed:** Navigator issue.
* **Fixed:** Default value handling when a form field is hidden.
* **Optimization:** General bug fixes and code improvements.

#### Version 1.1.0 | Jan 24, 2024

* **Added:** Conditional field support for HTML fields, enhancing form versatility.
* **Added:** Review notice for user feedback.
* **Fixed:** Form now correctly sends values even if the condition is active but no selection is made.
* **Fixed:** JSON object creation now handled properly, avoiding empty JSON objects.
* **Fixed:** Change trigger code improved for seamless integration.
* **Fixed:** Value trimming functionality improved to prevent issues with spaces.
* **Optimization:** Removed unnecessary AI-generated text.

#### Version 1.0.1 | Jan 9, 2024

* **Minor Textual Changes**

#### Version 1.0.0 | Jan 3, 2024

* **Initial Release**
