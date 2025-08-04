# Talk: It's all about the ecosystem

## Abstract

You may or may not remember Steve Ballmer's famous "developers, developers, developers" cheer from the late 90's, but Microsoft has known something for a very long time that some OSS companies might learn from. When a tool or product exists in order to run third-party content -- that third-party content is the real value of your tool because without that content, there's no reason to buy the product.

Commercially supported open source projects often lose track of this real value. And all too often, they learn that hard fact after community-hostile decisions decimate their ecosystem. SaltStack learned this the hard way, so did Hashi, Chef, Redis, and others.

I'd like to talk about the idea that the ecosystem is the product and the thing that you build and sell only exists to support it. It's a subtle but important shift in mindset that I think helps keep focus on what's really important, and I'm using it to help direct the projects that I'm working on now.

This talk has been given at:

- https://cfp.cfgmgmtcamp.org/ghent2025/talk/R7CKYH/
- https://2025.fossy.us/schedule/presentation/351/


## Running the presentation

![Showoff Icon](https://github.com/binford2k/all_about_ecosystem/blob/main/_images/showoff-icon.png?raw=true)

This is a presentation written for the [Showoff presenter](https://binford2k.github.io/showoff/)
which is a tool originally written by [Scott Chacon](https://github.com/schacon),
and further developed by me and my team at Puppet for our education classes.
It has a lot of neat developer and user interactivity features and I hope someday
to get back to hacking on it.

Showoff is a Ruby application, so make sure you have Ruby and Bundler installed.
Then set up the environment and run the presentation like so,

```
$ bundle install
.....
$ bundle exec showoff serve
  -------------------------

  Your Showoff presentation is now starting up.

  To view it plainly, visit [ http://localhost:9090 ]

  To run it from presenter view, go to: [ http://localhost:9090/presenter ]

  -------------------------


== Sinatra (v2.2.3) has taken the stage on 9090 for development with backup from Thin
2025-08-04 15:23:51 -0700 Thin web server (v1.8.2 codename Ruby Razor)
2025-08-04 15:23:51 -0700 Maximum connections set to 1024
2025-08-04 15:23:51 -0700 Listening on 0.0.0.0:9090, CTRL+C to stop
```

Open one of the URLs provided. If you intend to present, then open the presenter
view and then click the `[Display Window]` button.

