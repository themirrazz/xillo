# Xillo
A basic XHR browser for Windows96


## How it works
It retrieves sites via XHR requests, and uses a custom rendering engine.

## Supported HTML Tags
html (full support)<br>
style (full support)<br>
head (full support)<br>
title (full support)<br>
meta (partial support)<br>
link (partial support)<br>
body (full support)<br>
p (full support)<br>
h1-h6 (full support)<br>
div (full support)<br>
pre (full support)<br>
span (full support)<br>
img (full support)<br>
audio (partial support)<br>
video (partial support)<br>
a (full support)<br>
button (full support)<br>
details (partial support)<br>
summary (full support)<br>
table (partial support)<br>
th (partial support)<br>
tr (full support) <br>
td (full support)<br>
noscript (full support)
script (partial support)
input (partial support)
textarea (full support)
form (partial support)
label (partial support)

## Supported CSS Features
flexbox (partial support)<br>
flex direction(full support)<br>
display(partial support)<br>
opacity (partial support)<br>
background-color (full support)<br>
color (full support) <br>
overflow (partial support)<br>
height (full support)<br>
width (full support)<br>
background (partial support)<br>
background-image (partial support) <br>
position (partial support)<br>
top (full support) <br>
left (full support) <br>
margin (full support) <br>
background-repeat (full support) <br>
background-size (partial support) <br>
background-position (partial support) <br>
border (partial support) <br>
border-color (full support) <br>
border-style (partial support) <br>
border-radius (full support) <br>
outline (partial support) <br>
cursor (partial support) <br>
font-size (full support) <br>
font-family (full support) <br>
font-weight (partial support) <br>
text-align (partial support) <br>
list-style-type (partial support) <br>
word-break (partial support) <br>
user-select (partial support, as -xillo-user-selectable)<br>
z-index (full support)

## Support CSS Color Formats
RGB (no alpha/RGBA)<br>
Hexidecimal (full support)<br>
HSL Colors (no alpha)<br>
Supported Color Names

## Supported CSS Color Names
red, orange, yellow, green, blue, purple, pink,<br>
magenta,lavendar,chucknorris,lime,brown,black,white,<br>
grey,gray,lightgrey,lightgray,lightbrown, peach, taupe,<br>
grass,crap

## Supported JavaScript Features
Audio (partial support) <br>
  loop (full support)<br>
  play (full support)<br>
  pause (full support)<br>
  currentTime(full support)<br>
  src(full support)<br>
  duration (full support)<br>
document (partial support)<br>
  createElement (full support)<br>
  getElementById (full support)<br>
  querySelector (full support)<br>
  querySelectorAll (full support) <br>
  title (full support) <br>
  cookie (full support) <br>
  documentElement (full support)<br>
  body (full support)<br>
Navigator(partial support)<br>
  userAgent (full support)<br>
  language (partial support)<br>
  languages (partial support)<br>
  onLine (full support)<br>
  appCodeName (full support)<br>
  appName (full support)<br>
  doNotTrack (full support)<br>
console (partial support)<br>
  log (full support)<br>
  warn (full support)<br>
  error (full support)<br>
  clear(partial support)<br>
Window (partial support)<br>
  innerWidth(full support)<br>
  innerHeight(full support)<br>
  isSecureContext(full support)<br>
  outerHeight (partial support)<br>
  outerWidth(partial support)<br>
  alert(full support)<br>
  prompt(full support)<br>
  confirm(full support)<br>
Element(partial support)<br>
  querySelector(full support)<br>
  children(full support)<br>
  parentNode(full support)<br>
  style(partial support)<br>
  appendChild(full support)<br>
  className (full support)<br>
  id (full support) <br>
HTMLAnchorElement(partial support)<br>
  href (full support) <br>
  target (full support) <br>
HTMLInputElement (partial support) <br>
  type (partial support)<br>
  value (partial support)<br>
  max (full support) <br>
  min (full support) <br>
  name (full support) <br>
  maxLength (partial support)<br>
  disabled (partial support) <br>
HTMLButtonElement (partial support) <br>
  disabled (full support)<br>
HTMLTextareaElement (partial support) <br>
  disabled (partial support)<br>
  value (full support)<br>
  name (partial support) <br>
HTMLFormElement (partial support)<br>
  submit (full support)<br>
HTMLVideoElement (partial support)<br>
  requestFullScreen(partial support)<br>
  playbackRate (partial support) <br>
  requestPictureInPicture (partial support)<br>
  paused (full support)<br>
  pause (full support) <br>
  play (full support) <br>
  volume (full support) <br>
  loop (full support) <br>
Array (partial support)<br>
  forEach (full support)<br>
  indexOf(full support)<br>
  slice(full support)<br>
  join (full support)<br>
String (partial support)<br>
  slice(full support)<br>
  indexOf(full support)<br>
  startsWith(full support)<br>
  endsWith(full support)<br>
  toUpperCase(full support)<br>
  toLowerCase(full support)<br>
localStorage (full support)<br>
sessionStorage (full support) <br>
Location (partial support) <br>
  href (full support) <br>
  hash (full support) <br>
  hostname (full support) <br>
  port (full support) <br>
  pathname (full support)<br>
  search (full support) <br>

## Secret Functions (Internal Pages Only, via the "xillo" module)

### bkm
Bookmark runtime
#### append (url:string,title?:string)
Creates bookmark
#### remove (title:string)
Removes bookmark

### priv
Privacy Runtime
#### scripts : boolean
Enables or disables JavaScript
#### dotr : boolean
Enables or disables Do Not Track
#### lsss : boolean
Enables or disables storing cookies via sessionStorage or localStorage
#### safem: boolean
Enables or disables the Secure Content policy
#### ofile : boolean
Enables or disables opening files

### cki
Cookie runtime
#### purge(url?:string)
removes all cookies (either from an origin or in general)
#### list(url:string):string[]
gets all cookies
#### rm (url:string,id:string)
removes a cookie

### thm
Theme runtime
#### drkm : boolean
Enables or disables Web Dark Theme
  
