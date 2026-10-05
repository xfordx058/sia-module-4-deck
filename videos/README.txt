The deck has 7 video placeholder slides. index.html loads each MP4 from this
folder using the filename in the slide's data-video attribute.

Expected files (the deck shows a "file not found" notice if one is missing):

  01-how-to-synchronize-data.mp4               PRESENT
  02-data-integration-strategies.mp4            missing
  03-data-transformation-and-mapping.mp4        missing
  04-data-quality-and-cleansing.mp4              missing
  05-master-data-management.mp4                 missing
  06-data-synchronization-and-replication.mp4   PRESENT
  07-real-time-data-integration.mp4             missing

Slide positions in index.html (1-based, out of 66):

  15  intro      01-how-to-synchronize-data.mp4
  24  Topic A    02-data-integration-strategies.mp4
  31  Topic B    03-data-transformation-and-mapping.mp4
  39  Topic C    04-data-quality-and-cleansing.mp4
  47  Topic D    05-master-data-management.mp4
  55  Topic E    06-data-synchronization-and-replication.mp4
  63  Topic F    07-real-time-data-integration.mp4

Filename history:

  01-how-to-synchronize-data.mp4
    was "Why_Out-of-Sync_Data_Breaks_Businesses.mp4"
    70.3s, 720x1280 (portrait), H.264 video + AAC audio, ~5.1 MB

  06-data-synchronization-and-replication.mp4
    was "Data_Synchronization_vs data integration.mp4"
    70.0s, 720x1280 (portrait), H.264 video + AAC audio, ~4.9 MB

Both present files are portrait (9:16). The player switches to a 9:16 frame
automatically so a portrait video is not stretched or cropped.

To use a different file, keep the filename or update the matching
data-video attribute in index.html.
