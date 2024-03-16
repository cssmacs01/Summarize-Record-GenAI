# Summarize-Record-GenAI
This utility fixes the current broken Azure_OpenAI proxy within DemoHub instances.

Here are the install steps:

pre-req: Make sure your plugins: UXC Generative AI is updated to 4.0.4
1. Load and Commit the attached update set (on error accept remote update)
2. goto sys_properties.list and find the property: com.sn.generative.ai.provider and make sure the value is: openai
3. Head over to Service Portal or Employee Center and search for GenAI, you'll see two requests, choose this one: Add Gen AI Features - OpenAI, check Summarize, pick your workspace, pick your tables, leave the fields blank
4. Head over to your workspace, you should have a record ui action called "Summarize Record", go ahead and click it and the record should be summarized with OpenAI. Copy and paste the summarization into the Work Notes if you want, but it should demo great. Add this to any table and you can summarize any record in SN.

sys_property should match this.
<img width="1736" alt="Screenshot 2024-03-16 at 4 35 35 PM" src="https://github.com/cssmacs01/Summarize-Record-GenAI/assets/11742161/c5a5e11e-be10-4baa-8b4b-e4134eda1341">

new catalog item to setup your Workspace records for summarization
<img width="1050" alt="Screenshot 2024-03-16 at 4 38 31 PM" src="https://github.com/cssmacs01/Summarize-Record-GenAI/assets/11742161/2320a874-fbe2-4311-ac51-515c7a8d43e1">

click the Summarize Record UI Action
<img width="1775" alt="Screenshot 2024-03-16 at 4 37 34 PM" src="https://github.com/cssmacs01/Summarize-Record-GenAI/assets/11742161/f5b39b82-53e4-4271-97b5-294bd2c6ad04">

Ba Boom! Summarized the activity notes, both work and additional comments
<img width="1768" alt="Screenshot 2024-03-16 at 4 37 45 PM" src="https://github.com/cssmacs01/Summarize-Record-GenAI/assets/11742161/dd9206d4-5d9a-43ab-93a2-38b770e61419">


