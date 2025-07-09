# Mini-POS-Billing-App

📦 Mini POS Billing App
💡 Concept
The Mini POS Billing App is a simple, client-side web application designed for small businesses to efficiently manage sales transactions. It allows users to input item details, calculate totals with discounts and taxes, and generate a printable invoice preview.

🔧 Features
Line-item Calculator: Automatically calculates the subtotal for each item based on quantity and price.

Auto-tax and Discount Logic: Apply a global percentage-based discount and tax to the entire bill, with automatic calculation of amounts and final total.

Invoice Preview: Generate a detailed invoice preview with a unique invoice number and the current date.

Receipt Print/Download: Utilize the browser's print functionality to print the invoice or save it as a PDF.

Item Management: Easily add and remove items from the cart.

Input Validation: Basic validation for item inputs to ensure correct data entry.

Responsive Design: Optimized for various screen sizes, ensuring usability on both desktop and mobile devices.

🚀 How to Use
Add Items:

Enter the Item Code (e.g., "SKU001").

Enter the Item Name (e.g., "Product A").

Specify the Quantity (e.g., "2").

Enter the Price per unit (e.g., "100.50").

Click the "Add Item" button.

Repeat for all items.

Manage Items:

Items added will appear in the "Items in Cart" table.

To remove an item, click the "Remove" button next to it.

Apply Discounts and Taxes:

In the "Billing Details" section, enter the Discount (%) you wish to apply (e.g., "10" for 10%).

Enter the Tax (%) rate (e.g., "18" for 18%).

The "Summary" section will automatically update with the calculated subtotal, discount amount, tax amount, and the final total.

Generate Invoice:

Once all items are added and details are correct, click "Generate Invoice Preview".

A full invoice will appear with a unique invoice number and the current date.

Print/Download Receipt:

On the invoice preview screen, click "Print/Download Receipt" to open your browser's print dialog. From there, you can print the receipt or save it as a PDF.

Reset Application:

To clear all items and reset the app to its initial state, click the "Reset App" button.

💻 Technologies Used
HTML5: For the structure of the web application.

CSS3 (Tailwind CSS): For styling and responsive design.

JavaScript (ES6+): For all application logic, including item management, calculations, and UI interactions.
