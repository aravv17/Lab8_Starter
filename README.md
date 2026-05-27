# Lab8-Starter

## Contributors:
**Arav Vyawahare**

### How are graceful degradation and service workers related?
- Service workers are one of the primary mechanism for implementing graceful degradation on the web. Graceful degrdation is the idea that web app should still function even if something goes wrong like a missing feature or slow connection. Service workers make this practical through a javascript file running in a background thread, separate from your page, acting as a proxy between your app and the network.
