### Activity Guide: Advanced Management of Accounts and Contacts
## Introduction
**In this hands-on activity, we will explore advanced configurations for managing Accounts and Contacts in Dynamics CRM. This guide will help you create custom views, set up parent-child hierarchies, and configure roll-up fields to summarize data from child records.**
# Step 1: Creating Parent-Child Hierarchies
1. Open Dynamics CRM and navigate to the Accounts entity.
2. Select an existing Account or create a new one that will serve as the Parent Account.
3. Create another Account to be a Child Account. In the Parent Account field, search for and select the Parent Account created earlier.
4. Save and close the Child Account. You should now see a hierarchical relationship displayed under the Parent Account.
# Step 2: Configuring Roll-Up Fields
1. Go to Settings > Customizations > Customize the System.
2. Select the Accounts entity and click on Fields.
3. Click on ‘New’ and create a new field of type ‘Whole Number’ or ‘Currency’ as appropriate (e.g., Total Revenue).
4. Under Field Type, select ‘Rollup’.
5. Define the roll-up criteria (e.g., sum of revenue from all child Accounts) and save the field.
6. Publish your customizations and verify that the roll-up field displays correctly.
# Step 3: Creating Custom Views
1. Navigate to Advanced Find in Dynamics CRM.
2. Select the Accounts or Contacts entity, depending on your use case.
3. Define the search criteria (e.g., Contacts with missing phone numbers).
4. Click on ‘Save As’ and provide a name for your custom view.
5. Apply conditional formatting as needed (e.g., highlighting missing data).
6. Save, publish, and test your custom view by navigating to the relevant entity in CRM.
# Troubleshooting and Best Practices
- **Missing Data**: Ensure that Parent-Child relationships are correctly configured and that roll-up fields have appropriate permissions.
- **Conditional Formatting Issues**: If conditional formatting is not applying, check view configurations and refresh the view.
- **Publishing Errors**: Verify all changes in the entity and field definitions before publishing.
- **Performance Optimization**: Use roll-up fields judiciously as they can impact performance when applied to large datasets.
