---
page_title: "snowflake_database_role Data Source - terraform-provider-snowflake"
subcategory: ""
description: |-
  
---

# snowflake_database_role (Data Source)



## Example Usage

```terraform
data "snowflake_database_role" "db_role" {
  database = "MYDB"
  name     = "DBROLE"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `database` (String) The database from which to return the database role from.
- `name` (String) Database role name.

### Read-Only

- `comment` (String) The comment on the role
- `id` (String) The ID of this resource.
- `owner` (String) The owner of the role