# **Magento 2 Call for Price Extension**

The **Magento 2 Call for Price extension** by Meetanshi offers a flexible solution for merchants to manage product pricing visibility. This extension is ideal for businesses dealing with fluctuating prices, exclusive products or wholesale pricing. It allows store owners to replace the “Add to Cart” button with a “Call for Price” option, encouraging customers to inquire about prices directly, fostering personalized interaction and negotiation.

## **How It Works**

The **Magento 2 Call for Price extension** hides the product price and replaces it with a customizable “Call for Price” button. Customers can click the button to contact the store owner via an inquiry form, enabling a direct communication channel to discuss pricing or product details.

## **Key Features**

* Enable the "Call for Price" feature for specific customer groups.  
* Choose between a button or a label to display the "Call for Price" option.  
* Automatically send a reply email to customers after they submit a quote inquiry.

## **Hide Prices for Select Products or Categories**

This feature allows you to hide product prices with precision by enabling the “Call for Price” option for specific products, categories, customer groups or store views, providing flexibility and targeted usage.

## **Customizable Inquiry Form**

The integrated inquiry form streamlines customer interactions by allowing them to easily submit their details, such as name, email and phone number, while automatically notifying the admin of each inquiry.

## **Multi-Store and Multi-Language Support**

Designed for global businesses, the extension supports multiple stores and languages, allowing you to customize the “Call for Price” button for each store view and translate inquiry forms to enhance the customer experience.

## **Advanced Admin Control**

The extension offers comprehensive backend settings, enabling you to manage and customize features effectively, view and handle customer inquiries directly from the admin panel and export inquiry details for record-keeping or analysis.

## **Extension Installation**

To install the **Magento 2 Call for Price** extension:

### **Step 1:** 

Extract the ZIP folder and upload the extension to the root directory of your Magento 2 installation using FTP.

### **Step 2:**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush 

**Note:** Ensure you install the Twilio library, even if you are not using the Twilio SMS gateway with our extension.

## **How to Configure Magento 2 Call for Price**

### **Step 1: SMS Gateway Registration**

To send "Call for Price" SMS notifications, register with either Msg91 or Twilio to configure the SMS gateway and obtain the necessary credentials.

### **Step 2: Configure Settings**

To configure the extension, log in to Magento 2 and navigate to **Stores \> Configuration \> Meetanshi \> Call for Price**, where you can adjust various settings to enable the extension.

![Configure Settings](https://github.com/user-attachments/assets/c631ded6-6151-471d-9a6d-858aad11ac1a)

* **Call for Price**: Enable or disable the Call for Price extension.  
* **Notification Type**: Choose the type of notification to send:  
  * **Email**: Sends email notifications to both admin and customers.  
  * **SMS**: Sends SMS/WhatsApp notifications to both admin and customers.  
* **Call for Price Scope**: Select the scope to apply the extension:  
  * **Global**: Enables Call for Price on all products across the store.  
  * **Category Specific**: Enables Call for Price for selected categories.  
  * **Product Specific**: Enables Call for Price for selected products.  
* **Select Categories**: Choose the categories to enable Call for Price when Category Specific scope is selected.  
* **Enable Call for Price As**: Select between a button or a label to display as Call for Price on the frontend.  
  * **Button**: Displays a button that opens a form to submit inquiries.  
  * **Label**: Displays a text label in place of the "Add to Cart" button.  
* **Button Text**: Customize the text for the Call for Price button if using the button option.  
* **Label Text**: Customize the text for the Call for Price label if using the label option.  
* **Label Text Color**: Set the color for the label text on the frontend.  
* **Enable Call for Price for Selected Group**: Choose "Yes" to enable Call for Price for specific customer groups.  
* **Select Customer Groups**: Select the customer groups for which Call for Price will be enabled.  
* **Call for Price Form Title**: Set a custom title for the Call for Price inquiry form.

### **Step 3: Configure Admin Email Settings**

The extension allows you to send "Call for Price" email notifications to both the admin and customers. If you have selected "Email" as the Notification Type, configure the following settings to ensure the admin receives email notifications when a new "Call for Price" inquiry is submitted:

![Configure Admin Email Settings](https://github.com/user-attachments/assets/87a7caab-8d02-482f-b7ec-1a50c15b1127)

* **Admin Email ID**: Enter the admin email address to receive new inquiry notifications.  
* **Email Sender**: Choose the email sender for the notifications.  
* **Email Template**: Select the email template to be used for the notifications.

### **Step 4: Configure Auto Reply Email Settings**

In addition to admin notifications, you can send an auto-reply email to customers after they submit a "Call for Price" inquiry. If you have selected "Email" as the notification type, configure the following settings to enable auto-reply notifications:

![Configure Auto Reply Email Settings](https://github.com/user-attachments/assets/bdf5f434-e4ef-4c2e-b6c7-cadeb9f84ab7)

* **Auto Reply Email to Customer**: Enable this option to send an auto-reply email to customers.  
* **Email Sender**: Choose the email sender for the auto-reply email.  
* **Email Template**: Select the email template to use for the auto-reply notification.

### **Step 5: Configure Admin SMS Notification Settings**

The extension allows you to send "Call for Price" SMS notifications to both the admin and customers. If you have selected "SMS" as the notification type, configure the following settings to ensure the admin receives SMS alerts when a new inquiry is submitted:

![Configure Admin SMS Notification Settings](https://github.com/user-attachments/assets/4e4de3db-4ef5-4ad3-a623-f205d40c12ed)

* **Message Format**: Enter the SMS text format for the notification that will be sent to the admin upon a new "Call for Price" inquiry submission.  
* **Admin Mobile Number**: Enter the admin's mobile number to receive the SMS notification for new inquiries.

### **Step 6: Manage Auto Reply SMS Settings**

In addition to admin notifications, you can send auto-reply SMS notifications to customers after they submit a "Call for Price" inquiry. If you have selected "SMS" as the notification type, configure the following settings to enable auto-reply SMS notifications:

![Manage Auto Reply SMS Settings](https://github.com/user-attachments/assets/d3b4152a-1b68-46ab-b1ba-55e019997340)

* **Auto Reply SMS to Customer**: Enable this option to send an auto-reply SMS to customers.  
* **Message Format**: Enter the SMS text format for the notification that will be sent to customers after their "Call for Price" inquiry submission.

### **Step 7: Configure Privacy Checkbox Settings**

Enable the privacy checkbox in the "Call for Price" form to ensure compliance with the EU’s GDPR. Configure the following settings:

![Configure Privacy Checkbox Settings](https://github.com/user-attachments/assets/3288f91c-ba1d-492d-8492-40031b6b2ed6)

* **Privacy Checkbox**: Enable this option to display the privacy checkbox in the "Call for Price" form.  
* **Privacy Notice Text**: Enter the text for your privacy policy.  
* **Privacy Policy Redirection Page**: Select the page to which users will be redirected when they click the privacy policy text.

### **Step 8: Manage Google reCAPTCHA Settings**

The "Call for Price" extension allows you to enable Google reCAPTCHA v3 in the popup form to prevent spammy inquiries. Configure the following settings to activate it:

![Manage Google reCAPTCHA Settings](https://github.com/user-attachments/assets/32ae6595-7e33-42c6-8c5d-28461fe91e6b)

* **Google reCAPTCHA**: Enable this option to add Google reCAPTCHA to the "Call for Price" form.  
* **Site Key**: Enter the site key obtained during Google reCAPTCHA v3 registration.  
* **Secret Key**: Enter the secret key obtained during Google reCAPTCHA v3 registration.

### **Step 9: Configure SMS API Settings**

If you have selected "SMS" as the notification type, configure the SMS gateway API to send SMS notifications to both the admin and users for "Call for Price" inquiries.

![Configure SMS API Settings](https://github.com/user-attachments/assets/a8426390-b899-44dc-a650-89c0f5551d15)

**Configure API Provider**: Choose your preferred SMS gateway API provider to send SMS notifications:

* Msg91  
  * Textlocal  
  * Twilio  
  * Twilio WhatsApp  
  * Other  
* **Sender ID**: Enter the sender ID provided by your SMS gateway during registration.  
* **Message Type**: Select the type of message to be sent for the "Call for Price" SMS notification.  
* **API URL**: Enter the API URL provided by your SMS gateway during registration.  
* **Authorization Key**: Enter the API key provided by your SMS gateway during registration.

**For Other SMS APIs:** If you are using a custom SMS API other than Msg91, Twilio, or Textlocal, you will need to add your CURL URL as follows:  

![SMS APIs](https://github.com/user-attachments/assets/41a43510-f2f6-477d-bca4-4984ad7ae74a)

* **Format:** https://yoursmsapi.com/sms/submitsms.jsp?user=yourusername\&senderid=yoursenderid\&key=yoursmskey\&mobile={mobile}\&message={msg}

* **Sample CURL URL:**  
  https://foxxsms.com/sms/submitsms.jsp?user=METANSHI\&senderid=FOXGLV\&accusage=6\&key=587e05afbcXX\&mobile={mobile}\&message={msg}

### **Step 10: Manage Product-Specific Call for Price**

You can enable the "Call for Price" functionality for specific products. If you have selected **Product Specific** under Call for Price Scope, follow these steps:

![Manage Product-Specific Call for Price](https://github.com/user-attachments/assets/fae1f31f-1023-4c0c-9b42-3999613d72a5)

1. Go to **Catalog \> Products**, select the product you want to edit.  
2. In the **Call for Price** tab, enable the "Call for Price" option.  
3. If you chose to display the "Call for Price" as a button, enter the custom button text. If you opted for a label, enter the label text instead.  
4. Save the configuration to apply the "Call for Price" option to that product.

Repeat this process for any other products you want to enable the "Call for Price" option for.

### **Step 11: Check Call for Price on the Frontend**

After configuring the settings, the "Call for Price" button is displayed on the store's frontend.

* **Call for Price on the Category Page**

![Call for Price on the Category Page](https://github.com/user-attachments/assets/c3a74fac-0484-4418-8507-90c98d907900)

The extension allows customers to inquire about prices directly from the category page. If the button type is selected in the configuration, the "Call for Price" button will appear on the category page. Customers can click the button to open the inquiry form and submit their details.

* **Call for Price on the Product Page**

![Call for Price on the Product Page](https://github.com/user-attachments/assets/a61b16df-5859-47d1-848d-e22d9bf74bde)

If "Call for Price" is set as a label, the custom label text will appear on both the category and product pages, allowing users to view the pricing inquiry option. Alternatively, if it is set as a button, users can click it to access the "Call for Price" inquiry form and submit their details.

* **Call for Price Form**

![Call for Price Form](https://github.com/user-attachments/assets/dfd69695-8171-4a1b-8543-7d2532b256a4)

For the "Call for Price" button type, users can easily submit price inquiries from the category or product pages. When clicked, a custom-titled inquiry form opens, prompting users to enter their personal details, provide a quote request message, agree to the privacy policy, and submit their inquiry.

If Google reCAPTCHA v3 is enabled by the admin, a badge appears on the page to help prevent spam submissions, ensuring secure and legitimate inquiries.

* **Call for Price Inquiries**

![Call for Price Inquiries](https://github.com/user-attachments/assets/788228b0-6972-4ed9-ad16-dbed1788f8ab)

When users submit a quote request through the "Call for Price" inquiry form on the frontend, all inquiry details are stored in a dedicated grid titled "Call for Price Inquiries". From this grid, the admin can view and manage all inquiries efficiently.

The admin has the option to select multiple inquiries and delete them using the "Delete" mass action. Additionally, the inquiries can be exported in CSV or XML format for further processing or record-keeping.

* **Call for Price Email Notifications**  
  * **Admin Email Notification for Contact Inquiries**

![Admin Email Notification for Contact Inquiries](https://github.com/user-attachments/assets/2248ffa0-ace3-4eb6-a102-9c141598692f)

When the "Notification Type" is set to "Email", the admin receives an email notification each time a user submits an inquiry through the "Call for Price" form. This ensures the admin is promptly informed of new contact inquiries.

* **Auto-Reply Email to Users**

![Auto-Reply Email to Users](https://github.com/user-attachments/assets/4dce40f1-6104-4fc7-8aa7-e60fad344de0)

When the **"Notification Type"** is set to **"Email"**, users receive an acknowledgment email confirming the successful submission of their "Call for Price" inquiry.

### **Step 12: Check Call for Price on the Frontend**

* **Admin SMS Notification for Contact Inquiries**

![Admin SMS Notification for Contact Inquiries](https://github.com/user-attachments/assets/f3d8d38f-eff8-4b5f-a021-4a5305998b77)

When the **"Notification Type"** is set to **"SMS"**, the admin receives an SMS notification each time a user submits an inquiry through the "Call for Price" form, ensuring prompt updates on new inquiries.

* **Auto-Reply SMS Notification to Users**

![Auto-Reply SMS Notification to Users](https://github.com/user-attachments/assets/3940131b-69b0-4b5d-8f5c-b35e78dc9039)

When the "Notification Type" is set to "SMS", users receive an acknowledgment SMS confirming the successful submission of their "Call for Price" inquiry.

### **Step 13: Check Call for Price on the Frontend**

* **Admin WhatsApp Notification for Contact Inquiries**

![Admin WhatsApp Notification for Contact Inquiries](https://github.com/user-attachments/assets/9cfc0067-91f8-44b7-96d6-6c441eb1ca9a)

If you choose to send "Call for Price" notifications via **WhatsApp**, the admin receives a WhatsApp message each time a user submits an inquiry through the "Call for Price" form, ensuring timely updates on new submissions.

* **Auto-Reply WhatsApp Notification to Users**

![Auto-Reply WhatsApp Notification to Users](https://github.com/user-attachments/assets/81dab7d3-82db-4424-8e66-d0b1afed9d97)

When "Call for Price" notifications are set to be sent via **WhatsApp**, users receive an acknowledgment message on WhatsApp confirming the successful submission of their inquiry.

## Download our [Magento 2 Call for Price](https://meetanshi.com/magento-2-call-for-price.html) Extension
