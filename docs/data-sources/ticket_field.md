---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "zendesk_ticket_field Data Source - terraform-provider-zendesk"
subcategory: ""
description: |-
  
---

# zendesk_ticket_field (Data Source)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `type` (String)

### Read-Only

- `active` (Boolean)
- `agent_description` (String)
- `collapsed_for_agents` (Boolean)
- `custom_field_option` (Set of Object) (see [below for nested schema](#nestedatt--custom_field_option))
- `description` (String)
- `editable_in_portal` (Boolean)
- `id` (Number) The ID of this resource.
- `position` (Number)
- `regexp_for_validation` (String)
- `removable` (Boolean)
- `required` (Boolean)
- `required_in_portal` (Boolean)
- `sub_type_id` (Number)
- `system_field_options` (Set of Object) (see [below for nested schema](#nestedatt--system_field_options))
- `tag` (String)
- `title` (String)
- `title_in_portal` (String)
- `url` (String)
- `visible_in_portal` (Boolean)

<a id="nestedatt--custom_field_option"></a>
### Nested Schema for `custom_field_option`

Read-Only:

- `id` (Number)
- `name` (String)
- `value` (String)


<a id="nestedatt--system_field_options"></a>
### Nested Schema for `system_field_options`

Read-Only:

- `name` (String)
- `value` (String)

