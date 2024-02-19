# Partytown JS in Webflow

Web workers only allow hosting scripts from the same origin to avoid XSS ( [more info](https://github.com/w3c/ServiceWorker/issues/940#issuecomment-280964703))

This project is an experiement to host the Service workers file on a CDN and try loading it using the [`importScripts`](https://github.com/w3c/ServiceWorker/issues/940#issuecomment-678745678) function