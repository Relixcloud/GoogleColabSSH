<h1>Relixcloud Google Colab SSH</h1>

<h3>Getting started</h3>
<h4>1. Make a new google colab notebook</h4>
<h4>2. Paste this code into the code cell</h4>

<p>!pip install colab_ssh --upgrade

from colab_ssh import launch_ssh_cloudflared, init_git_cloudflared
launch_ssh_cloudflared(password="yourpassword")</p>
<h3>Note : Make sure to change to what password you want</h3>

<h4>next download the cloudflared (argo tunnel)</h4>
<h4>make a folder called ".cloudflared in your C:/username folder"</h4>
<h4>Now place the .exe file in that folder</h4>
<h4>open command promt or powershell in the user dir, and type "notepad .ssh/config"</h4>
<h4>it will not be there so just create it in the notepad gui</h4>
<h4>and paste the server config colab did after starting</h4>
<h4>now go back to the user dir after saving the code, and type whatever ssh terminal code it gave you :)</h4>
