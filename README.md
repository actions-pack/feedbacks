# Actions Pack
Actions Pack is a Wordpress Plugin that extends Elementor Form widget providing different form actions those are executed when an Elementor form is submitted from the frontend. One such important action is Elementor User Registration that will help you create unlimited Wordpress users with the power of Elementor’s Native Form Widget. Currently the Plugin includes 5 premium actions and counting.

Download Actions Pack Plugin: https://actions-pack.com

=== Actions Pack ===
Contributors: dbjpanda
Tags: elementor, forms, register, login, Edit Profile, SMS, google-sheet
Requires at least: 4.7
Tested up to: 5.5
Requires PHP: 5.4
Stable tag: 2.0.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

== Changelog ==

= 2.0.8 - 2020-09-22 =
* Fix : Google Sheet Credentials not getting saved

= 2.0.7 - 2020-09-17 =
* Tweak : Google Sheet Internal Logic Changed (Require Form Reconfiguration)
* Tweak : Google Sheet UI & Performance improved
* Feature : Form Meta data like date, url etc are now available within Google Sheet Action [#27](https://github.com/dbjpanda/actions-pack-issue-tracker/issues/27)
* Feature : You can now connect your Elementor Form to Different Google Sheets like Sheet1, Sheet2.
* Compatibility issue fix with Elementor Pro 3.0.4 & Wordpress 5.5.1

= 2.0.6 - 2020-08-26 =
* Feature : Added Custom Column Option in Google Sheet that works after column 'Z'
* Feature : Introduced ap-userid, ap-password for show/hide widget on reset password form
* Tweak : Delete Actions Pack stored options when user uninstall the plugin
* Tweak : Hard Coded Reset pass link sent message
* Fix : Google Sheet Access Token Not saving after expired
* Fix : Login Redirection Option Undefined index warning

= 2.0.5 - 2020-08-15 =
* Fix : Js error Password Preview Toggle
* Fix : Login via Id & Password was set by default
* Added Template library API

= 2.0.4 - 2020-08-13 =
* Fix : Reset Password through Email
* Fix : Error Message Typo
* Reset Pass Performance Increase (Removed Html Parser)
* Added shortcode [ap-firstname] & [ap-lastname] for Reset Pass Message
* Harden Security, Prevent direct access to any php files

= 2.0.3 - 2020-08-12 =
* Fix : Internal Logic
* Compatibility fix with Wordpress 5.5

= 2.0.2 - 2020-08-9 =
* Fix : Login via Email and Number
* Tweak : Added Eye icon toggle for Password Preview
* Feature : Added Elementor Templates for User registration, login signup, signin, User profile

= 2.0.1 - 2020-07-30 =
* Feature : Edit Profile Action Added
* Feature : Login using Password, OTP(Password-less Login), Password & OTP
* Feature : Reset pass using OTP
* Tweak : Reset Pass and New Password actions are now a single action
* Registration Action Minor Bug Fix

= 2.0.0 - 2020-06-11 =
* Feature : OTP Verification
* Feature : SMS Action added
* Feature : Auto Login after registration
* Feature : Redirection after registration
* Refactored Elementor controls
* Internal logic change
* Added notification subject name option

= 1.3.0 - 2020-03-19 =
* Compatibility issue fix with Elementor Pro 2.9.1

= 1.2.9 - 2019-12-22 =
* Implemented Resend Confirmation Email
* Fix some PHP notices and warnings

= 1.2.8 - 2019-12-17 =
* Fix plugin updation bug
* Undefined index notice when both the login id/password is blank
* Translation Ready [#3](https://github.com/dbjpanda/actions-pack-issue-tracker/issues/3)
* Confirm password on Register Action [#4](https://github.com/dbjpanda/actions-pack-issue-tracker/issues/4)
* Remember me Implementation [#7](https://github.com/dbjpanda/actions-pack-issue-tracker/issues/7)
* Send form fields with registration email [#5](https://github.com/dbjpanda/actions-pack-issue-tracker/issues/5)
* Redirect to the same page after a Modal Pop-up Login left [#1](https://github.com/dbjpanda/actions-pack-issue-tracker/issues/1)

== Upgrade Notice ==

= 2.0.7 =
You need to reconfigure Google Sheet form because the UI and internal logic has been refactored in this version
