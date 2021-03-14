┌──(kali㉿kali)-[~/Downloads/11-carve-fat]
└─$ bulk_extractor -o bulk_output 11-carve-fat.dd
bulk_extractor version: 1.6.0
Hostname: kali
Input file: 11-carve-fat.dd
Output directory: bulk_output
Disk Size: 64979456
Threads: 2
Attempt to open 11-carve-fat.dd
All data are read; waiting for threads to finish...
Time elapsed waiting for 2 threads to finish:
     (timeout in 60 min.)
Time elapsed waiting for 1 thread to finish:
    6 sec (timeout in 59 min54 sec.)
Thread 0: Processing 0

All Threads Finished!
Producer time spent waiting: 1.162 sec.
Average consumer time spent waiting: 0.114099 sec.
MD5 of Disk Image: 0069813c892a462f88dc6d376624f7d9
Phase 2. Shutting down scanners
Phase 3. Creating Histograms
Elapsed time: 7.92084 sec.
Total MB processed: 64
Overall performance: 8.20361 MBytes/sec (4.10181 MBytes/sec/thread)
Total email features found: 1
                                                                             
┌──(kali㉿kali)-[~/Downloads/11-carve-fat]
└─$ tree bulk_output              
bulk_output
├── aes_keys.txt
├── alerts.txt
├── ccn_histogram.txt
├── ccn_track2_histogram.txt
├── ccn_track2.txt
├── ccn.txt
├── domain_histogram.txt
├── domain.txt
├── elf.txt
├── email_domain_histogram.txt
├── email_histogram.txt
├── email.txt
├── ether_histogram.txt
├── ether.txt
├── exif.txt
├── find_histogram.txt
├── find.txt
├── gps.txt
├── httplogs.txt
├── ip_histogram.txt
├── ip.txt
├── jpeg_carved.txt
├── json.txt
├── kml.txt
├── ntfsusn_carved.txt
├── pii_teamviewer.txt
├── pii.txt
├── rar.txt
├── report.xml
├── rfc822.txt
├── sin.txt
├── sqlite_carved.txt
├── telephone_histogram.txt
├── telephone.txt
├── unrar_carved.txt
├── unzip_carved.txt
├── url_facebook-address.txt
├── url_facebook-id.txt
├── url_histogram.txt
├── url_microsoft-live.txt
├── url_searches.txt
├── url_services.txt
├── url.txt
├── vcard.txt
├── windirs.txt
├── winlnk.txt
├── winpe_carved.txt
├── winpe.txt
├── winprefetch.txt
└── zip.txt

0 directories, 50 files

