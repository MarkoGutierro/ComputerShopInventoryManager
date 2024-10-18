**Project Summary:** Enhanced a Stateful API in Java by customizing a Spring Framework application to improve user interaction and functionality for an inventory management system.

**Implementation Steps:** The goal of this project was to enhance an existing API. While the basic HTML and Java backend were in place, I needed to add functionality for the inventory manager to operate effectively.

I successfully enhanced the Spring application by adding a sample inventory with five parts and five products, ensuring it didn’t overwrite any existing database data. The sample inventory is stored in a set to prevent duplicates.

I created a new controller to implement a "Buy Now" button, placing it next to the update and delete buttons. This button decrements the product's inventory by one while keeping the associated parts unaffected, displaying a message that indicates the success or failure of each purchase.

To track inventory levels, I added additional fields for maximum and minimum inventory to the part entity and updated the sample inventory accordingly. I included text inputs in the relevant forms for users to set these values and modified the code to enforce inventory limits.

I implemented validation to display error messages for low inventory when adding and updating parts and products, as well as for exceeding maximum inventory levels. I also added unit tests for the maximum and minimum fields in the test package.

In the end, the computer shop now features an inventory management system that enables users to add, modify, and delete relevant persistent data.
