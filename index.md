<link href="https://fonts.googleapis.com/css2?family=Tangerine&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Pinyon+Script&display=swap" rel="stylesheet">
<div style="font-family: 'Tangerine', cursive; font-style: italic; font-size: 4em; text-align: center;">
  Fugatto 1
</div>

<div style="font-family: 'Tangerine', cursive; font-style: italic; font-size: 3.5em; text-align: center">
 Foundational Generative Audio Transformer Opus 1
</div>


<div style="display: flex; justify-content: space-between; align-items: center;">
  <div style="flex: 0 0 34%; padding-right: 10px;">
    <img src="fugatto.webp" alt="Description of Image" width="100%" style="max-width: 400px;">
  </div>
  <div style="flex: 0 0 66%; padding-left: 10px;">
    <video width="100%" height="auto" controls>
      <source src="fugatto.mov" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

Fugatto is a framework for audio synthesis and transformation given text instructions and optional audio inputs. The framework includes Fugatto itself, the generative model, a dataset creation technique that exploits relationships between audio and text, and method for composing instructions flexibily called ComposeableART.

### Creative Examples
**1. Rap Song**<br>
[Singing Voice Synthesis (SVS), Text-To-Speech Synthesis (TTS), Text-To-Audio Synthesis (TTA)]

<table>
   <thead>
      <tr>
         <th style="text-align: left">Fugatto</th>
         <th style="text-align: left">Audio Context</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="rap song.mp3" type="audio/wav"></audio></td>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="rap backing track.mp3" type="audio/wav"></audio></td>
      </tr>       
   </tbody>
</table>

**2. Introduction for a Movie and _Recitativo Accompagnato_**<br>
[Singing Voice Synthesis (SVS), Text-To-Speech Synthesis (TTS), Text-To-Audio Synthesis (TTA)]

<table>
   <thead>
      <tr>
         <th style="text-align: left">Fugatto</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="movie intro.mp3" type="audio/wav"></audio></td>
      </tr>       
   </tbody>
</table>

### Emergent Sounds

Text-To-Audio Synthesis (TTA)

<table>
   <thead>
      <tr>
         <th style="text-align: left">Fugatto</th>
         <th style="text-align: left">Instruction</th>
         <th style="text-align: left">Emergence?</th>         
      </tr>
   </thead>
   <tbody>
		<tr>
			<td style="text-align: left"><audio controls style="width: 150px;"><source src="      Electronic Dance Music, Dogs Barking, Cats Meowing.wav" type="audio/wav"></audio></td>
          <td style="text-align: left">Synthesize Electronic Dance Music, Dogs Barking, Cats Meowing.</td>
          <td style="text-align: left">Dogs barking in sync with the music.</td>          
      </tr>   
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Banjo and rainfall.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Synthesize Banjo and Rainfall</td>
         <td style="text-align: left">Exitence of banjo and rain sounds in the training data.</td>         
      </tr>       
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Drum kit and ticking clock.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Synthesize Drum kit and ticking clock.</td>
         <td style="text-align: left">Clocks tick but not musically.</td>
      </tr>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Design factory machinery that screams in metallic agony.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Design factory machinery that screams in metallic agony.</td>
         <td style="text-align: left">Machines do not scream in agony.</td>         
      </tr>  
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Produce a typewriter that whispers each letter typed.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Produce a typewriter that whispers each letter typed.</td>
         <td style="text-align: left">Softer onset due to to whispering.</td>         
      </tr>          
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Produce a soundscape with a choir of sirens to produce a lush and calm choir composition with sustained chords.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Produce a soundscape with a choir of sirens to produce a lush and calm choir composition with sustained chords.</td>
         <td style="text-align: left">Music instruments, not sirens, create choirs and lush chords.</td>         
      </tr>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Produce an oral delivery of a male dog barking in English saying the words.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Produce an oral delivery of a male dog barking in English saying the words "I need to know… who let the dogs out?", with the sound of a male dog barking.</td>
         <td style="text-align: left">Dogs don't speak and people, normally, do not bark.</td>         
      </tr>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Produce an oral delivery of a violin playing a beautiful solo in English saying the words.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Produce an oral delivery of a violin playing a beautiful solo in English saying the words "I need to know; Who let the dogs out?", sounding like a violin playing a beautiful solo.</td>
         <td style="text-align: left">People normally slide between notes like a violin.</td>         
      </tr>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Synthesize a cello shouting with anger and a cello screaming.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Synthesize a cello shouting with anger and a cello screaming.</td>
         <td style="text-align: left">Cellos do not shout nor scream in anger.</td>         
      </tr>
		<tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Synthesize a female voice barking and a female voice meowing.wav" type="audio/wav"></audio></td>		
          <td style="text-align: left">Synthesize a female voice barking and a female voice meowing.</td>
         <td style="text-align: left">People do not bark while they speak</td>          
      </tr>     
		<tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Synthesize a flute barking and a flute meowing.wav" type="audio/wav"></audio></td>		
         <td style="text-align: left">Synthesize a flute barking and a flute meowing.</td>
         <td style="text-align: left">Flutes do not bark nor meow.</td>         
      </tr>     
		<tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Synthesize a saxophone barking and a saxophone meowing (1).wav" type="audio/wav"></audio></td>
         <td style="text-align: left">Synthesize a saxophone barking and a saxophone meowing.</td>
         <td style="text-align: left">Saxohones do not bark.</td>         
      </tr>
		<tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Synthesize a saxophone barking and a saxophone meowing (0).wav" type="audio/wav"></audio></td>
         <td style="text-align: left">Synthesize a saxophone barking and a saxophone meowing.</td>
         <td style="text-align: left">Saxohones do not bark.</td>         
      </tr>      
     <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Violin melody and baby laugh.wav" type="audio/wav"></audio></td>     
         <td style="text-align: left">Violin melody and baby laugh</td>
         <td style="text-align: left">Violins do not laugh like babies, nor do babies sound like violins.</td>         
      </tr>  
   </tbody>
</table>


