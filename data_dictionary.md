# Data Dictionary

| Field | Description |
|---|---|
| Lead_ID | Unique CRM lead identifier |
| Lead_Source | Acquisition channel |
| Sales_Stage | Current pipeline stage |
| Lead_Owner | Assigned sales representative |
| Estimated_Value | Estimated potential revenue |
| Qualified | Whether the lead reaches a qualified stage |
| Converted | Whether the lead closes as won |
| Duplicate_Flag | Flags repeated nonblank email records after the first occurrence |
| Missing_Owner | Flags leads with no assigned owner |
| Missing_Contact_Info | Flags leads missing both email and phone |
| Stale_Lead | Flags open leads with no contact for more than 30 days |
| Overdue_Followup | Flags open leads whose follow-up date has passed |
| Data_Quality_Issue | Flags records with at least one defined CRM quality issue |
| Primary_Record | 1 for first/unique record; 0 for later duplicate-email records |
