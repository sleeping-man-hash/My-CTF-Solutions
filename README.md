Challenge 1 — Nothing to See Here
The webpage appears completely empty. Inspecting the page’s html source code reveals the html comments which are not visible on the webpage but are part of the data received by the browser.

Challenge 2 — Mystery String
We are presented with an alphanumeric sequence that appears to be encrypted. It’s format suggests it’s Base64 encoding. I used the Base64 decoding command in the linux terminal to decode it. 

Challenge 3 — Picture Perfect
The challenge presents an image with no obvious important information visible. The hint suggests that checking the metadata will reveal. I used exiftool to view the metadata and find the flag.

Challenge 4 — Polite Robots
We are provided with the robots.txt file of a website. The robots.txt file lists directories which web crawlers are suggested to avoid. Checking the website showed the path /mini-ctf/s3cr3t-vault-7f3a/ which revealed the flag.

Challenge 5 — Where Was This Taken?
We are provided with an image whose gps coordinates and exif data have been stripped. I used the extremely recognisable visual features and reverse image search I identified it as the main building.

Challenge 6 — Not What It Seems
We are provided with a file which won’t open. It has the .jpg file extension. Using the ‘file’ command in the terminal on the file reveals that its a zip file. I didn't actually look at the first few bytes, the output of the ‘file’ command shows that its zip archive data. So after renaming the file ‘mystery.zip’, it opens and reveals the final flag.

Conclusion
The challenges cover basic practical skills like viewing source code, decoding Base64, geolocation osint, checking metadata, identifying filetypes all of which prompted me to look below the surface to find hidden information.
