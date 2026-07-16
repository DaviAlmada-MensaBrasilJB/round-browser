# Round Browser

An open-source browser with a simple interface, a custom protocol, and a search engine.

# What is and how does the protocol and search engine work?

`globe://` is a custom protocol that works similarly to HTTPS, using TCP sockets.
The search engine is **Globe Search**, another open-source project.
Globe Search works by connecting to the central server, searching for the indexed websites, and establishing a connection with the requested website's server. As shown in the
following diagram:

![Diagram](networkdiagram.png)
- The green "S" represents the **server**
- The blue "U" represents the **user**
- The overlapping "E"s represent the **external servers**

# How to publish my website?

Well, to publish your site, you need three things:
1. Your site
2. A server (which can be your own computer)
3. GPSA (Globe Protocol Search API), the "API" circle shown on the diagram above.
After that, you just need to complete some configuration steps and you're done!

# What languages does it use?
The core backend of the browser is written mostly in C++.
Websites will be built using HTML, CSS and Lua through a custom engine called WebLua.
There are two languages that are still on the drawing board.

# When will it be released?
I'm a solo developer, and it's difficult to develop a browser alone,
so the first stable version will take quite a long time to be released.
