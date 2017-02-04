# event-scheduler
It was built on Netbeans. External jar files used were jcalender and mysql-connector.
</br>It consists of two parts:
</br></br><b>1-> Event Scheduler application</b>
</br>Users can login as admin or event manager.
</br>Admin has special previliges. He/She can view booked events and add or delete venues, free timeslots, usergroups and users.
</br>Event manager can view booked events. He/She can book any timeslot from the set of free timeslots on any venue.
</br>Any usergroup can be blocked from any event.
</br></br><b>2-> Event Scheduler Server</b>
</br>It is UI-less and handles the booking requests using multithreading and socket-programming.
</br>Database used was MySQL.
