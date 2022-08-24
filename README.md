<br />
<p align="center">
  <a href="https://github.com/francescocastiglione/Luce-Notturna-Alexa-Skill">
    <img src="assets/images/it-IT_largeIconUri.png" alt="Luce Notturna" width="80" height="80">
  </a>
  
  <h3 align="center">Luce Notturna Alexa Skill</h3>
  
  <p align="center">
    Francesco Castiglione
  </p>
</p>

<details open="open">
  <summary>Contents</summary>
  <ol>
    <li>
      <a href="#usage">Usage</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <ul>
      <li>
          <a href="#available-languages">Available Languages</a>
      </li>
    </ul>
    <li>
      <a href="#instructions">Instructions</a>
    </li>
    <li><a href="#contact-information">Contact Information</a></li>
  </ol>
</details>

## Usage
"Luce Notturna" represents a very simple and intuitive unpublished skill to make your Echo device produce a soft light (if it is equipped with a LED), ideal for night operations.
In fact, just invoke the skill with "Alexa, lancia Luce Notturna" or "Alexa, chiedi a Luce Notturna di accendersi" and your device will revolutionize the atmosphere of your room, without waking anyone.
To stop the skill, simply send the command "Alexa, stop" and the device will cease its activity silently.

Unfortunately, Amazon does not allow a duration that exceeds 4 minutes or to choose the color of the light emitted, but if these possibilities are introduced, the skill will be updated immediately. However, after 4 minutes, just say "Alexa, avvia Luce Notturna" again.
The light produced is not particularly powerful and, in any case, its intensity is determined by the type of device owned. If you need more lighting, you can always turn on your light.

The microphone is disabled while the skill is running.

These are the main commands available to Luce Notturna:
- Alexa, avvia Luce Notturna
- Alexa, chiedi a Luce Notturna di accendersi
- Alexa, chiedi a Luce Notturna avviati
- Alexa, chiedi a Luce Notturna accendi la luce
- Alexa, chiedi a Luce Notturna aiuto
- Alexa, chiedi a Luce Notturna di aiutarmi

## Built With
* [Alexa Developer Console](https://developer.amazon.com/alexa/console/ask)
* [JavaScript](https://www.javascript.com)
* [Node.js](https://nodejs.org/it/)

## Available Languages
* Italian (IT)

## Instructions
In the Alexa Developer Console, after creating the skill from scratch, in the Build section, go to Intents - JSON Editor and paste the code found in the "interactionModels/custom/it-IT.json" file.
In the Code section, update the files with the code present in the "lambda" folder. Click on "S3 Storage" and uploads the files found in the "audio" folder.
Now you can test your skill in the Test section (activate it, if deactivated).
(Don't forget to change the invocation name to "Luce Notturna" by going to Build - Invocations - Skill Invocation Name).

## Contact Information
Instagram - [@_francescocastiglione](https://www.instagram.com/_francescocastiglione/)

Facebook - [Francesco Castiglione](https://www.facebook.com/francesco.castiglione.18/)

Email - francescocastiglione99@hotmail.com
