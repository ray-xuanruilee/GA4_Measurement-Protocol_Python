# GA4_Measurement-Protocol_Python (updated: 1 Dec 22, Thu)
I uploaded a new notebook, "GA4 MP for Offline Stores' Transactions", that further fleshed out and walked through the logic and considerations when dealing with offline Point-of-Sales (POS) systems.

**The guide includes:**
1. Where to Find your: I. GA4 Property Measurement ID, II. API Secret.
2. Create a class to represent the Client's customer and their transaction's parameters and user properties.
    - Sample code to fetch data from the Client's POS system - related to the current transaction and the offline customer _(might involve backend)_.
    - Sample code to instantiate the offline customer's current transaction and information. This is then used to construct the Payload below _(does not involve backend)_.
3. Construct the Payload
4. Send it to GA4
5. Check it on GA4
