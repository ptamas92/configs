# Privacy Policy – Spendoid

The Spendoid application does not collect any personally identifiable information (such as names, email addresses, or phone numbers).

Users can access all features of the application anonymously, without registration.  
By default, all data is stored locally on the user's device, in the device's internal memory.

When activating a PRO in-app purchase, the application generates a unique internal identifier (`purchaseId`), and in connection with this:
- it stores the purchase data (`purchase`),
- and periodically creates a backup of the user-generated data in a Firebase cloud-based database.

The purpose of this is to ensure that users who purchase the PRO package can:
- easily restore their purchase after reinstalling the app (based on the `purchaseId` or `transactionId`),
- and automatically regain access to their previously saved data (e.g., settings, recurring expenses, expected costs, etc.).

The stored data is used **exclusively for restoring PRO features**.  
Read and write operations are handled using hash-based secure identifiers.  
**The data is not shared with any third parties, not used for marketing purposes, and not analyzed in any form.**

The stored data cannot be used to identify users and contains only the minimal information required for the application's functionality.

If our data handling practices change, we will publish the updated policy on this page.
