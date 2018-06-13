# Web App Manifest

## What are Web App Manifest

According to [Google Web Fundamentals](https://developers.google.com/web/fundamentals/web-app-manifest/)

> `The web app manifest` is a simple `JSON` file that tells the browser about your web application and how it should behave when '`installed`' on the users mobile device or desktop. Having a manifest is required by `Chrome` to show the `Add to Home Screen` prompt.

A typical manifest file includes information about the app name, icons it should use, the start_url it should start at when launched, and more.

### How to do the things:

* Create the `manifest.json` file.
* Tell browser about manifest file by add a link to all pages.
    - ```
    <link rel="manifest" href="/manifest.json">
    ```
* Key properties of `manifest.json` file
    - short_name or name
    - icons
    - start_url
    - background_color
    - display
    - orientation
    - scope
    - theme_color
* Splash Screen
* Test your Manifest

### Sources Over Web: 

1. [Google Web Fundamentals](https://developers.google.com/web/fundamentals/web-app-manifest/)
2. [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/Manifest)