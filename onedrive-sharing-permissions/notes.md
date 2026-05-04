## Task: Change sharing permissions on a OneDrive folder

### Goal
Modify the sharing permissions on a OneDrive folder to control who can access it.

### Steps taken
1. Logged into admin.microsoft.com
2. Navigated to SharePoint admin center > Policies > Sharing
3. Reviewed the organization-wide sharing settings (set to Anyone by default)
4. Changed the external sharing level to Only people in your organization to restrict sharing outside the tenant
5. Navigated to a user's OneDrive via Users > Active Users > [User] > OneDrive > Open
6. Located a folder, right-clicked, and selected Manage access
7. Removed an existing external user and updated permissions to View only for internal users

### Screenshots
![](../screenshots/)
<br/>

### What I learned
OneDrive sharing permissions operate at two levels: organization-wide policies set in the SharePoint admin center, and folder-level permissions set per item. Restricting sharing to internal users only is a common data loss prevention (DLP) measure to prevent sensitive files from being shared externally by mistake.