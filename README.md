# Zfile4aws_V1R4_Beta
Zfile4aws is a java mainframe tool used to send and retrieve z/OS sequential file from an AWS S3 cloud type.
Data source could be any sequential file type or format (RECFM=PS).
Zfile4aws support tape files like DFDSS backup and LBI type dataset (Large physical block size).
With Zfile4aws sequential data could be compressed, encrypted and segmented before it is shipped to the cloud.
In theory, there is no limit in dataset size that could be send to the cloud. Limits depends on your environment and/or your cloud service provider.
Zfile4aws is running in batch mode (JZOS) only.
HFS, ZFS and OMVS file types are also supported

This product is a java mainframe standalone application design to run on z/OS system (z/OS 2.2 and higher).
