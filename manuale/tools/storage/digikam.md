---
title: 📷 digiKam
description: Our workflow in exploiting the software we user for managing Scambi Festival’s images
---
!!! info
	Please, do <mark>read the [Storage management](./) page first</mark>!

To manage and store each event’s pictures, we use [digiKam](https://digikam.org), a powerful and cool open source software specifically crafted for this purpose.

1. Ensure pictures’ metadata correctness (see warning above)
2. Rename pictures according to their date, stored into the EXIF metadata, using the following format: `[date:yyyy.MM.dd-HH.mm.ss]{unique}`
3. Ensure all files are in JPG format
4. Assign author and copyright in pictures’ metadata
	1. apply general basic copyright settings
	2. apply author-specific copyright settings
	3. Create a tag for each author and assign it to their pictures, in order to make filtering and sorting easier
5. Sort images in albums according to their topic/sub-event
6. Select and edit photos
7. Batch rename according to the following format: `[date:yyyy.MM.dd-HH.mm.ss]{unique} [dir], Scambi Festival`. Such format means pictures’ name contain the name of their belonging album, hence the name of the activity they are related to.
8. Check geotagging inside pictures’ metadata
9. Create/set/assign location tags
10. People recognition
	1. People’s face detection
	2. People’s face recognition
11. In order to upload the pictures in batch to the Internet Archive, all media and their metadata should be parsed in a CSV file. To do this, let’s use digiKam’s “Batch Queue Manager” and use the “custom shell script” tool, with this input: `echo "\"$INPUT\",$COLORLABEL,$TAGSPATH" >> ~/Desktop/ia-scambi.csv`
