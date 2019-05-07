======================
Using the calendar app
======================

.. note:: The calendar app is not enabled by default and needs to be installed
          separately from our App Store. Please ask your Administrator for it.

The Nextcloud Calendar app works similar to other calendar applications you can
sync your Nextcloud calendars and events with.

When you first access the Calendar app, a default first calendar will be
pre-generated for you.

.. figure:: images/calendar_application.png

Managing your calendars
-----------------------

Import a Calendar
~~~~~~~~~~~~~~~~~

If you want to transfer your calendar and their respective events to your Nextcloud
instance, importing is the best way to do so.

.. figure:: images/calendar_settings.png
            :scale: 50%

1. Click on the settings-icon labeled with ``Settings & Import`` at the left-bottom.

2. After clicking on ``+ Import Calendar`` you can select one or more calendar files
   from your local device to upload.

3. The upload can take some time and depends on how big the calendar you import
   is.

.. note:: The Nextcloud Calendar application only supports iCalendar-compatible
          ``.ics``-files, defined in RFC 5545.

Create a new Calendar
~~~~~~~~~~~~~~~~~~~~~

If you plan to setup a new calendar without transferring any old data from your
previous calendar, creating a new calendar is the way you should go.

.. only:: html

  .. figure:: images/calendar_create.gif

1. Click on ``+ New Calendar`` in the left sidebar.

2. Type in a name for your new calendar, e.g. "Work", "Home" or "Studies".

3. After clicking on the checkmark, your new calendar is created and can be
   synced across your devices, filled with new events and shared with your friends
   and colleagues.

Edit, Download or Delete a Calendar
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Sometimes you may want to change the color or the entire name of a previous
imported or created calendar. You may also want to export it to your local
hard drive or delete it forever.

.. note:: Please keep in mind that deleting a calendar is a irreversible action.
          After deletion, there is no way of restoring the calendar unless you
          have a local backup.

.. figure:: images/calendar_dropdown.png
            :scale: 50%

1. Click on the three-dot-menu of the respective calendar.

.. figure:: images/calendar_editing.png
            :scale: 50%

2. Click on ``Edit``, ``Download`` or ``Delete``.

Subscribe to a Calendar
~~~~~~~~~~~~~~~~~~~~~~~

You can subscribe to iCal calendars directly inside of your Nextcloud. By
supporting this interoperable standard (RFC 5545) we made Nextcloud calendar
compatible to Google Calendar, Apple iCloud and many other calendar-servers
you can exchange your calendars with.

1. Click on ``+ New Subscription`` in the left sidebar.
2. Type in the link of the shared calendar you want to subscribe to.

Finished. Your calendar subscriptions will be updated regularly.

Managing Events
---------------

Create a new event
~~~~~~~~~~~~~~~~~~

Events can be created by clicking in the area when the event is scheduled.
In the day- and week-view of the calendar you just click, pull and left your
cursor over the area when the event is taking place.

.. only:: html

  .. figure:: images/calendar_new-event_week.gif

The month-view only requires a single click into the area of the specific day.

.. only:: html

  .. figure:: images/calendar_new-event_month.gif

After that, you can type in the events name (e.g. **Meeting with Lukas**), choose
the calendar in which you want to choose the event (e.g. **Personal**, **Work**)
check and concretize the time span or set the event as all-day event.

If you want to edit advanced details such as the **Location**, a **Description**,
**Attendees**, **Reminders** or to set the event as a repeating-event click on
the ``More...``-button to open the advanced sidebar-editor.

.. note:: If you always want to open the advanced sidebar-editor instead of the
          simple event editor popup, you can set a ``Skip simple event
          editor``-checkmark in the ``Settings & Import``-section of the app.

Clicking on the blue ``Create``-button will finally create the event.

Edit or Delete an event
~~~~~~~~~~~~~~~~~~~~~~~

If you want to edit or delete a specific event, you just need to click on it.
After that you will be able to re-set all of the events details and open the
advanced sidebar-editor by clicking on ``More...``.

Clicking on the blue ``Update``-button will update the event. Clicking on the
``Cancel``-button will not save your edits.

If you click on the red ``Delete``-button the event will be removed from your
calendar.

Birthday calendar
-----------------

The birthday calendar is a auto-generated calendar which will automatically
fetch the birthdays from your contacts. The only way to edit this calendar is by
filing your contacts with birthday dates. You can not directly edit this calendar
from the calendar-app.

.. note:: If you do not see the birthday calendar, your Administrator may has
          disabled this for your server.


National holidays calendar
--------------------------

Nextcloud does not yet offer internal support for displaying the national holidays of your country in the calendar app. However, you can easily implement this feature by importing a national holiday calendar file from a third-party source. Here is how to do this:

1. Navigate in your browser to the repository of national holiday calendar files produced by the Thunderbird community for the Lightning add-on: https://www.thunderbird.net/en-US/calendar/holidays/

2. Download the ICS file for your region.

3. Go to the **calendar app** in your Nextcloud host.

4. Click on ``Settings and Import``

5. Click on ``Import calendar``. 

6. Select the ICS file you downloaded from Thunderbird.net

Nextcloud will import this calendar file and your national holidays will now be displayed in the app. The default title of the new calendar is the filename of imported the ICS file; this can be edited if so wish like any other calendar name. This calendar's events (holidays) can be edited like those of any standard Nextcloud calendar. 

If you live in a region for which a national holiday file is not yet available, please consider creating one yourself (very easy in the Lightning add-on, for example), exporting it from Thunderbird, and uploading it to the Thunderbird site to share with others. 








