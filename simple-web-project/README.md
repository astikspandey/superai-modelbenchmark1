# Simple Redirect Web Project

This project demonstrates a basic HTML, CSS, and JavaScript setup that automatically redirects users to a specified website.

## How it works

- When a user opens `index.html`, they see a message and are immediately redirected to [the target site](https://9000-firebase-studio-1749392988916.cluster-iktsryn7xnhpexlu6255bftka4.cloudworkstations.dev/?monospaceUid=705521).

## Customization

To change the redirect destination, edit the URL in `src/scripts/main.js`:

```javascript
window.location.href = "https://9000-firebase-studio-1749392988916.cluster-iktsryn7xnhpexlu6255bftka4.cloudworkstations.dev/?monospaceUid=705521";
```