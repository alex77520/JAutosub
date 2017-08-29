JAutosub is a pre-package, ready to use version of <a href="https://github.com/agermanidis/autosub">Autosub 0.3.12</a> with a Java GUI.

It can be used both to generate <b>automatic subtitles</b> to video/audio files or as a <b>audio transcription assistant tool.</b> <br>
Internet connection is REQUIRED because it uses the <a href="https://cloud.google.com/speech/">Google Cloud Speech Server</a> for the job, in the same way as the <a href="https://support.google.com/youtube/answer/6373554?hl=en">Youtube Automatic Subtitles</a>. <br>
The accuracy of the Google Speech Recognition has been improving over the time, under certain specific conditions and if the audio file has good quality it is possible to get a <a href="https://medium.com/@mlockrey/youtube-s-incredible-95-accuracy-rate-on-auto-generated-captions-b059924765d5">result close to 95%</a>.
<b>IMPORTANT: </b> For best results the audio file should have high quality/clarity. 

<img src="https://github.com/raryelcostasouza/JAutosub/blob/master/jautosub-screenshot.png" height="300">

<h1>For Users - Download the app</h1>
v1.0 - 29/08/2017
<ul>

<li><a href="https://github.com/raryelcostasouza/JAutosub/releases/download/v1.0/JAutosub-Setup.exe">Installable Version</a></li>
<li><a href="https://github.com/raryelcostasouza/JAutosub/releases/download/v1.0/JAutosub-Portable.zip">Portable Version</a></li>
</ul>

<h1>For Developers - Technical Details</h1>
<ul>
<li> To get autosub running on Windows followed <a href="https://github.com/agermanidis/autosub/issues/31">this instructions.</a> </li>
<li> The packaged version of Autosub contained was generated by <a href="http://www.pyinstaller.org/"> pyInstaller</a>. </li>
<li> The final <a href="https://github.com/raryelcostasouza/JAutosub/blob/master/autosub_modified.py">autosub_modified.py<a> with all the modifications needed for packaging on the pyinstaller and <a href="https://github.com/raryelcostasouza/JAutosub/blob/master/patch-autosub-0.3.12.patch"> the respective patch for the autosub 0.3.12 </a> </li>
</ul>

<h2>How to compile/run (for developers)</h2>
Extract and open the <a href="https://github.com/raryelcostasouza/JAutosub/blob/master/JAutoSub-netbeans-project.zip">netbeans project</a> on <a href="https://netbeans.org/">Netbeans</a> and run it.
