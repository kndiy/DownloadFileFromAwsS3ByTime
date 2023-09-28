# DownloadFileFromAwsS3ByTime
Object to help downloading files (byte array actually) from AWS S3 using time String (yyyyMMddHHmmss) or last/ first modified,
Create a TreeMap of all object keys inside a specific S3 folder,
Either choose FILE_LOCATION: FIRST/LAST or specify your choice of time in String format: yyyyMMddHHmmss to initiate the download,
The TreeMap is saved as an instant variable so that we can re-querry without parsing all object summaries again
