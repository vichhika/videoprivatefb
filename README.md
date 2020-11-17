# Download video from facebook private group
<br>
The idea to download video from facebook private group is just extract video link from source code.
<br>
<p><b>Step 1 :</b> append "view-source:" before link</p>
<p><b>Step 2 :</b> search "playable_url_quality_hd" and copy the 10 to 20 lines that contains search matched to filter with regex</p>
<p><b>Step 3 :</b> Regex step 1: search match = ("playable_url_quality_hd"):"([^"]*) and replace = $2<p>
<p><b>Step 4 :</b> Regex step 2:copy output from step 1 and do search match = u0025 and replace = %<p>

