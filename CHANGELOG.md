# Changelog

## Version 0.1.19 [2024-08-20]

## Bug Fixes
* Corrected a formatting issue in the changelog to improve readability.
* Resolved an accessibility issue with the "Copy to Clipboard" icon in webviews to ensure better usability for all users.

## Version 0.1.18 [2024-08-07]
## Updates
* Added support for custom domains in "Try out your sign in" step

## Bug Fixes
* Enhanced the 403 Error message on Explorer View Resources.

## Version 0.1.17 [2024-08-01]
## Updates
* Introduced IntelliSense for tenant resources' JSON files, providing hover-over details to facilitate understanding of various JSON fields.

## Bug Fixes
* Fixed bug in configure sign-in experience to allow users with existing tenants to update branding.

## Version 0.1.16 [2024-07-29]
## Updates
* Added a confirmation step in quick picker to ensure users want to proceed with branding updates, affecting all apps.
* Users can now create a tenant from resource manager after signing in if they don't have one.
* Improved error notification for 403 errors when users lack the required access to perform an action.

## Bug Fixes

## Version 0.1.15 [2024-07-18]
## Updates
* Added async input validation to provide instant feedback on tenant name availability during tenant creation process
* Added capacity to delete applications and user flows directly from the manage resources section.
* Introduced trial tenant expiry notifications for users who created trial tenants from within the extension.

## Version 0.1.14 [2024-07-15]
## Bug Fixes
* Fixed an issue related to telemetry functionality

## Version 0.1.13 [2024-07-11]
## Updates
* Introduced a new walkthrough step to try out the configured sign-in experience and create the first user.
* Tenant names are now sorted alphabetically by title.
### Bug Fixes
* Resolved issue to ensure existing applications get updated with correct redirect URI

## Version 0.1.12 [2024-07-02]
### Updates
* Improved error message clarity during tenant creation using a subscription.
* Removed the cancel button from the branding call process to avoid confusion, as branding updates are non-cancellable once applied.
### Bug Fixes
* Display the tenant name instead of the default logo in the branding webview, if the logo has not been configured, to match the actual sign-in page.
* Removed ".entra" from the resource webview name.

## Version 0.1.11 [2024-06-06]
### Updates
* Introduced a quick picker for easy tenant creation when selecting "Create a tenant to get started" in the explorer view.
* Improved readability of branding prompt descriptions in quick picker
* Revised README to include updated content and a new explorer view GIF

### Bug Fixes
* Fixed refreshing issues with the explorer view.

## Version 0.1.10 [2024-05-20]
### Bug Fixes
* Fixed issues with app registration and user flow setup.

## Version 0.1.9 [2024-05-17]
### Updates
* Enhanced the walkthrough GIF for better visual experienceq

### Bug Fixes
* Fixed branding preview to update instantly after changes.

## Version 0.1.8 [2024-05-16]
### Updates
* Updated the Microsoft Entra External ID logo to reflect the latest product branding.
### Bug Fixes
* Addressed and resolved several bugs to improve performance and stability, enhancing the overall user experience. Specific fixes include:
* Ensured that JSON files of External ID resource are now readable.
* Fixed an issue to ensure the correct application ID is displayed in the the webview.
* Improved validation checks for tenant names during tenant creation process.
* Resolved intermittent failures during logo upload in the branding settings.

## Version 0.1.7 [2024-05-10]
### Updates
* Added webviews to enhance the display of tenant resources information in a more readable and user-friendly format.
* Added sample codes for Python using Flask and Django frameworks, tailored to align with the configured sign-in experience.
* Improved error message notifications during tenant creation to help users better understand and resolve issues
* Added notifications that prompt users to provide feedback

## Version 0.1.6 [2024-04-19]
### Updates
* Made branding configuration optional and provided the ability to update branding in the "Manage Resources" section.
* Added automatically configured sample app for ASP.Net core and Node.js that align with the configured sign-in experience.
* Improved error handling during tenant creation.
* Added progress indicators for notifications.
* Fixed a bug to enable downloaded samples to launch on non-Windows platforms.


## Version 0.1.5 [2024-04-04]
### Bug fix
* Hotfix for tenant creation to resolve API changes


## Version 0.1.4 [2024-03-28]
### Updates
* Added branding to the "Manage Resources" section.
* Updated right-click context menu titles in the "Manage Resources" section for better clarity.
* Added tenant name validations to prevent errors during setup.
* Added checks for valid user flows with appId to improve the sample download process.
* Introduced auto-refresh in the "Manage Resources" section to keep it up to date.
* Configured automatic registration of "Microsoft.AzureActiveDirectory" as a resource provider when creating tenants using a subscription.

## Version 0.1.3 [2024-03-01]
### Initial release
* Free trial tenant setup: Enable users to set up a free trial tenant directly within the extension without any upfront costs.
* Azure subscription tenant setup: Allows users with an existing Azure subscription to seamlessly set up a tenant through the extension.
* Sign-in experience and branding customization: Offers customizable sign-in options including email/password and one-time passcode. Enhance the user interface with company logo, background color, and layout adjustment.
* Preconfigured sample app: Includes sample codes for single-page applications (JavaScript, React, Angular) that integrate automatically with the configured sign-in experience
