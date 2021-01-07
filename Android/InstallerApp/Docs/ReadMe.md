### Installer&trade; Application

**Who will use this application?**  
It will be used by installer agents or service agents of the oves organization. these agents are different from the credit agents (ROAM&trade; App).

**How different the Credit Agents and Installer Agents?**  
For high-level understanding, you can consider installer agents **equivalent** to the distributors and credit agents **under** the distributors. for now, installer agents ables to access all the users, products, payAccounts as a distributor can do. But for credit agents, they can only access the resources for what they have been assigned.

**What major functions are in Installer&trade; application?**  
* PayAccount Creation via GraphQL
* Events Publishing Via MQTT

**What is PayAccount?**  
It simply accounts creation of users for tracking financial records, giving them warranty services, or various services for the respective product. We'll have same the number of payAccounts as the Installed Products. Remember, We can't have multiple users for any created payAccount. However, users can own multiple products or payAccounts.
>e.g. Telecome service provides the SIM card to the end user. Your account gets created in their system Whenever you purchase the SIM Card. Therefore, in the future, if you need any service like Recharge, Caller-tune, Data-Subscription, they will simply look into your account and will allocate to you after collecting the respective amount.

based on the example, no any SIM Card has two users/owners. likewise, in our OVES&trade; Organization we can not have two users/customers for the same product. ultimately, we are creating one payAccount for one Product. We are creating payAccount for recharges, warranty services or any add-on services that we can introduce in the future.

