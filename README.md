# iframe-resize-demo
Quick demo showing how to smoothly adjust an iframe's height to match its content. 

Live demo: https://yochannah.github.io/iframe-resize-demo/

This demo uses the postmessage API https://developer.mozilla.org/en-US/docs/Web/API/Window/postMessage to communicate between the iframe and the parent, sending the height of the internal page to the parent and then smoothly transitioning the iframe's height using css.
