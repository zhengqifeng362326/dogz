# Dogz

## Why?What?How

### Why do we do it?

For most frontender, we always feel tired when we start to call the request from the back-end server.We hope that it's accord with the previous appointment and don't have any trivial diff. Unfortunately, it's so precious for us.

In our daily development, we have to done communication with backender every hour and moment(also a little bit exaggerate!!!) Imagine that, you are drinking a coffee in a sunny afternoon, a call breaks the moment suddenly.  "Hurry up, I have changed a field and you must adjust it in the page, Come back soon, pls!" Oh, no...

So, do we have any way to avoid this worst circumstance, we only want to focus on the functional coding. If the request has been changed, please announce me and help me to update to the latest version automatically.



### What problems did it solve?

- How can we generate the request function by a standard way?
- How do we know whether the backender has changed anything?
- Can we update the changed points automatically?
- Can it improve the efficiency in development?



### How to do this?

Firstly, I assume that our backend can supply the `swagger.json` to us. If them can't, please push them. I think you all will live it.

What;s the swagger? Let me refer to the official introduction.

> Simplify API development for users, teams, and enterprises with the Swagger open source and professional toolset. Find out how Swagger can help you design and document your APIs at scale.

Shortly, it's a standard json file for describing API. It includes every thing you may use in fetch request.



With this file, we can know to call the request to service and what parameters do we need to send and that response are we fetching?



SO, can we parse the swagger json into our font-end project? Yes, you can, just use this tool. It supports those features you're going to need it.



## Features

- **Faster**: Implementation by Rust, it's faster than other node tools naturally.
- **Code hinting**: Generate the hinting script, prompt the property of request when you call the function.
- **Increment update**: Not update the generation fully every time.
- **No broken change**: It will not affect your original code, please feel free to use it.
- **Visual Tools**: We support some visual tools for the purpose of easier to use it.