---
description: Disaster Recovery
---

# Disaster Recovery

Disaster Recovery -

Fault tolerance can be defined as the prevention of data loss if a network component fails

But in the event if the fault tolerance fails then disaster recovery will be our last option.

Disaster recover is the process of rebuilding an organizations data after a disaster has happened such as data loss.

So even if we implement a fault tolerance measures we still need to backup over data.

There are 3 different types if backups -

Full Incremental Differential

Full Backup -

All the data is simply copied and backed up into one tape.

This is the simplest form of backup because only one tape is used.

If you ever needed to restore the data then that one tape is all you would need for restoration.

But if your organization has a large amount of data then performing a full backup would not be efficient because the disadvantage of this that it takes the longest to perform.

Incremental Backup -

Includes all the data that has been changed since the last full or incremental backup.

Ex - Let’s say you have a company that does a full backup on a weekend and does incremental backups in weekdays.

The only data that is copied to tape is the data that has been changed since the last incremental backup which is each weekday.

So, Monday will only copy Monday’s data, Tuesday will only copy Tuesday’s data and so on.

The way an incremental backup knows which data has been changed is by what is called an archived bit.

This bit informs which files have been changed since the last full backup and it clears the archive bit when the backup is done.

Incremental Restore -

When you have to restore an incremental backup, you have to restore the full backup along with the incremental backups. \(FULL + INCREMENTAL \(in correct order\) = RESTORE\).

You have to restore the incremental in the same order as you backed them up.

Ex - You may have a full backup on weekends and incremental backup in weekdays.

You will go ahead and restore the full backup tape first and then will restore the incremental from Monday to Friday in correct order.

Differential Backup -

Includes all the data that has been changed since the last full backup.

Ex - A company does a full backup on a weekend and differential backup on the weekdays as data is being added to the database each weekday, the differential backup will backup the data that has been changed since the last weekend full backup.

Monday will copy Monday’s data, Tuesday will copy Monday’s and Tuesday’s data, Wednesday will copy Monday’s, Tuesday’s and Wednesday’s data and so on.

Each backup tape copies data not only from their own day but also from the previous days as well since the last full backup that was done on weekend.

The differential backup also uses the archive bit but it does not clear the archive bit when the differential backup is done.

Differential Restore -

You need to restore the last full backup and the last differential backup to completely restore the data.

Off site Storage -

Off site storage is where you can backup your data and have it stored in differential geographical locations for safety purposes.

Ex - You have office in Miami and you have off site storage in New York so if any natural disaster happens then you will still have the exact backup of the data.

Hot Spares -

Equipment that can be swapped out without the need of turning off the power.

Ex - If you had a server with multiple hot swappable hard drives and if your hard drive were to fail, you wouldn’t need to shutdown the server, you just simply remove the hard drive and replace it with the new one while the power is still is on.

Cold Spares -

Power must be turned off before replacing the piece of equipment.

