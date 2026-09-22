Team No 9
Assignment No 1

Canteen-Food Ordering

Prompt

Create a clean, accurate, professional 3D-style academic diagram set for a Canteen Food Ordering System based on these five features in exactly this order:

Customer Details Menu Items Order Details Order Status Order Cancellation 

Create THREE separate sections: FLOWCHART, ALGORITHM, and ER DIAGRAM.

PART 1 – FLOWCHART 

Create a proper standard flowchart using correct flowchart symbols:

START/END → Oval
PROCESS → Rectangle
DECISION → Diamond
INPUT/OUTPUT → Parallelogram
FLOW → Arrows

Follow these steps:

START

↓ Enter Customer Details
(Customer ID, Customer Name, Mobile Number, Email, Class/Department)

↓

Validate Customer Details

↓

Display Menu Items
(Item ID, Item Name, Category, Price, Availability)

↓

Select Available Menu Item

↓

Enter Order Details
(Order ID, Customer ID, Item ID, Quantity, Date/Time, Total Amount)

↓

Confirm Order

↓

Set Order Status = PENDING

↓

Check Order

↓

Update Order Status: PENDING → ACCEPTED → PREPARING → READY → COMPLETED

↓

Decision: Does Customer Want to Cancel?

YES → Enter Order ID and Customer ID → Enter Cancellation Reason → Record Cancellation Date/Time → Set Status = CANCELLED → END

NO → Continue Order Processing → Order Completed → END

Make the arrows clear and properly connected. Use no unnecessary steps.


PART 2 – ALGORITHM 

Create a separate step-by-step algorithm with numbered steps.

Algorithm:

Start. Enter Customer ID, Customer Name, Mobile Number, Email, and Class/Department. Validate and store the customer details. Display the available menu items with Item ID, Name, Category, Price, and Availability. Select the required menu item. Enter Order ID, Customer ID, Item ID, Quantity, Date/Time, and Total Amount. Confirm and store the order details. Set the initial Order Status as Pending. Accept the order and change the status to Accepted. Prepare the food and change the status to Preparing. When the food is ready, change the status to Ready. Complete the order and change the status to Completed. If the customer requests cancellation, verify the Order ID and Customer ID. Enter the cancellation reason and cancellation date/time. Change the order status to Cancelled. End. 

Present the algorithm in a clean numbered format with excellent spacing and readability.


PART 3 – ER DIAGRAM 

Create a proper ER (Entity-Relationship) Diagram for the same Canteen Food Ordering System.

Use these entities:

CUSTOMER

Customer_ID (PK) Customer_Name Mobile Email Class/Department 

MENU_ITEM

Item_ID (PK) Item_Name Category Price Availability 

ORDER

Order_ID (PK) Customer_ID (FK) Item_ID (FK) Quantity Date/Time Total_Amount Order_Status 

ORDER_CANCELLATION

Cancellation_ID (PK) Order_ID (FK) Customer_ID (FK) Reason Cancellation_Date/Time Status 

Show the relationships clearly:

CUSTOMER 1 ─── places ─── M ORDER

MENU_ITEM 1 ─── included in ─── M ORDER

ORDER 1 ─── may have ─── 0..1 ORDER_CANCELLATION

Show PK and FK labels clearly. Use proper ER notation and relationship lines.

DESIGN REQUIREMENTS Make it suitable for a BCA college project. Use a clean white/light background. Use professional 3D-style boxes with subtle depth. Use clear black/dark text. Keep all text readable and correctly spelled. Keep each diagram separate and clearly labelled: FLOWCHART ALGORITHM ER DIAGRAM Maintain the exact feature order: Customer Details → Menu Items → Order Details → Order Status → Order Cancellation Do not add unrelated features. Do not overcrowd the diagrams. Make all arrows, relationships, symbols, PKs, and FKs clearly visible. Ensure the final diagrams are technically correct and suitable for submission as a college project. 



