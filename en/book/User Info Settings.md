### 2.13.2	User Info Settings

Member registration preferences are configured in this area of the control panel. Some of the settings have implications for the security of your website.

|Field|	Description|
| -- | -- |
|Allow new user registration? |	This is enabled by default. Disabling it will prevent anyone else from registering as a member of your site. A simple flash page is displayed showing a no registration allowed message when the “register now” link is pressed.|
|Minimum length of password required |The longer the minimum password the more secure it is. Short passwords are more vulnerable to brute force attacks. The default minimum is five characters. Minimum length of username required	The username is the ‘nickname’ or ‘handle’ by which the member will be known on the site. The default minimum length is five characters.|
|Maximum length of username|The default maximum length is ten characters.|
|Allow users to change email address?|	The default is ‘no’. Email addresses can provide an additional means of enforcing bans on troublesome members – they cannot register a new account using the same email address.|
|Notify by mail when a new user is registered?|	You can elect to notify a particular user group whenever a new member registers on the site.  This may be useful if you would like to send a personal welcome message or need to track membership for administrative reasons.|
|Select group to which new user notification mail will be sent|	See above. Notification messages should generally be sent to the Webmaster group, other users might regard them as ‘spam’.|
|Select activation type of newly registered users|	There are three options here: <br>i) Requires activation by user (recommended). When a user registers a confirmation email will be sent to the email address they supplied. They must click on a link in that email to activate their website account. This ensures that the user has supplied a valid email account and gives some degree of confidence that a human rather than a machine submitted the registration. This is the default.<br>ii) Activate automatically. The user’s account will be automatically activated on submission of their registration form, giving them immediate access to the site. This is the user-friendliest option (as it is the fastest) but it is also the least secure. <br>iii) Activation by Administrators. This is potentially the most secure option if Administrators take steps to confirm the identity of the user. However, users will probably be frustrated by the delay in having their account approved.|
|Select group to which activation mail will be sent	|This setting is only valid only when 'Activation by administrators' is selected (option iii) above). You can pick a user group to alert when a registration is pending approval. This should normally be ‘Webmasters’, which is the default.|
|Select the level of strictness for username filtering|	There are three options:<br>o	Strict. This is the default; only alphabets and numbers are allowed in the username.<br>o	Medium. <br>o	Light.  This is recommended if your members are likely to want to use multi-byte character sets (for example, Asian fonts).|
|Allow custom avatar upload?|	This enables members to supply their own choice of avatar, otherwise they can only use those supplied by the Administrators (see 2.3.1). The default is ‘no’.|
|Minimum posts required Enter the minimum number of posts required to upload a custom avatar|	You have the option to give members custom avatar privileges only after they submit a certain number of posts. This option is disabled by default (set at zero).|
|Avatar image max width (pixel)	|You can constrain the maximum dimensions of custom avatars. This prevents members from uploading large images that may interfere with the layout of your site. The default is 80 pixels.|
|Avatar image max height (pixel)|	As above.|
|Avatar image max filesize (byte)|	You can also set an absolute file size limit on custom avatars to help keep the size of your forum pages down to reasonable limits. A forum page can easily have (say) 10 different avatars on it, so putting a limit on avatar size can make quite a difference. The default is 35KB, which is quite large|
|Allow users to delete own account?	|The default is ‘no’. This can be useful to prevent banned members from deleting and then re-registering an identical account. |
|Enter names that should not be selected as username|	You can use this to reserve important, offensive or misleading usernames. Webmaster, and names beginning with XOOPS and Admin are reserved by default. You may wish to add others such as ‘Editor’, Administrator’ or Director-General ! Separate each entry with a pipe character ‘&#124;’ This preference is case insensitive. It is also regular expressions (regex) enabled. Regex is a pattern-matching language, you can use here to create rules for filtering names.  A “newbie guide” to regular expressions is available from: http://www.newbie.org/gazette/xxaxx/xprmnt02.html The ^ character indicates that the matched string should be at the beginning of a line and the pipe &#124; character is equivalent to a logical OR.
|Enter emails that should not be used in user profile|	You can prevent people from using certain email accounts in the registration process. It may be useful to exclude ‘disposable’ email accounts as a security precaution. The syntax to prohibit all addresses ending in homail.com, for example, is homail.com$. Separate each entry with a &#124;. This preference is case insensitive and regex enabled.|
|Display disclaimer?|	Select yes to display your disclaimer in registration page. Users will not be able to register unless they tick a checkbox that says ‘I agree to the above’.|
|Registration disclaimer|	Enter the text of your registration disclaimer here. This has a default text that you may edit or change completely.|