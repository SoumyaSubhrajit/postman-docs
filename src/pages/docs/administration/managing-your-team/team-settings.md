---
title: "Configure team settings"
updated: 2023-06-21
contextual_links:
  - type: section
    name: "Additional resources"
  - type: subtitle
    name: "Videos"
  - type: link
    name: "Checklist for a Great Team Profile | Postman Level Up"
    url: "https://youtu.be/Ud_rq-VwO4s"
  - type: subtitle
    name: "Blog posts"
  - type: link
    name: "Increase API adoption with improved team profiles"
    url: "https://blog.postman.com/increase-api-adoption-with-improved-team-profiles/"
  - type: link
    name: "Get More Out of Postman by Collaborating with Your Team"
    url: "https://blog.postman.com/get-more-out-of-postman-by-collaborating-with-your-team/"
---

Your [Team Settings](https://go.postman.co/settings/team/general) enable you to manage items such as your team's profile, discoverability, custom domains, authentication, and active invite links.

<img alt="Team menu with Team Settings selected" src="https://assets.postman.com/postman-docs/v10/team-settings-configured-v10.jpg"/>

## Contents

* [Accessing team settings](#accessing-team-settings)
* [Managing your team profile](#managing-your-team-profile)
    * [Editing your team profile](#editing-your-team-profile)
    * [Making your team profile public](#making-your-team-profile-public)
* [Making your team discoverable](#making-your-team-discoverable)
* [Reviewing Secret Scanner patterns](#reviewing-secret-scanner-patterns)
* [Adding custom domains](#adding-custom-domains)
* [Using installed apps](#using-installed-apps)
* [Editing authentication methods](#editing-authentication-methods)
* [Managing roles and permissions](#managing-roles-and-permissions)
* [Reviewing invite links](#reviewing-invite-links)
* [Downloading the Postman Enterprise app](#downloading-the-postman-enterprise-app)

## Accessing team settings

You can access team settings by selecting **Team** in the header, then selecting **Team Settings**.

<img alt="Team menu with Team Settings selected" src="https://assets.postman.com/postman-docs/v10/team-settings-menu-selected-v10.jpg" width="350px"/>

## Managing your team profile

Your team profile gives you a way to share important information about your team with other Postman users. The profile brings together all your team's public resources in one place, and can serve as a developer portal for your API's consumers.

[Super Admins, Admins, and Community Managers](/docs/collaborating-in-postman/roles-and-permissions/#team-roles) can edit your team profile, customize your team's branding, and manage the public visibility of your team profile.

Your team profile includes:

* A short summary about your team and the work you do
* Social media links like your GitHub profile
* A list containing links to your team members' profiles
* A **Team Description** section
* A **Highlights** section with pinned elements
* A **Related collections and flows from the community** section with collections and Flows using your team's APIs (suggested by Postman)
* Links to all your team's public collections, APIs, workspaces, and Flows

<img alt="Example of a filled-in team profile" src="https://assets.postman.com/postman-docs/v10/team-settings-overview-v10.1.jpg" width="800px"/>

### Editing your team profile

When you select **Team Settings**, you will be automatically directed to your **Team profile**. Next, select **View team profile**. Here, you can edit your team's summary, description, highlights, and more.

<img alt="Edit your team profile" src="https://assets.postman.com/postman-docs/v10/team-settings-edit-profile-v10.jpg" width="700px"/>

* **Team summary** - Select **Add Team Summary**. Use this space to add a summary about your team and the work you do, up to 140 characters. To edit your team summary, hover over the section and select the edit icon <img alt="Edit icon" src="https://assets.postman.com/postman-docs/documentation-edit-icon-v8-10.jpg#icon" width="18px">.
* **Social links** - Select **Add Social Links**. You can add a link to your website and links to social media accounts. To edit these links, hover over the section and select the edit icon <img alt="Edit icon" src="https://assets.postman.com/postman-docs/documentation-edit-icon-v8-10.jpg#icon" width="18px">.
* **Members** - To manage your team members, hover over this section and select **Manage**.
* **About your team** - Select **Add Team Description**. To update your team description, hover over the section and select the edit icon <img alt="Edit icon" src="https://assets.postman.com/postman-docs/documentation-edit-icon-v8-10.jpg#icon" width="18px">. The editor supports Markdown, or you can use the built-in text formatting tools.
* **Highlights** - This section lets you show off your team's work to other Postman users. If you don't choose any elements to pin to this section, Postman displays the most popular elements that you've worked on. To update the highlighted elements, hover over the section and select the edit icon <img alt="Edit icon" src="https://assets.postman.com/postman-docs/documentation-edit-icon-v8-10.jpg#icon" width="18px">. Add or remove the desired elements, then select **Save**.

#### Customizing your team's branding

Select **Team profile** to add a team logo, cover photo, and favicon. These assets help you establish your team identity and ensure consistent branding.

To add a team logo and cover photo, hover over the section and select the edit icon <img alt="Edit icon" src="https://assets.postman.com/postman-docs/documentation-edit-icon-v8-10.jpg#icon" width="18px">, then upload the image you want to use. To add a favicon, select **Upload** under the **Favicon** section.

<img alt="Customize your team's branding" src="https://assets.postman.com/postman-docs/v10/team-settings-customize-branding-v10.jpg" width="500px"/>

Keep the following in mind when you upload a logo, cover photo, or favicon:

* Logos and cover photos must be 500 KB or less in size and must be in JPG, JPEG, or PNG format.
* Logos must have a 1:1 aspect ratio (height:width), and cover photos must have a 1:7.5 aspect ratio. If your image has a different aspect ratio, Postman prompts you to select a part of your image to display.
* Favicons must be in ICO format, no larger than 32x32 pixels, and 500 KB or less in size. Your favicon appears on the browser tab of your team's published documentation site.

### Making your team profile public

A public team profile encourages other users to collaborate with you in a public workspace, enabling you to ask for contributions, gather feedback, and increase your API's discovery in search results.

If you enable your team's public profile, your team will be visible on [the Public API Network](https://www.postman.com/explore), along with your public workspaces, collections, APIs, and Flows. Learn more about [the Public API Network and best practices for sharing elements](/docs/collaborating-in-postman/public-api-network/public-api-network-overview/).

To make your [team profile](https://go.postman.co/settings/team/general) public, do the following:

1. In **Team Settings**, select **Team profile**.
1. Select **Make team profile public** to set the profile to public.

<img alt="Make your team profile public" src="https://assets.postman.com/postman-docs/v10/team-settings-make-profile-public-v10.jpg" width="500px"/>

## Making your team discoverable

Select **Team discovery** to view your options for making your team discoverable to other Postman users with email addresses from your team's domain.

See [Enabling team discovery](/docs/collaborating-in-postman/working-with-your-team/enabling-team-discovery/) for more information about enabling people in your organization to find and join your team.

## Reviewing Secret Scanner patterns

> **[Custom patterns are available on Postman Enterprise plans.](https://www.postman.com/pricing/)**

Select **Secret Scanner** to review default patterns for tokens issued by common service providers that the Postman Secret Scanner scans for. You can also add and review custom patterns that scan for your team's proprietary tokens and third-party app tokens.

See [Secret Scanner](/docs/administration/managing-your-team/secret-scanner/) to learn more about scanning public workspaces to detect exposed secrets.

## Adding custom domains

Select **Custom Domains** to add, update, or remove custom domains for your API documentation.

See [Use custom domains](/docs/publishing-your-api/custom-doc-domains/) for information about adding, verifying, troubleshooting, and publishing to custom domains.

## Using installed apps

Select **Installed apps** to enable all members of a team to use the same stored authorization details when adding integrations.

See [Using installed apps in integrations](/docs/integrations/installed-apps/) for more information about adding and using installed apps in integrations.

## Editing authentication methods

> **[SSO is available on Postman Professional and Enterprise plans.](https://www.postman.com/pricing/)**

Select **Authentication** to configure or reconfigure your team's authentication methods.

See [Configuring SSO for a team](/docs/administration/sso/admin-sso/) for details explaining how to configure your team's custom SSO setup and manage user accounts.

## Managing roles and permissions

You can select the following to add roles to users and groups, and review role assignments:

* Select **Members** to manage your team members and assign them roles.
* Select **Groups** to manage your user groups and assign them roles.
* Select **Roles and permissions** to view a complete list of permissions for users' roles at a team, collection, workspace, API, mock server, and monitor level.

See [Defining roles](/docs/collaborating-in-postman/roles-and-permissions/) for more information about roles you can assign to team members. See [Managing your team](/docs/administration/managing-your-team/managing-your-team/) for an overview of managing roles and users within your Postman team. See [Managing user groups](/docs/collaborating-in-postman/user-groups/) for more information about managing groups and adding roles to the groups.

## Reviewing invite links

Select **Invite links** to review the invites your team has sent to others.

See [Managing invites](/docs/administration/managing-your-team/managing-your-team/#managing-invites) to learn more about managing invites and invite links.

## Downloading the Postman Enterprise app

> **[The Postman Enterprise app is available on Postman Enterprise plans.](https://www.postman.com/pricing)**

Select **Enterprise application** to download the Postman Enterprise app.

See [Managing Enterprise deployment](/docs/administration/enterprise/managing-enterprise-deployment/) to learn more about managing and deploying the Postman Enterprise app.
