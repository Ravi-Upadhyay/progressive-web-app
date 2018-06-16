# Service Workers __//TODO: Continue From Service Workers Lifecycle__

> Service workers essentially act as proxy servers that sit between web applications, the browser, and the network (when available). They are intended, among other things, to enable the creation of effective offline experiences, intercept network requests and take appropriate action based on whether the network is available, and update assets residing on the server. They will also allow access to push notifications and background sync APIs. Says MDN

## About this guide

Here We have two approaches to follow. One specifically to PWAs i.e. How service workers enables offline experience. Another, service workers in general. I am following two guides first one is GWFs which is more directed towards using service workers. Another is MDN, which is all about service workers.

### What are Service Workers Again

- A `service worker` is a script that runs in the background, separate from your web page.
- It responds to events, including network requests made from pages it serves.
- It has an intentionally short lifetime. 
- It wakes up when it gets an event and runs only as long as it needs to process it.
- It has limited access to APIs when compared to javascript run from context of a page.
- It can’t access the `DOM` but access things like the `Cache`, `Storage API`.
- It can make network calls using `Fetch API`.
- The `IndexedDB API` and `postMessage()` are also available to use for data persistence and messaging between the `service worker` and pages it controls.
- It is an event-driven `worker` registered against an origin and a path.

### Lifecycle of Service Workers

To understand service workers completely we may need to understand its life cycle. On a broad scope it constitute of three steps:

1. Download
2. Install
3. Activate

![Service Worker Life Cycle](https://github.com/Ravi-Upadhyay/progressive-web-app/blob/master/Guides/Images/ServiceWorkerLifeCycle.png)

### Sources on the Web

1. [Introduction to Service Workers, GWF](https://developers.google.com/web/fundamentals/primers/service-workers/)
2. [Service Worker API, MDN](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
3. [Service Workers Cookbook](https://serviceworke.rs/)



