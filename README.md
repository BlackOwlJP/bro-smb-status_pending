# bro-smb-status_pending

The presence of SMB2 Create Response with NT Status equal to STATUS_PENDING can create association problems (present also in Wireshark) with regard to the operations following the SMB2 Create Request message. 

More details: https://bro-tracker.atlassian.net/browse/BIT-1862

Patch merged in Bro version 2.6.
