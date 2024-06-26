.. include:: ../chapters-img/settings-img.rst

.. index:: Settings

Settings
========

.. note:: Using this app, you can change the device settings.

Open the applications list

     |application-menu-button|

Open the Settings application

     |settings-icon|

You will be greeted with the following settings list:

    |settings-main-1|

The list goes on two screens:

    |settings-main-2|

The available options are grouped in three sections, plus in the :ref:`chapters/ui:In-app menu`:

    |settings-in-app-menu|

#. Personalization
    #. :ref:`chapters/settings:Themes`
    #. :ref:`chapters/settings:Language & region`
    #. :ref:`chapters/settings:Notification light`
    #. :ref:`chapters/settings:Profiles`
    #. :ref:`chapters/settings:Date and time`
    #. :ref:`chapters/settings:Display`
    #. :ref:`chapters/settings:Text input`
#. Connectivity
    #. :ref:`chapters/settings:Location`
    #. :ref:`chapters/settings:Internet connections`
    #. :ref:`chapters/settings:VoIP and IM accounts`
    #. :ref:`chapters/settings:Phone`
#. General
    #. :ref:`chapters/settings:Device lock`
#. In-app menu
    #. :ref:`chapters/settings:Restore original settings`
    #. :ref:`chapters/settings:Clear device`

Themes
------

You have a list of available themes that you can pick from, to have an uniform design look of the interface.

     |select-theme|

.. note:: You can install more themes from the :ref:`summary:Application Manager`.

.. index:: Language & region

Language & region
-----------------

You will be greeted with the following screen:

     |language-n-region|

The following options will be available:

#. :ref:`chapters/settings:Device language`
#. :ref:`chapters/settings:Date format (read-only)`
#. :ref:`chapters/settings:Date format`
#. :ref:`chapters/settings:Decimal separator (read-only)`
#. :ref:`chapters/settings:Thousands separator (read-only)`

.. warning:: Saving these settings will require the device to reboot

Device language
^^^^^^^^^^^^^^^

You will be shown a list, through which you can scroll and select your desired interface language:

     |device-language|

.. note:: You can also type to search, but you will need to have a method of :ref:`chapters/ui:Input and keyboard` layout which includes the potentially special characters of the language you search for, since native language names are being used.

Date format (read-only)
^^^^^^^^^^^^^^^^^^^^^^^

This shows how the date is being displayed based on the currently set :ref:`chapters/settings:Device language`.

Date format
^^^^^^^^^^^

.. note:: This is probably a bug, while it should be named Regional format, instead of date format. See :ref:`summary:Known bugs`.


You will be shown a list, through which you can scroll and select the country corresponding to the your desired regional format:

     |date-format|

Decimal separator (read-only)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This shows which decimal separator is being used, based on the currently set :ref:`chapters/settings:date format`.

Thousands separator (read-only)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This shows which thousands separator is being used, based on the currently set :ref:`chapters/settings:date format`.

.. index:: Notification light

Notification light
------------------

You will be shown a menu from where you select the desired settings regarding notifications using the LED light.

     |notification-light-1|

The options go on two screens:

     |notification-light-1|

The following options are available:

#. :ref:`chapters/settings:Device on`
#. :ref:`chapters/settings:Missed call`
#. :ref:`chapters/settings:Text message received`
#. :ref:`chapters/settings:E-mail message received`
#. :ref:`chapters/settings:Instant message received`
#. :ref:`chapters/settings:Charging`
#. :ref:`chapters/settings:Other notifications`

Check the situations when you would like to have notifications signaled by the LED (if your device has one - see see :ref:`chapters/devices:Device specific info [wip]`)

Device on
^^^^^^^^^

Use the notification light to show that the device is on, when the display is off.

Missed call
^^^^^^^^^^^

Notify missed calls.

Text message received
^^^^^^^^^^^^^^^^^^^^^

Notify when there's an incoming text message (SMS).

E-mail message received
^^^^^^^^^^^^^^^^^^^^^^^

Notify when there's a new e-mail message received.

Instant message received
^^^^^^^^^^^^^^^^^^^^^^^^

Notify when there's an incoming instant message (IM).

Charging
^^^^^^^^

Notify when the device's battery is charging.

Other notifications
^^^^^^^^^^^^^^^^^^^

Notify all other events.

.. index:: Sound profiles

Profiles
--------

Selecting *Profiles* gives you the list of the existing sound profiles.

Besides the default General and Silent, you can make your own custom profiles.

    |profiles-custom|

Here you have the following options:

#. :ref:`chapters/settings:Delete (profile)`
#. :ref:`chapters/settings:Edit (profile)`
#. :ref:`chapters/settings:New (profile)`

When finished modifying settings, tap on *Done*.

Delete (profile)
^^^^^^^^^^^^^^^^

Tap on *Delete* to remove the selected custom profile.

The default profiles cannot be deleted, so the *Delete* button won't be present if you have no custom profiles configured.

    |profiles-main|

Edit (profile)
^^^^^^^^^^^^^^

Tap on *Edit* to modify the selected profile.

Editing profiles gives the same options as when creating a :ref:`chapters/settings:New (profile)`.

New (profile)
^^^^^^^^^^^^^

Start by giving the new profile a name. See :ref:`chapters/ui:Input and keyboard` about how to input text.

    |profiles-new-name|

Then, when you tap on *Done*, a menu with options will appear.

    |profiles-new-settings-1|

The menu goes on more pages.

    |profiles-new-settings-2|

Some options' availability depends on enabling others.

    |profiles-new-settings-3|

We have the following settings for a profile:

#. :ref:`chapters/settings:Statusbar icon`
#. :ref:`chapters/settings:Vibrate`
#. :ref:`chapters/settings:Ringing tone`
#. :ref:`chapters/settings:SMS alert`
#. :ref:`chapters/settings:IM tone`
#. :ref:`chapters/settings:E-mail alert`
#. :ref:`chapters/settings:System sounds`
#. :ref:`chapters/settings:Key sounds`
#. :ref:`chapters/settings:Touch screen sounds`
#. :ref:`chapters/settings:Touch screen vibrate (profi_fi_touch_screen_vibrate)`
#. :ref:`chapters/settings:Autoanswer`
#. :ref:`chapters/settings:Autoanswer timer slider`
#. :ref:`chapters/settings:Disable proximity check`
#. :ref:`chapters/settings:Speaker`

Statusbar icon
""""""""""""""

Here you can choose which icon will be shown in the :ref:`chapters/ui:Status menu`.

    |profiles-statusbar-icon|

Tapping on the folder icon allows you to pick a custom icon from the :term:`filesystem`.

    |profiles-statusbar-icon-custom|

Vibrate
"""""""

Checking this enables vibration for the current profile.

Ringing tone
""""""""""""

Here you can select which sound will be played as ringing for an incoming call.

    |profiles-ringing-tone|

Tapping on more allows you to pick a custom audio file from the :term:`filesystem` as ringing tone.

    |profiles-add-tone|

SMS alert
"""""""""

Here you can select which sound will be played as an alert for an incoming text message (SMS).

    |profiles-sms-alert|

Tapping on more allows you to pick a custom audio file from the :term:`filesystem` as SMS alert, similar as for picking a custom :ref:`chapters/settings:Ringing tone`.

IM tone
"""""""

Here you can select which sound will be played as an alert for an incoming instant message (IM).

    |profiles-im-alert|

Tapping on more allows you to pick a custom audio file from the :term:`filesystem` as IM alert, similar as for picking a custom :ref:`chapters/settings:Ringing tone`.


E-mail alert
""""""""""""

Here you can select which sound will be played as an alert for a new email.

    |profiles-email-alert|

Tapping on more allows you to pick a custom audio file from the :term:`filesystem` as e-mail alert, similar as for picking a custom :ref:`chapters/settings:Ringing tone`.

System sounds
"""""""""""""

Here you can select the volume level of system sounds.

    |profiles-system-sounds|

You can select between:

* **Off** - there will be no system sounds played.
* **Level 1** - the system sounds will be less loud
* **Level 2** - the system sounds will be louder

Key sounds
""""""""""

Here you can select the volume level of key sounds (sounds made when pressing/tapping a key on the keyboard).

    |profiles-key-sounds|

You can select between:

* **Off** - pressing keys will make no sound.
* **Level 1** - the key sounds will be less loud
* **Level 2** - the key sounds will be louder

Touch screen sounds
"""""""""""""""""""

Here you can select the volume level of touch screen sounds (sounds made when tapping on the screen).

    |profiles-touch-screen-sounds|

You can select between:

* **Off** - touching the screen will make no sound.
* **Level 1** - the touch screen sounds will be less loud
* **Level 2** - the touch screen sounds will be louder

Touch screen vibrate (profi_fi_touch_screen_vibrate)
""""""""""""""""""""""""""""""""""""""""""""""""""""

Check to enable vibrating when touching the screen.

Autoanswer
""""""""""

Check to enable automatic call answering.

Autoanswer timer slider
"""""""""""""""""""""""

Set the the time after which the call is automatically answered.

Disable proximity check
"""""""""""""""""""""""

Check to disable proximity check when automatically answering calls.

If this is checked, the call will be automatically answered even if the device is not held to the ear.

Speaker
"""""""

Check to answer the call in loudspeaker mode (?).

Date and time
-------------

You will be greeted with the following menu:
     |date-time-main|

The following options will be available:

#. :ref:`chapters/settings:24-hr clock`
#. :ref:`chapters/settings:Time zone`
#. :ref:`chapters/settings:Date`
#. :ref:`chapters/settings:Time`

24-hr clock
^^^^^^^^^^^
When ticked, the clock will be displayed as 24-hour (also called military time).
    |date-time-24h|

Untick it, and hit the Save button, and then the clock will be displayed as 12-hour clock (AM and PM).
    |date-time-12h|

.. index:: Time zone

Time zone
^^^^^^^^^
You will be shown a map, where the current place is shown (and its time zone and name written on the bottom of the screen), and from where you can change it, by selecting the place which is closest to your location (or one which is in your local timezone). You can select the place by choosing it from the map.
    |choose-time-zone-London|

When ready, tap on *Done*, at the top of the screen, if you want to save the changes.

.. note:: You can also search for a place by tapping on the magnifier on top of the screen.
    |choose-time-zone-search|

And then you can type to search for a place to select as your local time place.
    |choose-time-zone-select-Chisinau|

Your new time zone location will then be displayed.
    |choose-time-zone-Chisinau|

When ready, tap on *Done*. Otherwise, search for a different place.

.. index:: Date setting

Date
^^^^
A menu will appear, from which you can select the current date.
    |adjust-date|

Then tap on *Done* when ready selecting.

.. index:: Time setting

Time
^^^^
A menu will appear, from which you can select the current time.
    |adjust-time|

Then tap on *Done* when ready selecting.

.. index:: Display

Display
-------

Here you can adjust the display settings.

|display|

You have the following options:

#. :ref:`chapters/settings:Brightness`
#. :ref:`chapters/settings:Backlight time-out`
#. :ref:`chapters/settings:Lock screen automatically`
#. :ref:`chapters/settings:Display stays lit when charging`

.. index:: Brightness

Brightness
^^^^^^^^^^

By dragging the slider to the left or right, you can decrease, or respectively increase the display brightness level, in five steps.

.. note:: :ref:`summary:Unexpected behavior`: From the five steps available, the last two seems to correspond to the same brightness level (tested using :ref:`chapters/devices:Droid 4`), so this means that there are only four brightness levels.

Backlight time-out
^^^^^^^^^^^^^^^^^^

Here you can set the backlight timeout (how much the screen will be still on after the last interaction with the device).

|display-backlight-timeout|

You have the following options:

**0 seconds** - The display will never turn off automatically

**10 seconds** - The display will turn off after 10 seconds of user inactivity

**30 seconds** - - The display will turn off after 30 seconds of user inactivity

**1 minute** - The display will turn off after 1 minute of user inactivity

**2 minutes** - The display will turn off after 2 minutes of user inactivity

.. note:: You can temporarily set the backlight timeout to zero, thus disabling automatic turn-off, by using the **Brightness applet menu** from the #. :ref:`chapters/ui:Brightness slider`. This won't change the timeout settings above.

Lock screen automatically
^^^^^^^^^^^^^^^^^^^^^^^^^

Check to lock screen automatically when it turns off.

Display stays lit when charging
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Check to always keep the display on when charging the device (when power is plugged in).

.. index:: Text input
.. index:: Keyboard settings

Text input
----------

When you select Text input from :ref:`chapters/settings:Settings`, the following menu is shown:

    |text-input-1|

The menu is long, so it goes on two pages:

    |text-input-2|

You will have the following options:

#. :ref:`chapters/settings:Hardware keyboard layout`
#. :ref:`chapters/settings:Use virtual keyboard`
#. :ref:`chapters/settings:Word completion`
#. :ref:`chapters/settings:Auto-capitalization`
#. :ref:`chapters/settings:Insert space after word`
#. :ref:`chapters/settings:1st language`
#. :ref:`chapters/settings:2nd language`
#. :ref:`chapters/settings:Dictionary (of the 1st language)`
#. :ref:`chapters/settings:Dictionary (of the 2nd language)`
#. :ref:`chapters/settings:Use dual dictionaries`

Hardware keyboard layout
^^^^^^^^^^^^^^^^^^^^^^^^

    |hardware-keyboard-layout|

.. note:: The layout for the hardware keyboard doesn't seem to change. Possible bug. See :ref:`summary:Known bugs`

Use virtual keyboard
^^^^^^^^^^^^^^^^^^^^

This enables the use of virtual (on-screen) keyboard.

If this is disabled, the virtual keyboard won't work, but you can still use the hardware keyboard, if your device has one (see :ref:`chapters/devices:Device specific info [wip]`).

Word completion
^^^^^^^^^^^^^^^

This enables automatic word completion.

.. note:: Word completion doesn't seem to work. Possible bug. See :ref:`summary:Known bugs`

Auto-capitalization
^^^^^^^^^^^^^^^^^^^

This enables automatic capitalization of words at the beginning of sentences (the first letter after *full stop* + *space*, or *full stop* + *new line* will be uppercase - the first letter after only *new line* won't be uppercased).
The effects of this setting can be changed by using the *SHIFT* key (for the exact key name on your device, see :ref:`chapters/devices:Device specific info [wip]`).

Insert space after word
^^^^^^^^^^^^^^^^^^^^^^^

This option enables adding a space after each word chosen through the :ref:`chapters/settings:Auto-capitalization` option.

1st language
^^^^^^^^^^^^

From here you can select the layout number one, of the virtual keyboard.

    |keyboard-first-language|

You can have two layouts set, between which you can switch. Select the second layout from the option :ref:`chapters/settings:2nd language`.

Dictionary (of the 1st language)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    |keyboard-first-language-dictionary|

2nd language
^^^^^^^^^^^^

From here you can select the layout number two, of the virtual keyboard.

    |keyboard-second-language|

You can have two layouts set, between which you can switch. Select the first layout from the option :ref:`chapters/settings:1st language`.

Dictionary (of the 2nd language)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    |keyboard-second-language-dictionary|

Use dual dictionaries
^^^^^^^^^^^^^^^^^^^^^

This option is active only if you have two languages set. Then, the :ref:`chapters/settings:Text input` menu's second page looks like this:

    |text-input-two-languages|

Then, when this is enabled, words are being searched for in both languages, when using :ref:`chapters/settings:Word completion`.

.. index:: Location settings

Location
--------

Here you can adjust the location-related settings, such as those for the GPS, or for the network-based location detection:

    |location-1|

There's also a second page:

    |location-2|

The options here are in two categories:

#. :ref:`chapters/settings:GPS`
#. :ref:`chapters/settings:Network positioning`

.. index:: GPS settings

GPS
^^^

For the :term:`GPS`, the options are the following:

#. :ref:`chapters/settings:Enable (GPS)`
#. :ref:`chapters/settings:GPS device`
#. :ref:`chapters/settings:Pair new device`

Enable (GPS)
""""""""""""

Checking this enables the :term:`GPS` device, using it for satellite-based location detection.

GPS device
""""""""""

Here you can select between the available :term:`GPS` devices, such as the internal one, or any externally connected ones.

    |gps-device|

Pair new device
"""""""""""""""

Here you can connect to (pair) an external :term:`GPS` device, to use it for location detection.

.. note:: :ref:`summary:Unexpected behavior`: Pressing on :ref:`chapters/settings:Pair new device` to pair a new external :term:`GPS` device seems to not do anything.

Network positioning
^^^^^^^^^^^^^^^^^^^

Here are the settings for the network-based location detection:

#. :ref:`chapters/settings:Enable (Network positioning)`
#. :ref:`chapters/settings:Location server`

.. note:: Possible :ref:`summary:Leftovers`: The network positioning service seems to not work. supl.nokia.com is given as default server, which seems to not be reachable anymore.

Enable (Network positioning)
""""""""""""""""""""""""""""

Checking this enables network positioning, using it for mobile network-based location detection.

Location server
"""""""""""""""

Choose the server which is being used to provide network positioning.

.. index:: Internet connections

Internet connections
--------------------

From here you can configure the ways to connect to :term:`internet`, through :term:`Wi-Fi`, or through mobile networks.

    |internet-connections-main|

You have the following options:

#. :ref:`chapters/settings:Connect automatically`
#. :ref:`chapters/settings:Search interval`
#. :ref:`chapters/settings:Switch to Wi-Fi when available`
#. :ref:`chapters/settings:Connections`
#. :ref:`chapters/settings:Save (Internet connections)`

.. tip:: If you just want to connect to a visible :term:`Wi-Fi` network, or to an already-known-to-work mobile connection, it's easier to do it from the :ref:`chapters/ui:Internet connection menu`.

Connect automatically
^^^^^^^^^^^^^^^^^^^^^

This options specifies whether any type of connection should be automatically activated, and which.

    |internet-connect-automatically|

#. :ref:`chapters/settings:Always ask`
#. :ref:`chapters/settings:Wi-Fi`
#. :ref:`chapters/settings:Mobile connection (Orange)`
#. :ref:`chapters/settings:Any connection`

Always ask
""""""""""

Never automatically connect, ask each time instead.

Wi-Fi
"""""

Automatically connect to available saved :term:`Wi-Fi` networks.

Mobile connection (Orange)
""""""""""""""""""""""""""

Automatically connect to mobile data.

.. note:: In this case the available network was Orange, so the name of the network appears here as an option for auto-connect.

Any connection
""""""""""""""

Connect automatically to any available connection, be it :term:`Wi-Fi` or mobile.

.. note:: To set the priority, :term:`Wi-Fi` over mobile, or the other way around, see :ref:`chapters/settings:Switch to Wi-Fi when available`.

Search interval
^^^^^^^^^^^^^^^

    |internet-connections-search-interval|


Switch to Wi-Fi when available
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Check to give priority to :term:`Wi-Fi` over mobile data, when a saved :term:`Wi-Fi` connection is available.

Especially useful when connecting to :ref:`chapters/settings:Any connection` is active.

Connections
^^^^^^^^^^^

Here you can see the list of saved :term:`Wi-Fi` networks, and the available mobile network:

    |internet-connections-list|

And you have the following options:

#. :ref:`chapters/settings:New (Wi-Fi connection)`
#. :ref:`chapters/settings:Edit (Wi-Fi connection)`
#. :ref:`chapters/settings:Edit (Mobile connection)`
#. :ref:`chapters/settings:Delete (Connections)`
#. :ref:`chapters/settings:Done (Connections)`

New (Wi-Fi connection)
""""""""""""""""""""""

You will be carried through a multi-page configuration wizard.

On each of the steps, after you finished configuring the options on that page, you go forward by pressing *Next*, or backwards, to the previous page, by pressing *Previous*.

    |internet-connections-wifi-setup|

Tap *Next* to continue.

    |internet-connections-wifi-name|

Write a network name. See :ref:`chapters/ui:Input and keyboard` about how to input text.

The network name is a local name, like a bookmark, so it can be different than the network's actual name (SSID).

Tap *Next* to continue.

    |internet-connections-wifi-scan|

You will be asked whether to scan for available :term:`Wi-Fi` networks.

If you want to add a hidden network, or one that is not in range, select *No* here.

You will then be able to manually add the network settings:

    |internet-connections-wifi-manual-1|

#. Network name (SSID)
#. Network is hidden (keep checked if the network you want to add is hidden)
#. Network mode:

    |internet-connections-wifi-manual-2|

    * Infrastructure (AP-mode)
    * Ad hoc (No need of an AP)
#. Security method:

    |internet-connections-wifi-manual-3|

    * None
    * :term:`WEP`
    * :term:`WPA` :term:`pre-shared key`
    * :term:`WPA` with :term:`EAP`

If you select *Yes* when you are asked to scan for :term:`Wi-Fi` networks, then you will receive the list of available :term:`Wi-Fi` networks:

    |internet-connections-wifi-available|

Select the desided one.

Tap *Next* to continue.

    |internet-connections-wifi-key|

If the network is protected, you will be asked to input the key (password).

Tap *Next* to continue.

    |internet-connections-complete|

The configuration should be done now, but if you need advanced settings, tap on *Advanced*, otherwise just tap on *Finish*.

If you select Advanced, you will be shown this four-tabbed menu, from where you can make the changes you need for your particular situation.

The first tab is *Proxies*. If you need to setup a proxy for this connection, you can do this here.

    |internet-connections-wifi-settings-1|

    |internet-connections-wifi-settings-2|

Check *Use proxy* to enable it. Then you have the following options:

    * **HTTP proxy**
    * **Port number** (for HTTP)
    * **HTTPS proxy**
    * **Port number** (for HTTPS)
    * **FTP proxy**
    * **Port number** (for FTP)
    * **RTSP proxy**
    * **Port number** (for RTSP)
    * **Do not use proxy for** (Domains for which the proxy shouldn't be used)
    * **Automatic configuration** (Check to use an automatic proxy configuration)
    * **Web address** (The address where the automatic proxy configuration is to be found)

The second tab is :term:`IP` Address. :term:`IP` related settings go here.

    |internet-connections-wifi-settings-3|

If you want to set :term:`IP` addresses manually, and not use :term:`DHCP` to get the addresses automatically, uncheck *Auto-retrieve IP address* and then set manually the following:

    * **IP address**
    * **Subnet mask**
    * **Default gateway**

    |internet-connections-wifi-settings-4|

If you want to set-up :term:`DNS` manually, uncheck *Auto-retrieve DNS* and then set manually the following:

    * **Primary DNS address**
    * **Secondary DNS address**

The third tab is *Providers*

    |internet-connections-wifi-settings-5|

The options are:

    * **Provider type**
    * **Provider ID**

The fourth tab is *Other*. Here you can find the other settings, not belonging to the other categories:

    |internet-connections-wifi-settings-6|

    * **Wi-Fi transmission power** (How much power the device outputs while connected to :term:`Wi-Fi`, the default being 100mW)
    * **WPA2-only mode** (Only :term:`WPA2` will be allowed as a protocol for securing :term:`Wi-Fi` connections)
    * **Power saving** (The level of :term:`Wi-Fi` power saving)


Edit (Wi-Fi connection)
"""""""""""""""""""""""

Here you can edit the settings of a :term:`Wi-Fi` connection. Tap on *Finish* on any step, when done.

The steps are almost the same as when creating a :ref:`chapters/settings:New (Wi-Fi connection)`.

Edit (Mobile connection)
""""""""""""""""""""""""

Here you can edit the settings of a mobile connection. Tap on *Finish* on any step, when done.

    |internet-connections-mobile-edit-1|

You can edit the *Connection name*.

Tap *Next* to continue.

    |internet-connections-mobile-edit-2|

#. Access point name (:term:`APN`)
#. User name (The user name for the mobile data connection, it might not be required)
#. Password (The password for the mobile data connection, it might not be required)

Tap *Next* to continue.

    |internet-connections-complete|

The configuration should be done now, but if you need advanced settings, tap on *Advanced*, otherwise just tap on *Finish*.

The advanced settings are almost the same as for creating a :ref:`chapters/settings:New (Wi-Fi connection)`.

Delete (Connections)
""""""""""""""""""""

It deletes the currently selected :term:`Wi-Fi` connection (inactive for mobile connections).

Done (Connections)
""""""""""""""""""

Tap here when done configuring, to exit the :ref:`chapters/settings:Connections` menu and return to :ref:`chapters/settings:Internet connections`.

Save (Internet connections)
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Tap here when done configuring, to save the settings made, and exit the :ref:`chapters/settings:Internet connections` menu.

.. index:: VoIP accounts
.. index:: IM accounts

VoIP and IM accounts
--------------------

Here you can edit the settings of VoIP and IM accounts.

    |accounts|

Selecting an account will allow you to edit its settings, which is the same as creating a new account. See below how to create new accounts.

Tapping on **New** will allow you to configure new accounts.

When you configure a new account, or if you have no accounts set, you will be shown a list of services from which you can pick to configure your accounts with.

    |account-setup-service|

You have the following options (protocol, and in brackets, the connection manager):

#. :ref:`chapters/settings:IRC (idle)`
#. :ref:`chapters/settings:Jabber (gabble)`
#. :ref:`chapters/settings:SIMPLE (haze)`
#. :ref:`chapters/settings:XMPP (haze)`

.. index:: IRC accounts

IRC (idle)
^^^^^^^^^^

Here you can configure an :term:`IRC` account, using the *idle* connection manager.

    |idle-irc-account-setup|

You have the following basic options:

#. :ref:`chapters/settings:Nickname (accounts_fi_nickname)`
#. :ref:`chapters/settings:Server (accounts_fi_server)`
#. :ref:`chapters/settings:Real name (accounts_fi_real_name)`

Nickname (accounts_fi_nickname)
"""""""""""""""""""""""""""""""

The nickname displayed in the chat server and channels.

Server (accounts_fi_server)
"""""""""""""""""""""""""""

The address of the server to connect to.

Real name (accounts_fi_real_name)
"""""""""""""""""""""""""""""""""

The real name of the user.

For more settings, tap on *Advanced settings*.

    |idle-irc-settings|

You will have the following advanced options:

#. :ref:`chapters/settings:User name`
#. :ref:`chapters/settings:Password`
#. :ref:`chapters/settings:Port`
#. :ref:`chapters/settings:Use SSL`

User name
"""""""""

The user name of the account, if you need one to connect to the server.

Password
""""""""

The password of the account, if you need one to connect to the server.

Port
""""

The network port used to connect to the server (to modify it if it's different than the default).

Use SSL
"""""""

Check to use an :term:`SSL` connection to the server.

.. index:: Jabber accounts

Jabber (gabble)
^^^^^^^^^^^^^^^

Here you can configure a :term:`Jabber` (now called :term:`XMPP`) account, using the *gabble* connection manager.

    |gabble-jabber-account-setup|

You have the following options:

**Register new account** - If you don't already have an account, tap here to go to :ref:`chapters/settings:New Jabber account (gabble)`

**Address** - If you already have a :term:`Jabber` (:term:`XMPP`) account, you can just enter your XMPP address (or :term:`JID` - Jabber ID) here

**Password** - ...and here, the corresponding password.

**Advanced settings** - If you need special settings, tap here, to go to :ref:`chapters/settings:Advanced settings (Jabber)`

Then tap on **Sign in**, to connect.

Advanced settings (Jabber)
""""""""""""""""""""""""""

Here are some extra settings, in case you need a special configuration.

    |gabble-jabber-settings-1|

They go on two pages.

    |gabble-jabber-settings-2|

Available options:

**Connect to server** - The address of the server to connect to, in case it's different than the one in the address.

**Port** - The port on the server to connect to.

**Resource** - The identifier (name) of the client/device. Use this to differentiate between your devices connected through the same account.

**STUN server** - The :term:`STUN` server to connect to, in case it's needed, if you are behind a :term:`NAT`.

**STUN port** - The port of the :term:`STUN` server to connect to.

**Encryption required** - Check if encryption is required for making the connection to the server.

**Use old SSL** - Use the old :term:`SSL` protocol, and not the new :term:`TLS` protocol.

**Ignore SSL certificate errors** - Check to ignore :term:`SSL` certificate errors, for instance if using a self-signed or an expired :term:`Digital certificate`.

New Jabber account (gabble)
"""""""""""""""""""""""""""

Here you can register a new :term:`Jabber` (now called :term:`XMPP`) account, on a server of your choice.

    |gabble-jabber-new|

**Address** - Enter here the XMPP address (or :term:`JID` - Jabber ID) you want to register, in the form of user@server.

**Password** - ...and here, the chosen new password (See here :ref:`summary:How to choose a good password`).

**Verify password** - Enter the chosen password here, to verify that you entered it correctly.

Then tap on **Register**.

.. note:: If registering doesn't work, check if that particular server allows this.

.. index:: SIP accounts

SIMPLE (haze)
^^^^^^^^^^^^^

Here you can configure a :term:`SIMPLE` (based on :term:`SIP`) account, using the *haze* connection manager.

    |haze-simple-account-setup|

Available options:

**Address** - The :term:`SIP address` (read-only)

**Password** - The password of the :term:`SIP` account

**Advanced settings** - They're called *advanced settings*, but you will most likely need to configure them, so then tap here, to go to :ref:`chapters/settings:Advanced settings (SIMPLE)`.

Then tap on **Sign in**, to connect.

Advanced settings (SIMPLE)
""""""""""""""""""""""""""

Here are some extra settings, which you will most likely need:

    |haze-simple-settings-1|

They go on two pages.

    |haze-simple-settings-2|

Available options:

**User name** - The user name of the :term:`SIP` account.

**Transport** - Pick the transport mode, between **Auto**, **TCP**, **UDP** or **TLS**.

    |haze-simple-transport|

**Outbound proxy** - The :term:`SIP` server used as a proxy for outbound connections.

**Port** - The port on the :term:`SIP` server to connect to.

**Discover public address** - Discover your public address.

**Loose routing** - Enable loose routing, which is being used since SIP version 2. It might break compatibility with some servers having older versions.

**Keep-alive mechanism** - Select the method of keeping the connection active between the device and the server.

|haze-simple-keepalive-mechanism|

**Keep-alive period** - Select how often to check if the connection between the device and the server is active.

    |haze-simple-keepalive-interval|

**Auto-detect STUN** - Check to enable automatic detection of the :term:`STUN` server.

.. index:: XMPP accounts

XMPP (haze)
^^^^^^^^^^^

Here you can configure an :term:`XMPP` (formerly :term:`Jabber`) account, using the *haze* connection manager.

The procedure is the same as for :ref:`chapters/settings:Jabber (gabble)`.

    |haze-xmpp-account-setup|

You have the following options:

**Register new account** - If you don't already have an account, tap here to go to :ref:`chapters/settings:New XMPP account (haze)`

**Address** - If you already have a :term:`Jabber` (:term:`XMPP`) account, you can just enter your XMPP address (or :term:`JID` - Jabber ID) here

**Password** - ...and here, the corresponding password.

**Advanced settings** - If you need special settings, tap here, to go to :ref:`chapters/settings:Advanced settings (XMPP)`

Then tap on **Sign in**, to connect.

Advanced settings (XMPP)
""""""""""""""""""""""""

The settings are the same as :ref:`chapters/settings:Advanced settings (Jabber)`

New XMPP account (haze)
"""""""""""""""""""""""

The procedure is the same as for a :ref:`chapters/settings:New Jabber account (gabble)`

.. index:: Phone settings

Phone
-----

Here you can edit the settings of telephony. When done, tap on *Save*.

The settings go on more pages, and are split into three categories:

#. :ref:`chapters/settings:Call`
#. :ref:`chapters/settings:Network`
#. :ref:`chapters/settings:SIM card`

    .. note:: The availability and the configuration of some options depend on the mobile network operator.

    |phone-1|

    |phone-2|

    |phone-3|

    |phone-4|

Call
^^^^

Send my caller ID
"""""""""""""""""

Options about :term:`Caller ID`

Call waiting
""""""""""""

Check to enable :term:`Call waiting`.

Call forwarding
"""""""""""""""

Options about :term:`Call forwarding`

Forward to
""""""""""

Destination of the forwarded calls, if :ref:`chapters/settings:Call forwarding` is active.

Network
^^^^^^^

Network selection
"""""""""""""""""

Options about network selection:

**Automatic** - automatically select the first available authorized one

**Manual** - manually pick from the authorized ones

Network mode
""""""""""""

Select the network mode:

**Dual** - Automatically switch between the best available type (:term:`3G` or :term:`2G`).

**3G** - Use only :term:`3G` networks

**GSM** - Use only :term:`GSM` (:term:`2G`) networks

    |phone-network-mode|

.. index:: Roaming for data

Data roaming
""""""""""""

Options about mobile data connection in :term:`Roaming`:

**Always ask** - Always ask before enabling mobile data connection when in :term:`Roaming`.

**Always allow** - Always enable mobile data connection, even when in :term:`Roaming`.

    |phone-data-roaming|

Home network data counter
"""""""""""""""""""""""""

Here you can see the amount of mobile data used in the home network (the network of your provider).

    |phone-home-network-data|

Options available:

**Sent (read only)** - the amount of sent data

**Received (read only)** - the amount of received data

**Cleared (read only)** - last time the counter was cleared

**Enable transfer warning** - Enable being warned when the amount of transferred data exceeds a certain threshold.

**Display warning for every** - When to be warned about the amount of transferred data. Enabled only if *Enable transfer warning* is active.

Roaming network data counter
""""""""""""""""""""""""""""

Here you can see the amount of mobile data used in :term:`Roaming` (other networks than of your provider's).

    |phone-home-roaming-data|

The settings are the same as for :ref:`chapters/settings:Home network data counter`.

.. index:: SIM card settings

SIM card
^^^^^^^^

Here there are options about the :term:`SIM` card.

PIN code request
""""""""""""""""

Check to enable asking for the PIN code to enable the :term:`SIM` card.

PIN code
""""""""

Set the PIN code.

Device lock
-----------

Here there are settings for locking the access to the device (also called "locking the screen").

    |device-lock|

You have the following options:

#. :ref:`chapters/settings:Autolock`
#. :ref:`chapters/settings:Change lock code`

Autolock
^^^^^^^^

This option sets the automatic lock of the device after a certain amount of time, or disables this.

    |device-lock-auto|

Available options:

**Disabled**

**After 5 minutes**

**After 10 minutes**

**After 30 minutes**

**After 1 hour**

Change lock code
^^^^^^^^^^^^^^^^

This option sets the lock code used to unlock the device, after it's been automatically or manually locked.

To change the code, you'll be asked to first enter the current code.

    |device-lock-enter-current|

.. index:: Restore original settings

Restore original settings
-------------------------

Tap on **Restore original settings** in the :ref:`chapters/ui:In-app menu`

    |settings-in-app-menu|

This option restores the original settings of the phone, and then reboots the device.

    |restore-original-settings|

Tap **Yes** to perform this operation.

Tap **No** to cancel.

.. warning:: If you tap on **Yes**, all the modifications you did in settings will be lost, including internet connection settings and accounts.

.. index:: Clear device

Clear device
------------

Tap on **Clear device** in the :ref:`chapters/ui:In-app menu`

    |settings-in-app-menu|

This option clears all user data, except for installed programs, and then reboots the device.

    |clear-device|

Tap **Yes** to perform this operation.

Tap **No** to cancel.

.. warning:: If you tap on **Yes**, all your modifications and files on the device will be lost, except for installed programs.
