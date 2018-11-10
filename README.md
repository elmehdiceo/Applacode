# Applacode

# New Document


### Social Sharing Codes

You can share text, link, image using this social sharing code. It's works only in Custom Page Feature.

Go to Features >> Custom Page >> Add Text Section  >> Click on Source Button

Here are some examples you can copy-paste and edit as you want.


Share Text Only:

`<button onclick="window.plugins.socialsharing.share('YOUR TEXT HERE')">Click to Share</button>`


Share Link Only:


`<button onclick="window.plugins.socialsharing.share(null, null, null, 'http://www.google.com')">Click to Share</button>`


Share Text & Link:


`<button onclick="window.plugins.socialsharing.share('YOUR TEXT HERE', null, null, 'http://www.google.com')">Click to Share</button>`


Share Image Only:


`<button onclick="window.plugins.socialsharing.share(null, null, 'https://www.google.co.in/images/branding/googlelogo/2x/googlelogo_color_120x44dp.png', null)">Click to Share</button>`

Share Text & Image:
`<button onclick="window.plugins.socialsharing.share('YOUR TEXT HERE', null, 'https://www.google.co.in/images/branding/googlelogo/2x/googlelogo_color_120x44dp.png', null)">Click to Share</button>`

Share Text, Link & Image:
`<button onclick="window.plugins.socialsharing.share('YOUR TEXT HERE', null, 'https://www.google.co.in/images/branding/googlelogo/2x/googlelogo_color_120x44dp.png', 'http://www.google.com')">Click to Share</button>`


### WhatsApp Click to Chat

Go to Features >> Custom Page >> Add Text Section  >> Click on Source Button

`<a href="#" onclick="window.open('https://api.whatsapp.com/send?phone=212XXXXXXXXXX', '_system', 'location=yes'); return false;">Click to Chat</a>`

Note: here you don't have to use 0 or + sign in country code. For MOROCCO, Country code is 212.


### Delete the navigator - layouts n°3, 4 & 5

To do that, add the following css in the advanced customization section of your editor:

`.slider-pager { 
    display: none; 
}`


### Change your menu's style  Template Metro - layout 3 - full.

To do that, just add the following css in the advanced customization section of your editor:

`.layout.l14 li { 
    margin: 0; 
    width: 33%; 
}
.layout.l14 ul { 
    margin: 6%; 
}`

Information

This modification only affects the Layout 3 - full.
