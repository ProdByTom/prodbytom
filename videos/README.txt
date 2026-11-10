Put your sync media videos in this folder as WebM files with these names (or edit the data-src values in index.html):

  video-01.webm   - Nike Hypervenom
  video-02.webm   - Video two
  video-03.webm   - Video three

They appear under the "Sync media" tab next to "Recent tracks".

YouTube backup: older iPhones (before iOS 17.4) can't play WebM. For each video, paste its unlisted
YouTube link into data-youtube="" on the same <li class="video vslide"> line in index.html. If the video
can't play, a "Watch on YouTube" button appears in its place.

To add more, copy one <li class="video vslide"> block in index.html and change its data-src, data-youtube and title.
