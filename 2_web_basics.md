# Web Basics
This section will help you to understand some of the fundamental concepts around how web applications work. The content is easier to capture and discuss with [Slides](https://docs.google.com/presentation/d/1yY6XPY3Ngzq2Hd14oFZe2BN-kHF2KhkQwGWxtMJwZnE), so that's I've opted to use.

Now that we have a sense of how HTTP works, let's see some of the things we discussed in practice. 

## Enable Capturing Responses
1. Click **Proxy**
2. Click **Options**
3. Under **Intercept Server Responses**, click **Intercept responses based on the following rules:**

## Observing what happens when we go to a site
1. Click the **Intercept** tab
2. Click **Intercept is off** to turn intercept mode back on
3. In the burp browser, go to [https://google.com/](https://google.com/)
4. Observe that the first intercepted item is a request. Remember what we just talked about in terms of the various components that make up a request.
5. Click **Forward** to see the associated response.
6. Keep clicking **Forward** to see the various requests and responses that make up your browser communicating with google.com - it's probably a lot more complicated that you thought.
   
## HTTP History
It's a bit unwieldy to keep having to click **Forward** when you're getting a sense of how communication with a site works, so I'll show you an area that can be helpful when you want to get a sense for how the communication is happening between your browser and a web server.

1. Click **Intercept is on** to turn it off
2. Click **HTTP history** - this has a listing of all of the requests and responses you've accumulated
3. Click `#^` to get the order of requests in descending order. This is usually how I like to view web traffic.

Do feel free to spend time later trying this out with a number of sites that you regularly visit to get a sense for how they work.

At this point, you should feel free to move on to [Vulnerable Targets](3_vulnerable_targets.md).