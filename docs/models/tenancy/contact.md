# Contacts

A contact represents an individual or group that has been associated with an object in NetBox for administrative reasons. For example, you might assign one or more operational contacts to each site.

## Fields

### Groups

The [contact groups](./contactgroup.md) to which this contact is assigned (if any).

!!! info "This field was renamed from `group` to `groups` in NetBox v4.3, and now supports the assignment of a contact to more than one group."

### Name

The name of the contact. This may be an individual or a team/department. (This is the only required contact detail; all others are optional.)

### Title

The contact's title or role.

### Phone

The contact's phone number. (Note that NetBox does _not_ enforce a particular numbering format.)

### Email

The contact's email address.

### Address

The contact's physical or mailing address.

### Link

A URL to reach the contact via some other means.
