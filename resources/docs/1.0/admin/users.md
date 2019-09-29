# Users

Site users can be managed from the Users page. Admin can temporarily disable their account by turning `Status` `On/Off` or permanently delete them.

> {info} User's group can be changed from `User - Edit` page. By default, a new user is assigned with `Members` (public) group.

---

- [User Groups](#User-Groups)
- [Manage ACL](#Manage-ACL)

<a name="User-Groups"></a>
## User Groups

This is about making multiple user groups and assigns them different permissions for managing different modules throughout the `Admin Panel`.


### Default Groups

3 default groups can't be modified or deleted. `Members` group users are restricted to Admin Panel, all other group users can access admin panel.

- Admin
    
    Super Admin group, have all the permissions on the admin panel.

- Members

    Public group, this group user can't visit the admin panel. (front-end access only)

- Editors

    Semi-admin group, this group user can visit the admin panel, depending on the permissions assigned on Manage ACL


>{primary} Admin can create unlimited groups according to different needs. 


<a name="Manage-ACL"></a>
## Manage ACL

Manage Access Control List of user groups. Assign the groups permissions to access a modules e.g Messages - `View` `Add` `Edit` `Delete` operations.

---

![access control list](https://anofie-docs.classiebit.com/images/acl-1.jpg "access control list")

---


### Assign View | Add | Edit | Delete Permissions

4 types of permissions can be assigned to limit access of different group to each module.

<br>

- **View** User can view the module or not.
- **Add** User can add new data to the module or not.
- **Edit** User can modify the existing data in the module or not.
- **Delete** User can delete the existing data in the module or not.

--- 

> {warning} `Admin` & `Members` group permissions can't be modified.