<h1>YouTube Data Extraction Instructions</h1>
<h3>1. Get Youtube video links</h3>
<p>In the 'getYoutubelinks.ipynb' notebook, links are extracted given a url playlist link. The links are saved in 'links_titles.txt'</p>
<h3>2. Installations</h3>
<p>To proceed it is necessary to have node and ffmpeg installed. The ytdl-core library is used to extract videos as mp4 from a Youtube link. The ffmpeg clt is used to convert mp4 to .wav</p>
<h3>3. Execute the getAudio.sh script</h3>
<p> Once the bash script has been executed two directories will be generated: 'wavfiles' and 'audioData'. The 'audioData' directory will contain the mp4 files and the 'wavfiles' directory will contain the data as .wav.</p>
