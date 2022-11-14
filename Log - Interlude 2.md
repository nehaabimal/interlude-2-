---
**Tutorial: Working on my Unessay (the Decolonization of Museums and Repatriation of Indigenous Artefacts) using a combination of Twine, DALL-E, Mural**

After reading the VICE article "This First Nations Artist Recreates Tense Moments in Native History in Second Life," which is about a VR game/cyberspace called TimeTraveller™ which features overlooked chapters in native history and lets Native American users control the POV, I wanted to do a digitization of my research topic "the Decolonization of Museums and Repatriation of Indigenous Artefacts." 

I began by using GPT-3/OpenAI API to generate some titles for my Twine story by plugging in some prompts in the playground. I initially wanted to do a time traveller's perspective of history, but that changed into focusing on a museum tour of collections of Indigenous artefacts. Titles generated included: "Aboriginal Art and Artefacts: A Tour of Our Indigenous History"" and "Telling Our Stories: A Museum Tour of Indigenous Artefacts." I then began using OpenAI's DALL-E to create 3D rendrings of museums that I would do a tour of in my Twine Story. My research focuses on the Kellarney Centennial Museum in Ontario that has been trying to repatriate stolen Anishanaabe artefacts from the 1950s from the University of Michigan. 

I have pictures of the museum from one of my sources but I wondered if AI could generate a 3D rendring of a "cabin-style museums that showcases Indigenous artefacts." DALL-E generated images that were very similar to the Centennial Museum's layout which was suprising. I also have a catalogue of the missing artefacts, like arrowheads - DALL-E was able to generate "Indigenous arrowheads being preserved in a museum." I want to do a contrast of the cabin-style museums and the smaller, more intimate collections within the few Indigenous museums in Canada like the Aanischaaukamikw Cree Cultural Institute, versus the History Hall of the Canadian Museum of History, a larger, well-funded institution. My description for the bigger museum was "3D rendering of the Grand Hall in the Canadian Museum of History," which features the totem poles of the First Peoples of Canada’s Pacific Coast. My plan is to insert these images to create a game-format on Twine so that players will have visual elements. 

My plan is to also visit the Canadian Museum of History and the Aanischaaukamikw Cree Cultural Institute, and create a Mural website of all the visual and educational content I take on both trips, which I will then hyperlink into my Twine story under the options "Welcome to the Canadian Museum of History!" and "Welcome to the Aanischaaukamikw Cree Cultural Institute!". This was based on feedback from Intertistial 1. Unlike Intertistial 1, I added images to my Twine using wix.com (after watching this tutorial:(https://www.youtube.com/watch?v=6bVz6Ny0Xq4)  I

I had some difficulty finding the html code but it worked - all I had to do was copy the url from the uploaded image on wix.com and insert it like this: 

<center><img src = "https://static.wixstatic.com/media/0d4445_d800a720893f49638c93111362ebfa12~mv2.jpg"></center>

I also plan to use the same tutorial and create a background image for my Twine story using the following CSS code in the stylesheet.
tw-story {bacground-image: url("");background-size: cover;}
                
I found the above code on the following website: (https://ohiofi.com/blog/twine-pictures-gifs-and-background-images/) 

I had to switch into incognito mode as my regular browser's Twine format was not allowing me to add images in the default Harlowe mode for Twine 2.

I also hyperlinked the UMichigan catalogue of Indigenous artefacts to my Twine story under "The Stolen Artefacts" using the code: 

(link: "The Stolen Artefacts") [(goto-url:'https://quod.lib.umich.edu/a/anthro1ic?size=50;sort=archsitename;start=1;type=boolean;view=reslist;rgn1=archsitename;select1=phrase;q1=Killarney%20Bay%201')]

I have interviewed curators and academics who are knowledgeable in the repatriation process, so instead of generating personalities/characters using GPT-3, I used my original sources as guides for the player. For the next interstitial, I am going to see if I can add audio, specifically SoundCloud clips of the interviews I've conducted, into my Twine story. I also generated people using DALL-E such as the player and the curators/guides to help visuallize the museum experience in a passive, story format. 

**tutorial: 3812-ar**

I was able to fork/clone the 3812-ar repo to create my own [3812-ar/targets.mind at main · nehaabimal/3812-ar (github.com)](https://github.com/nehaabimal/3812-ar) However, after following the instructions, I realized that I should not have used one of my repatriation-related images as a target image but one of the samples given. 

However, there were many point of interest on the image I chose when uploading to  [https://hiukim.github.io/mind-ar-js-doc/tools/compile](https://hiukim.github.io/mind-ar-js-doc/tools/compile) so when I downloaded it to as targets.mind, the racoon graphic recognized it and reacted to it once my cam (ghost) scanner was activated and my repo went live. I checked out the 3D models on Sketchfab for museums and Indigenous artefacts (totem poles) but none were free and I could not vouch for the historical accuracy of the renderings. 

I am going to try incorporating location based AR once I visit one of the museums I've listed in my Twine story to set the geotriggers to that location. I downloaded the raw code from Professor Graham's [my demo scratchpad repo](https://github.com/shawngraham/demo/blob/master/twine-ar/cu-arg.html)for this purpose. 

