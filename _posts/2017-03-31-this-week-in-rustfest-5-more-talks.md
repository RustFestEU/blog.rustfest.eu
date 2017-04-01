---
layout: post
title: "This Week in RustFest -5: More talks announced"
socialImageSrc: '/assets/posts/2017-2nd-set-of-speakers.png'
authors:
  - badboy
  - hoverbear
---

## Grab your ticket

If you haven't got your ticket yet, you [should grab one as soon as possible](https://ti.to/asquera-event-ug/rustfest-kyiv).
There are still some left in Batch #2.

## More talks announced

By now we have all speakers confirmed and we used last week to announce five more talks.
[Follow us on twitter](https://twitter.com/rustfest) for more news in the coming days.

[![First round of speakers](/assets/posts/2017-2nd-set-of-speakers.png)](http://2017.rustfest.eu/talks/)


### Sōzu, a hot reconfigurable reverse HTTP proxy
_by [Geoffroy Couprie](http://2017.rustfest.eu/talks/#s%C5%8Dzu-a-hot-reconfigurable-reverse-http-proxy) (Geal)_

Could you write a Rust program that never, ever has to stop? Not even for configuration changes or binary upgrades? One that will handle the traffic for thousands of applications on many more virtual machines that get up and down at any time? The Sōzu HTTP reverse proxy is there to solve that problem. This talk will cover various parts of its architecture, from its streaming HTTP parser built with nom, its single-threaded worker handling events with mio, and all the associated tooling to command and control the proxy.

### Building SSH servers in minutes
_by [Pierre-Étienne Meunier](http://2017.rustfest.eu/talks/#building-ssh-servers-in-minutes) (pe_meunier)_

Thrussh is an SSH library for writing both clients and servers. It grew out of the need for a specialised SSH server, with very limited default permissions.

Thrussh uses Tokio, which allows it to be combined with other protocols easily, and asynchronously. Current projects using it include nest.pijul.com, where SSH is used to push and pull Pijul patches to repositories hosted there, and authentication is just a matter of checking a public key in an PostgreSQL database.

Now, why would anyone want to write such a library? Well, I’ll try to show why Rust convinced me that this was a good idea.

### GStreamer & Rust – A perfect match
_by [Sebastian Dröge & Luis de Bethencourt](http://2017.rustfest.eu/talks/#gstreamer-rust-a-perfect-match)_

GStreamer is a highly versatile, cross-platform, plugin-based multimedia framework that caters to the whole range of multimedia needs. It can be used basically everywhere, from embedded devices like phones, TVs or drones to desktop applications or on huge server farms.
In this talk we will discuss how Rust is the perfect match for GStreamer to evolve from its C roots and safely enter the future.

And who knows, maybe in the future we will have a GStreamer completely written in Rust?

### Taking Rust to Production: Lessons Learned From the Habitat Project
_by [Fletcher Nichol](http://2017.rustfest.eu/talks/#taking-rust-to-production-lessons-learned-from-the-habitat-project) (fnichol)_

The Rust language is more than ready for production–it excels at it! The Habitat project team has been using Rust for a year in public and an extra year in stealth. With over 40,000 lines of Rust code so far, we maintain multiple CLI applications, a cross-platform process supervisor, a gossip subsystem, and a micro service-oriented distributed build system.

Have no fear: there has never been a better time to use Rust for your next service, application, or tool!

### The Illustrated Adventure Survival Guide for New Rustaceans
_by [Liz Baillie](http://2017.rustfest.eu/talks/#the-illustrated-adventure-survival-guide-for-new-rustaceans) (_lbaillie)_

Programming is an adventure, often more harrowing than it has to be. If you’re more used to higher-level languages like Ruby or JavaScript, learning Rust can feel like an impossible journey that leaves you wishing for a well-written and heavily illustrated field guide.

Good news! I have already gone down this road and am now prepared to share my adventure with you. Luckily, I was able to capture much of the flora and fauna of Rustlandia with my primitive pictorial devices (paper and pen).
