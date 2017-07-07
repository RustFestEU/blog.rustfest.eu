---
layout: post
title: "Get in the Swing with the Libz Blitz Contest: Win Free Tickets to Zurich!"
authors:
  - hoverbear
---

Our incredible friends at Berlin's **[1aim](http://1aim.com/)**, along with some help from the <span id="glorification">venerable</span> Rust core team member **[Brian Anderson (brson)](https://github.com/brson/)**, are at it again with another way to help you get your butt to **Rustfest**, so you can mix, mingle and learn with other members of our community.

This time around, we're having a contest! It's part of the **[libz blitz](https://blog.rust-lang.org/2017/05/05/libz-blitz.html)**, and is focused on getting you familiar with some well-used crates, as well as more of our community members.

**Not an experienced Rust developer?** That's alright. Mentoring is available to help guide you through the process.

**What’s it like?** KodrAus recently posted about their experience with the initiative [here](https://www.reddit.com/r/rust/comments/6lkuyd/my_experience_with_the_libz_blitz/).

**What do you get to do?**

- Lead the evaluation of a qualifying crate **or** fix eight qualifying crate or cookbook issues. If you already contributed to the libz blitz that also counts!
- Finish your work before Aug. 31 and submit your application [**here**](https://goo.gl/forms/Sgb7aAfonSzxxQUj2)

**What do you get?**

- One RustFest Zurich **ticket**.
- **Hotel** accommodation from Sept. 29 to Oct. 2. *(Provided by 1aim)*
- Up to **150€** for EU and **250€** for non-EU participants toward your travel expenses (reimbursed post-conference, pending receipts)


**Note:** Only the **first 15** applications will be accepted. You'll be informed if you won within a few days of submitting your application.

**How to get started?**

- Decide if you want to do a crate evaluation, or work on issues.
- Pick a crate or issues from **[this list](https://internals.rust-lang.org/t/rust-libz-blitz/5184)**.
- Join <strong><a href="https://kiwiirc.com/client/irc.mozilla.org/?nick=libblitzer|?#rust-libs">#rust-libs</a><strong> to receive mentoring and advice.

**You** can also contact **Brian (brson on irc)** directly with questions.

The core activity of the **[libz blitz](lb)** is evaluating key Rust crates.

The community peforms the evaluations on the **[Rust internals forum](f)** under the leadership of a “crate evaluation lead.”

Heading up  a crate evaluation is a multi-week process that involves:

- Opening an internals thread to host the discussion.
- Soliciting others to assess the crate using **[Rust API guidelines](g)**.
- Ensuring the Rust API guidelines are evaluated.
- Soliciting new recipes for the **[Rust Cookbook](c)**.
- Filing resultant issues against the crate.
- Ensuring they are completed.
- Finally, finishing an evaluation to get a reward.

[lb]: https://internals.rust-lang.org/t/rust-libz-blitz/5184
[f]: http://internals.rust-lang.org/
[c]: http://github.com/brson/rust-cookbook

The libz blitz crate evaluations produce a handful of (typically) small-sized issues against each crate, as well as the cookbook. While each issue might only be a minor improvement, in aggregate they’re major upgrades to each crate, and ultimately, to the entire crate ecosystem.

Details about leading a crate evaluation can be found [here](https://internals.rust-lang.org/t/rust-libz-blitz/5184/80).

Ask on the thread, or contact **brson** with questions.

> *Note: This is our first time doing something like this, so we're excited to make mistakes and get messy with **you**.*

Again, big thanks to **1aim** and we’re excited to see them (and **you!**) at **RustFest** this year!

![1aim Logo](assets/sponsors/1aim.svg)

**[1aim](https://1aim.com/)** is redefining how buildings work and how we relate to the objects around us. They’re a people-centric company that combines excellence in mechanical, electrical and software engineering with an intelligent approach to design to create the best access control systems ever built. Each product has hardware, software and server infrastructure components. All product development is done in-house. Their flagship product is LightAccess Pro, the access control solution of the future.

In addition to 1aim’s sponsorship of **RustFest** the last 2 events, CTO **Yann Leretaille**, who's also the system architect, delivered a keynote presentation. **Want to join?** They’re **[actively looking](https://1aim.com/#careers)** to expand their team of developers to support their **Rust-powered backend**.

Based in Berlin, they are also behind the upcoming launch of the **[Good Technology Collective](http://goodtechnologycollective.com/)**, a group working to create awareness of the need for intelligent design and a global algorithm-literacy effort.

<script>
  const adj = [ "venerable", "honourable", "mighty", "wizened", "Right Honourable", "incredible" ],
        cycleTime = 4000;
  let cycleBrsonGlorification = () => {
    let brsonElem = document.getElementById("glorification");
    if (brsonElem) {
      brsonElem.innerHTML = adj[Math.floor(Math.random()*adj.length)];
    }
  }

  document.addEventListener("DOMContentLoaded", cycleBrsonGlorification);
  window.setInterval(cycleBrsonGlorification, cycleTime);
</script>
