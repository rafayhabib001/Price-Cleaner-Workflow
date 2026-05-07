# Price-Cleaner-Workflow
# Price Cleaner Workflow (n8n)

This workflow demonstrates a simple price-cleaning automation in n8n.

## Features

- Takes a raw price value
- Removes currency symbol ($)
- Returns cleaned numeric value
- Beginner-friendly workflow
- Uses JavaScript Code node

---

## Workflow Structure

1. Manual Trigger
2. Set Node
3. JavaScript Code Node

---

## Example

### Input
```json
{
  "row_price": "$500"
}
**Output**
{
  "row_price": "$500",
  "clean_price": "500"
}
