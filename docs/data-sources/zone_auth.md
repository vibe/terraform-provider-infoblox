---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "infoblox_zone_auth Data Source - terraform-provider-infoblox"
subcategory: ""
description: |-
  
---

# infoblox_zone_auth (Data Source)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `filters` (Map of String)

### Read-Only

- `id` (String) The ID of this resource.
- `results` (List of Object) List of zones matching filters (see [below for nested schema](#nestedatt--results))

<a id="nestedatt--results"></a>
### Nested Schema for `results`

Read-Only:

- `comment` (String)
- `ext_attrs` (String)
- `fqdn` (String)
- `id` (String)
- `ns_group` (String)
- `view` (String)
- `zone_format` (String)
