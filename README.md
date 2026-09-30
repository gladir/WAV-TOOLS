# WAV-TOOLS
Suite de commandes écritent en Turbo Pascal/Free Pascal pour les WAV

<h3>Liste des fichiers</h3>

Voici la liste des différents fichiers proposés dans WAV-TOOLS :

<table>
	<tr>
		<th>Nom</th>
		<th>Description</th>
	</tr>
	<tr>
    <td><b>AIFF2WAV.PAS</b></td>
    <td>Cette commande permet de lancer le convertisseur AIFF/AIFF-C PCM vers WAV PCM.</td>
  </tr>
  <tr>
    <td><b>MOD2WAV.PAS</b></td>
    <td>Cette commande permet de lancer le convertisseur MOD ProTracker vers WAV PCM16.</td>
  </tr>
  <tr>
      <td><b>MP32WAV.PAS</b></td>
      <td>Cette commande permet de convertir un MP3 vers WAV PCM 16 bits, decodeur intégré.</td>
  </tr>
  <tr>
      <td><b>PLAYWAV.PAS</b></td>
      <td>Cette commande permet de lancer lecteur de fichier WAV.</td>
  </tr>
  <tr> 
     <td><b>VOC2WAV.PAS</b></td>
    <td>Cette commande permet de lancer le convertisseur Creative VOC PCM vers WAV PCM16.</td>
  </tr>  
</table>

<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> <i>LEFICHIER.PAS</i></pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> <i>LEFICHIER.PAS</i></pre>
	
Par exemple, si vous voulez compiler PLAYMP3.PAS, vous devrez tapez la commande suivante :

<pre><b>fpc</b> PLAYMP3.PAS</pre>

<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/WAV-TOOLS/blob/main/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/WAV-TOOLS/blob/main/LICENSE">MIT</a>.</li>
</ul>
