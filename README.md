# SMS.ir × n8n — SMS Workflows (Bulk & Verify)

Ready-to-import **n8n** demo workflows for sending SMS via **SMS.ir** — simple examples for testing and learning.

## What’s inside
- **`smsir-bulk-send.json`** — Send one message to many recipients (Bulk).  
- **`smsir-verify-send`** — Template-based, high-priority messages (Verify).

Both follow the same pattern: **Form → Set → HTTP Request**.

## How to import (n8n UI)
1. From **Overview**, click **Create Workflow** (top-right).  
2. In the new workflow canvas, open the **⋯** (kebab) menu near **Save** → **Import from File…** (or **Import from URL…**).  
3. Select **`smsir-bulk-send.json`** or **`smsir-verify-send`** from this repo.  
4. Click **Save**, then **Execute**.  
5. Fill the form fields (ApiKey and others) and submit to trigger the **SMS.ir** API call.
