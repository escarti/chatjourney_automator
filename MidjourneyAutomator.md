# Adapted from original file seen here: https://www.youtube.com/watch?v=MAPM6xvvg_0&t=1s 

# ----- Part 1 ------ #
# Copy this part first #

Hey Assistant, I need your help creating Midjourney command for suffixes. 
 
The command for this kind of suffix should be in this format.
 
`/prefer option set option:[simple one-word name, so it can be easily referred to later] value: - [three-word description of the style]::5 [clearer description of the style, including the medium]::4 [technical details about the style]::3 [color, lighting and tone hints for the style]::3 [something you do not want out of the style (explained as if you want it)]::-2`
 
This formatting is taking advantage of Midjourney's multi-prompt functionality. The'::' splits up the prompt and the number chosen controls the weight of the prompt that came before it. In each piece it is important that the kind of artwork is mentioned, so that the multi-prompts do not interfere with each other. Since the AI does not understand grammar, in each part use comma separated keywords with heavy meaning to describe each. 
 
For example:
`/prefer option set option:impressionist value: - beautiful impressionist painting::5 dramatic oil painting, sweeping, expressive swirling strokes::4 painting, swirling impasto, thick brushes, pallet knife, strong creative choices, obvious brush marks::3 painted with saturated, epic colors, highly visual, rule of thirds::3 dull, boring, and ugly artwork::-2`
 
`/prefer option set option:portrait value: - headshot portrait photography::5 beautiful rich photograph, with focal depth and a majestic blurring behind the subject's face::4 portrait photograph taken  on a Canon EOS 5D Mark IV DSLR, f/5.6 aperture, 1/125 second shutter speed, ISO 100::3 portrait with natural rim lighting, shot on location, beautiful exposure, and high dynamic range of both color and light::3 black and white vintage photo with grainy, blurry, and deformed subjects::-2`
 
Since this will be used for AI 'Text-to-Image' processing, it's far more important to be specific than accurate to an existing style. Make bold and interesting choices when you invent your own art style.
 
Every time you generate one suffix describe a visually appealing art style with clear detail so someone would be inspired to try the command. (Write in the format of persuasive ad copy). 
Then print the command itself within a code block so it can be easily copy and pasted. Then store the suffix in a table with 3 columns, suffix, description and full command for future use. We'll call this table suffix table for short.

#--------- PART 2 --------#

Now I need your help to create Midjourney commands for images. The commands all follow the following format:

Format:
`/imagine prompt:[Scene] with [Traits], [Lighting], [Mood]. --[parameter] --[suffix]'

Scene, traits, lighting, and mood can be brief descriptions in plain English. Scenes should be creative and extremely unique, bold outlooks on interesting visual places. Traits can be anything from items in the scene, to color pallet, or anything else to make the idea more unique. The lighting and mood should be consistent and can be used to enhance the visual idea. 

Suffix has to be an existing suffix within the suffix table and is specified with '--' followed by the suffix name.

And parameter has to be among these:

Aspect Ratios
--aspect, or --ar Change the aspect ratio of a generation. Specified in format w:h within the range 1:2–2:1

Chaos
--chaos <number 0–100> Change how varied the results will be. Higher values produce more unusual and unexpected generations.

No
--no Negative prompting, --no plants would try to remove plants from the image.

Quality
--quality <.25, .5, 1, or 2>, or --q <.25, .5, 1, or 2> How much rendering quality time you want to spend. The default value is 1. Higher values cost more and lower values cost less.

Seed
--seed <integer between 0–4294967295> The Midjourney bot uses a seed number to create a field of visual noise, like television static, as a starting point to generate the initial image grids. Seed numbers are generated randomly for each image but can be specified with the --seed or --sameseed parameter. Using the same seed number and prompt will produce similar ending images.

Stop
--stop <integer between 10–100> Use the --stop parameter to finish a Job partway through the process. Stopping a Job at an earlier percentage can create blurrier, less detailed results.

Style
--style <4a, 4b or 4c> Switch between versions of the Midjourney Model Version 4

Stylize
--stylize <number>, or --s <number> parameter influences how strongly Midjourney's default aesthetic style is applied to Jobs.

Uplight
--uplight Use an alternative "light" upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image is less detailed and smoother.

Upbeta
--upbeta Use an alternative beta upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image has significantly fewer added details.

No matter what parameter you use, they should match the vibe and tone of the scene you describe. 

Please print the command within a code block to make it easier to copy paste.
 
Since this will be used for AI 'Text-to-Image' processing, it's far more important to be specific than accurate to any existing place or  Make bold and interesting choices for your artworks.

Feel free to us as many parameters you like if you think it fits the mood of the image.

Please don't do anything until I command, just ack with ...

