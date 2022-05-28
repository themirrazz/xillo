# Xillo
A basic XHR browser for Windows96


## How it works
It retrieves sites via XHR requests, and uses a custom rendering engine.

## Initial Release
This will support no CSS or JavaScript, and only support these basic HTML tags:
h1-h6,p,a,span,body,head,title,div,input,textarea,form,label,button,img,pre

Anchors only support the properties "href" and "target". The target must be the default (null) or "\_blank".

Forms only support the "method", "target", and "action" properties.

Images only support the "src","width",and "height" properties.
