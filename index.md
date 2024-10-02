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

_Fugatto_ is a framework for audio synthesis and transformation given text instructions and optional audio inputs. The framework includes Fugatto itself, the generative model, a dataset creation technique that exploits relationships between audio and text, and method for composing instructions flexibily called ComposeableART.

### Creative Examples
This section provides a collection of sound pieces that were created by first using Fugatto to create and modify assets, then using a digital audio workstaion to combine them.

**1. Rap Song**<br>
[Singing Voice Synthesis (SVS), Text-To-Speech Synthesis (TTS), Text-To-Audio Synthesis (TTA)]

<table>
   <thead>
      <tr>
         <th style="text-align: left; font-style: italic;">Fugatto</th>
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
         <th style="text-align: left; font-style: italic;">Fugatto</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="movie intro.mp3" type="audio/wav"></audio></td>
      </tr>       
   </tbody>
</table>

### Emergent Sounds and Capabilities

[Text-To-Audio Synthesis (TTA)]

This section provides a collection of sound snippets that are unlikely to exist in the real world and in the training data. Assuming the text instructions describe the task, and that _Fugatto_ has not seen such instructions during training, _Fugatto_ is able to execute these tasks without explicit supervision.

<table>
   <thead>
      <tr>
         <th style="text-align: left; font-style: italic;">Fugatto</th>
         <th style="text-align: left">Instruction</th>
         <th style="text-align: left">Emergence?</th>         
      </tr>
   </thead>
   <tbody>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Electronic Dance Music, Dogs Barking, Cats Meowing.wav" type="audio/wav"></audio></td>
          <td style="text-align: left">Synthesize Electronic Dance Music, Dogs Barking, Cats Meowing.</td>
          <td style="text-align: left">Dogs barking in sync with the music.</td>          
      </tr>   
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Banjo and rainfall.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Synthesize Banjo and Rainfall</td>
         <td style="text-align: left">Unlikely existence of banjo and rain sounds at the same time in the training data.</td>         
      </tr>       
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Drum kit and ticking clock.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Synthesize Drum kit and ticking clock.</td>
         <td style="text-align: left">Clocks tick but not musically nor with the sound of drum sticks.</td>
      </tr>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Design factory machinery that screams in metallic agony.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Design factory machinery that screams in metallic agony.</td>
         <td style="text-align: left">Factory machinery does not scream in agony.</td>         
      </tr>  
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Produce a typewriter that whispers each letter typed.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Produce a typewriter that whispers each letter typed.</td>
         <td style="text-align: left">Typewriters generally have a strong onset for every letter typed.</td>         
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
         <td style="text-align: left">People normally don't slide between notes, like a violin, when they speak.</td>         
      </tr>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Synthesize a cello shouting with anger and a cello screaming.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Synthesize a cello shouting with anger and a cello screaming.</td>
         <td style="text-align: left">Aside from Xenakis' music, cellos do not shout in anger nor scream.</td>         
      </tr>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Synthesize a female voice barking and a female voice meowing.wav" type="audio/wav"></audio></td>    
          <td style="text-align: left">Synthesize a female voice barking.</td>
         <td style="text-align: left">People, normally, do not bark</td>          
      </tr>     
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Synthesize a flute barking and a flute meowing.wav" type="audio/wav"></audio></td>      
         <td style="text-align: left">Synthesize a flute barking and a flute meowing.</td>
         <td style="text-align: left">Flutes do not bark nor meow.</td>         
      </tr>     
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Synthesize a saxophone barking and a saxophone meowing (1).wav" type="audio/wav"></audio></td>
         <td style="text-align: left">Synthesize a saxophone barking and a saxophone meowing.</td>
         <td style="text-align: left">Aside from Free Jazz, Saxophones do not bark nor meow.</td>         
      </tr>
      <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Synthesize a saxophone barking and a saxophone meowing (0).wav" type="audio/wav"></audio></td>
         <td style="text-align: left">Synthesize a saxophone barking and a saxophone meowing.</td>
         <td style="text-align: left">Aside from "Interstellar Spaces", Saxophones do not bark nor meow.</td>         
      </tr>      
     <tr>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="Violin melody and baby laugh.wav" type="audio/wav"></audio></td>     
         <td style="text-align: left">Violin melody and baby laugh</td>
         <td style="text-align: left">Violins do not laugh like babies, nor do babies sound like violins.</td>         
      </tr>  
   </tbody>
</table>


[MIDI-2-Audio (TTA)]

This section provides a collection of examples to showcase Fugatto's ability to convert from MIDI audio to natural Audio. We emphasize that this is zero-shot behavior and emergent capability, given that Fugatto has never seen monophonic melodies during MIDI2Audio training, with the average number of stems present in training this task being 8.
<table>
   <tbody>
      <tr>
         <td style="text-align: left; font-style: italic;">Fugatto</td>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="54334_Csharp_4_minor_9_7_down_down_down_up_0.wav" type="audio/wav"></audio></td>         
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="3207_C_4_major_7_4_up_down_down_down_0.wav" type="audio/wav"></audio></td>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="14514_C_4_minor_4_11_up_up_down_up_0.wav" type="audio/wav"></audio></td>           
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="26540_C_4_blues_3_6_down_down_up_up_0.wav" type="audio/wav"></audio></td>    
      </tr>        
      <tr>
         <td style="text-align: left">Audio Context</td>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="54334_transposed.wav" type="audio/wav"></audio></td>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="3207_transposed.wav" type="audio/wav"></audio></td>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="14514_transposed.wav" type="audio/wav"></audio></td>
         <td style="text-align: left"><audio controls style="width: 150px;"><source src="26540_transposed.wav" type="audio/wav"></audio></td>
      </tr>
   </tbody>   
</table> 
