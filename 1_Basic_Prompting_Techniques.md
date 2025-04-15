# **Normal Prompting Techniques**

This section covers the fundamental concepts for structuring your prompts and describing the music you want Suno AI to generate.

## **Table of Contents**

* [Structuring Your Song](#bookmark=id.ldotptjalp7a)  
* [Describing Musical Elements](#bookmark=id.zdrgdblrotmz)  
  * [Genre and Sub-genre](#bookmark=id.mbkraj8252nd)  
  * [Mood and Emotion](#bookmark=id.snci0nhmm594)  
  * [Instrumentation](#bookmark=id.4wgjdj5zz5wa)  
* [Core Prompt Structure Example](#bookmark=id.syzxmkdfh1xw)  
* [Punctuation & Formatting Strategies](#bookmark=id.nn7y6d1wigdh)  
* [Simple Narrative Example](#bookmark=id.7c3d3gfw80ts)

## **Structuring Your Song**

You can guide Suno AI on the desired song structure using meta tags within the lyrics box. These tags help define the song's architecture.

Common tags include:

* \[Intro\]: Sets the initial tone of the song.  
* \[Verse\]: Contains the main narrative sections.  
* \[Pre-Chorus\]: Builds anticipation for the chorus.  
* \[Chorus\]: Typically the most memorable and repetitive part, encapsulating the main message or hook.  
* \[Bridge\]: Provides variation, a shift in perspective, or a change in mood.  
* \[Guitar Solo\], \[Instrumental Break\], etc.: Indicate sections without vocals.  
* \[Outro\]: The concluding part, bringing the song to a close.

**Note:** Using these tags helps the AI understand the intended flow. Usually, Suno will *not* sing the tag names themselves unless the structure is overly complex, confusing, or contains too many tags, causing the AI to read them literally.

## **Describing Musical Elements**

The more specific you are in your descriptions, the better Suno AI can align its output with your vision. Provide details in the "Style of Music" box.

### **Genre and Sub-genre**

Specify the musical style clearly. You can combine genres for unique sounds.

* *Example:* "bittersweet Hindustani Electro-pop"  
* *Example:* "90s hip hop"  
* *Example:* "folk rock ballad"  
* Refer to the [**Style Tag Sheet**](http://docs.google.com/style-tag-sheet.md) for an extensive list of possibilities.

### **Mood and Emotion**

Indicate the desired emotional tone.

* *Example:* "upbeat and energetic"  
* *Example:* "melancholic and reflective"  
* *Example:* "dramatic and epic"  
* *Example:* "calm and peaceful"

### **Instrumentation**

Detail the instruments you envision.

* *Example:* "featuring synth pads, electronic drums, and a groovy bassline"  
* *Example:* "acoustic guitar driven with subtle piano"  
* *Example:* "heavy electric guitars, pounding drums, and screaming vocals"  
* *Example:* "orchestral arrangement with strings and brass"

## **Core Prompt Structure Example**

Here’s a basic template showing where different elements go in the Suno interface:

::in\_title\_box::

"""\[Your Song Title Here, or leave blank for Suno to generate\]"""

::in\_style\_box::

"""  
\[Style/genre specifications, mood, instrumentation descriptions here\]  
e.g., Upbeat pop-punk with driving guitars and catchy female vocals  
"""

::in\_lyric\_box::

\[Intro\]  
(Instrumental intro description, e.g., driving guitar riff)

\[Verse 1\]  
Lyrics for the first verse go here...

\[Chorus\]  
Lyrics for the chorus go here...

\[Verse 2\]  
Lyrics for the second verse go here...

\[Chorus\]  
Lyrics for the chorus repeat here...

\[Bridge\]  
Lyrics for the bridge go here...

\[Chorus\]  
Lyrics for the final chorus go here...

\[Outro\]  
(Description of how the song ends, e.g., fade out with guitar riff)  
"""

*(Note: The ::in\_title\_box::, ::in\_style\_box::, ::in\_lyric\_box::, and """ notations are from the original user document for copy/paste purposes and are not part of the actual Suno prompt format).*

## **Punctuation & Formatting Strategies**

How you use punctuation and formatting within the lyrics box can subtly influence the output:

* **Brackets \[\]:** Primarily used for structural tags (like \[Verse\], \[Chorus\]). Can sometimes be used for non-lyrical instructions or sound effects, though results vary (e.g., \[Sound of rain\]).  
* **Colons ::** Can sometimes help separate distinct ideas or parameters, though primarily used in standard grammar.  
* **Parentheses ():** Often used for background vocals, ad-libs, or non-lyrical cues. Suno might interpret these as whispers or background elements.  
  * *Example:* (Ooh-ooh)  
  * *Example:* (softly)  
* **Slashes /:** Can indicate alternatives or choices, though standard grammatical use is more common.  
* **Quotation Marks "":** Used for direct speech within lyrics. Can sometimes emphasize specific phrases for the AI.  
* **Asterisks \*\*:** Can suggest emphasis or non-lexical sounds/effects.  
  * *Example:* \*Boom\!\*  
  * *Example:* \*whispering\*  
* **Question Marks ?:** Adds an interrogative quality to the vocal delivery.  
* **Exclamation Points \!:** Adds intensity or excitement to the vocal delivery.  
* **Capitalization:** ALL CAPS can suggest shouting or increased intensity, while lowercase might suggest whispering or a softer delivery.  
* **Spacing & Line Breaks:** Can influence the pacing and rhythm of the lyrical delivery. Extra line breaks might create pauses.

Experiment with these, but remember that structural tags \[\] are the most reliably interpreted formatting elements for song architecture.

## **Simple Narrative Example**

This example demonstrates combining a unique genre blend with a clear narrative structure.

* **Title:** All My GirlFriends Are Flowers  
* **Style:**  
  \[folk, pagan folk, ska, funk\]

* **Lyrics:**  
  \[Verse\]  
  All my girlfriends are flowers  
  They bloom in the sun  
  Petals in the wind  
  Every color under one  
  They whisper to the morning  
  Dance beneath the moon  
  Tied to the soil  
  Their scent's a fleeting tune

  \[Verse 2\]  
  The farmer bends low  
  Fingers in the dirt  
  Humming to the roots  
  Through joy and through hurt  
  Time's a cruel river  
  Weeds call out his name  
  But he tends to his blooms just the same

  \[Chorus\]  
  Oh  
  How the hours drift under the field's demand  
  Calloused hands and aching back  
  A life unplanned  
  Every fleeting moment  
  Every breaking dawn  
  Till the flowers fade and he's left to carry on

  \[Verse 3\]  
  Girls with wild stems  
  And hearts soft as rain  
  They spring up in laughter  
  But fledglings in pain  
  Some need no pruning  
  Others twine so tight  
  The farmer sorts their stories in the fading light

  \[Bridge\]  
  He said  
  "Love's just a harvest  
  Sowed deep in care  
  You reap what is tender  
  But the weeds'll always be there."  
  Dust in his hair  
  And dirt on his knees  
  Whispering to flowers caught on the breeze

  \[Chorus\]  
  Oh  
  How the hours drift under the field's demand  
  Calloused hands and aching back  
  A life unplanned  
  Every fleeting moment  
  Every breaking dawn  
  Till the flowers fade and he's left to carry on

* **Notes from Original Author:** Despite its simplicity, this prompt played to Suno's strengths, producing a unique song. The original prompt idea involved an organic farmer whose girlfriends are flowers. The lyrics were edited to adjust rhyming structure, as non-rhyming patterns can sometimes yield more creative (though not always conventionally beautiful) results, and Suno often re-rhymes anyway.
