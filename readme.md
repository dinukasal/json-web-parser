component types and definitions other than html attributes
---------------------------------------------------------

button with image
- image_src
- onClick

selection button
- options

dropdown
- options

input_field
- placeholder

input_selection_field
- options

compound_input
- children [
    {
        "label":"word",
        "type":"input"
    },
    {
        "label:"Sound Like",
        "type": "input_selection_field",
        "options":[]
    }
]

play button
music_url

upload input
- upload_url
- type [music,file,document,image]

color picker

label

form
 - action
 - method
