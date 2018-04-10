# Users overview

Users are the representation of an Azure Active Directory user account in Microsoft Graph. The User resource lets you explore the group and organizational relationships of a user as well as access and create user messages, contacts, and files.

## Why users?

### User relationships and data 

Access user elationships, information, and data allow you to build applications and user workflows that are personalized and immediately relevant to the user.

The Microsoft Graph Users entity has resources that let you access these relationships and data in the context of a user. The returned Graph entities from these resources-such as messages, contacts, and groups-that you can review and act on in your application. 

To get permissions to access a user's information and data, you'll need to [get access on their behalf](https://developer.microsoft.com/graph/docs/concepts/auth_v2_user) before using the Users resource.

### Manage users in your organization

Create new users in your organization or update the resources and relationships for existing users with the Users endpoint. 

- Create or delete users in your Azure AD organization
- List a user's group memberships and check if a user is a member of a group.
- List the users who report to a user and assign managers to a user.
- Upload or retrieve a photo for the user.

### Work with user calendars

Users has direct resources that let you view, query, and update user calendar and calendar groups

- List and create events on a users calendar.
- Find free meeting times for a set of users.
- Get a list of reminders set on a user's calendar.

### Administer mail and handle contacts

Users provides resources to configure user mail settings and contact lists and to send mail on a user's behalf.

- List mail messages and send new mail.
- Create and list user contacts and organize contacts in folders.
- Retrieve and update mailbox folders and settings.

## Next steps

- Authenticate with Microsoft Graph [on behalf of a user](https://developer.microsoft.com/en-us/graph/docs/concepts/auth_v2_user) or [as a daemon or service by consent of an administator](https://developer.microsoft.com/en-us/graph/docs/concepts/auth_v2_service).
- Set access control and policies for users with the [Azure AD resource](https://developer.microsoft.com/en-us/graph/docs/api-reference/v1.0/resources/azure_ad_overview)
- Review the [permissions](https://developer.microsoft.com/en-us/graph/docs/concepts/permissions_reference) your app will need to access user data. 
- Stay up to date with the Microsoft Graph [changelog](https://developer.microsoft.com/en-us/graph/docs/concepts/changelog)