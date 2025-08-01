=== Ko-fi Members ===
Contributors: trudslev
Donate link: https://ko-fi.com/
Tags: ko-fi, membership, roles, webhook, user management
Requires at least: 5.6
Tested up to: 6.8
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Integrate with Ko-fi to manage WordPress users or roles via webhook.

== Description ==

Ko-fi Members is a WordPress plugin that integrates with Ko-fi to manage WordPress users and roles based on Ko-fi webhooks. This plugin allows you to automate user role assignments, log donations, and manage memberships seamlessly.

**Features:**
- Automatically assign roles to users based on Ko-fi donations or memberships.
- Log user actions, such as donations and role changes, in a dedicated database table.
- Configure logging levels and enable email notifications for logs.
- Fully compatible with GDPR and WordPress privacy tools.

**Use Cases:**
- Reward your Ko-fi supporters with exclusive access to content or features.
- Automate user role management for subscription-based memberships.
- Track and log user activity for better insights.

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/kofi-members` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Configure the plugin settings under **Settings > Ko-fi Members**.
4. Set up your Ko-fi webhook to point to your WordPress site.

== Frequently Asked Questions ==

= How do I set up the Ko-fi webhook? =
1. Log in to your Ko-fi account.
2. Go to **Settings > Webhooks**.
3. Add your WordPress site's webhook URL (e.g., `https://your-site.com/wp-json/kofi-members/v1/webhook`).

= Does this plugin delete data on deactivation? =
No, the plugin does not delete any data on deactivation. However, you can manually delete data by uninstalling the plugin.

= Is this plugin GDPR compliant? =
Yes, the plugin integrates with WordPress's privacy tools to allow exporting and erasing user data.

== Screenshots ==

1. **Settings Page**: Configure plugin options, including logging and role mapping.
2. **User Logs**: View detailed logs of user actions, such as donations and role changes.
3. **Webhook Configuration**: Example of setting up the Ko-fi webhook.

== Changelog ==

= 1.0.0 =
* Initial release.
* Added support for Ko-fi webhooks.
* Automatic role assignment based on donations or memberships.
* Logging of user actions with configurable log levels.

== Upgrade Notice ==

= 1.0.0 =
Initial release. No upgrade steps required.

== License ==

This plugin is licensed under the GPLv2 or later. See the [GNU General Public License](https://www.gnu.org/licenses/gpl-2.0.html) for more details.