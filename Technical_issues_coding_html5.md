HTML 5 document structure

If you are using the X-UA-Compatible META tag you want to place it as close to the top of the page's HEAD as possible. Internet Explorer begins interpreting markup using the latest version. When Internet Explorer encounters the X-UA-Compatible META tag it starts over using the designated version's engine. This is a performance hit because the browser must stop and restart analyzing the content.
Here are your options:

"IE=edge"
"IE=11"
"IE=EmulateIE11"
"IE=10"
"IE=EmulateIE10"
"IE=9"
"IE=EmulateIE9
"IE=8"
"IE=EmulateIE8"
"IE=7"
"IE=EmulateIE7"
"IE=5"

@ http://stackoverflow.com/questions/6771258/whats-the-difference-if-meta-http-equiv-x-ua-compatible-content-ie-edge-e
