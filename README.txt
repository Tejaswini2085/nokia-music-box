NOKIA MUSIC BOX — SETUP NOTES

This is a lightweight static website template designed for basic browsers like Opera Mini. It includes links to sites where some music is legally downloadable; it does not include copyrighted songs.

IMPORTANT: This static template cannot upload files to the web server by itself.

To make your own MP3s available to your Nokia over the internet:
1. Choose a web host that lets you upload files (for example, a GitHub Pages repository).
2. Upload index.html and the music/ folder.
3. Put only MP3 files you own or have permission to share inside music/.
4. Edit index.html and replace the example song entry with a link like:
   <div class="song"><strong>Song Title — Artist</strong><br><a href="music/song01.mp3">Download MP3</a></div>
5. Upload the updated index.html and MP3 files to the host.
6. Open your hosted website URL in Opera Mini on the Nokia.

Do not upload music you do not have permission to redistribute. On third-party sites, check the licence/terms for each track.
If an MP3 does not play on the Nokia, try a standard MP3 file encoded at 44.1 kHz with a modest bitrate (e.g. 128 kbps).
