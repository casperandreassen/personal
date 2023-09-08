---
title: "Experimenting with HTMX"
date: 2023-09-08T02:01:58+05:30
description: "Creating a simple todo app with HTMX and Go."
---

Like many others, I've recently come across an intriguing new technology known as HTMX. Over the past few weeks, it has been generating quite a buzz. What's particularly fascinating about HTMX is its ability to revolutionize the way we handle web applications. Essentially, HTMX offers an alternative approach to the traditional method of delivering a substantial JavaScript bundle (think React) to the user's browser.

Instead of relying on a JavaScript framework to fetch data from an API, perform rendering tasks, and manage the application's state, HTMX re-introduces a simple paradigm. In this paradigm, we maintain the application's state on the server side, and the server primarily communicates with the client by sending and receiving HTML and form data. Just like it was in the early days of the internet!

In simple terms, with HTMX, the server plays a central role in maintaining the application's state, and it responds to client's requests with HTML to refresh the user interface. This departure from the late client-heavy approach is both innovative and promising.

However, I won't delve into the intricate details of how HTMX operates in this brief introduction. If you're eager to explore this technology further and understand its inner workings, I encourage you to visit the official HTMX documentation, which can be found at https://htmx.org/docs/. There, you'll find a wealth of information to satiate your curiosity and allow you to dive into the world of HTMX.

## TODO App

To put HTMX to the test and gain a more concrete understanding of its capabilities, I decided to embark on a project: creating a simple Todo application. Additionally, I chose to implement basic user authentication to enhance the app's functionality and security.

If you're interested in examining the code for this project, you can find it on my [GitHub repository](https://github.com/casperandreassen/htmx-todo). This will give you a chance to explore the inner workings of the HTMX Todo app and potentially use it as a reference for your own projects.

Moreover, I've gone a step further and published a live demonstration of the HTMX Todo app. You can experience it firsthand by visiting https://htmx-todo-23.fly.dev/. Feel free to create an account and start experimenting with the Todo functionality. It's an excellent way to see HTMX in action and gain practical insights into its capabilities. So, go ahead, make some todos, and enjoy exploring this exciting technology!
