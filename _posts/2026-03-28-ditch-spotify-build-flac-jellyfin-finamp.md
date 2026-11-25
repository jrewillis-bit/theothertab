---
layout: post
title: "Ditching Spotify: Building My Own FLAC Music Library with Jellyfin & Finamp"
category: "Technology"
description: "For years, I relied on Spotify like most people—instant access to millions of tracks, curated playlists, and zero effort. But there has always been a trade"
tags: ["digital ownership","finamp","flac","home server","jellyfin","library","linux","lossless audio","media server","music server","nas","self-hosting","spotify alternative","streaming"]
featured: false
cover: "/assets/images/decluttered-bytes/2026/03/file_000000006d387246bbfbd602b475e9a9.png"
cover_alt: "Ditching Spotify: Building My Own FLAC Music Library with Jellyfin & Finamp"
---

<h2 class="wp-block-heading">For years, I relied on Spotify like most people—instant access to millions of tracks, curated playlists, and zero effort. But there has always been a trade-off: you do not really own anything, audio quality is compressed, and your library effectively disappears the moment you stop paying.</h2>



<p>So I decided to take control.</p>



<p>This is how I built my own self-hosted music streaming setup using Jellyfin, FLAC files, and Finamp—and why I am not going back.</p>



<h2 class="wp-block-heading">Why Move Away from Spotify?</h2>



<p>Spotify is convenient, but it comes with a few big limitations. Audio quality still is not true lossless, you do not own your music, tracks can disappear due to licensing changes, and offline downloads are locked inside the app.</p>



<p>I wanted something different: lossless audio, full ownership of my library, a system that works without subscriptions, and a setup that still feels slick enough to use every day.</p>



<h2 class="wp-block-heading">The Goal: My Own Private Spotify</h2>



<p>The idea is simple. Store music as FLAC files, host it on a Jellyfin server, and stream it anywhere using Finamp.</p>



<p>The end result feels like having your own Spotify, but with better audio quality, proper offline access, no monthly fee, and complete control over your library.</p>



<h2 class="wp-block-heading">Building the Library</h2>



<p>I used a workflow based around scraping my playlists off Spotify and rebuilding them as FLAC files for my own collection. That let me keep the music I actually listen to, rather than starting from scratch.</p>



<p>The most important part of this stage is keeping everything tidy. A clean folder structure and proper metadata make a massive difference once Jellyfin scans the library.</p>



<pre class="wp-block-code"><code>Music/
  Artist/
    Album (Year)/
      01 - Track.flac</code></pre>



<p>I made sure artist names, album titles, track numbers, years, and artwork were all embedded properly. It takes a bit of effort up front, but it pays off later with a library that actually looks polished instead of messy.</p>



<h2 class="wp-block-heading">Setting Up Jellyfin for Music</h2>



<p>Jellyfin is usually talked about as a film and TV server, but it works brilliantly for music too. I added my music folder as a dedicated music library, let Jellyfin scan everything, and then checked that it was identifying albums and artists correctly.</p>



<p>One thing I would recommend is making sure your files are tagged well before the scan. Jellyfin works best when the underlying metadata is already solid. Embedded album art helps too, especially if you want the library to look good across apps.</p>



<h2 class="wp-block-heading">Finamp on My Phone</h2>



<p>Finamp is what made the whole setup feel complete. It is a dedicated Jellyfin music player for mobile, and it gives you that proper app-based experience rather than just opening the web interface on your phone.</p>



<p>Once connected to my Jellyfin server, Finamp gave me access to my entire library, playlists, album art, and offline downloads. I can stream music at home over Wi-Fi, use it remotely when I am out, or download playlists for offline listening.</p>



<p>That is the key difference for me. This is not just a folder of files sitting on a NAS. It actually feels like a modern music service, except it is one I control.</p>



<h2 class="wp-block-heading">Why I Prefer This Setup</h2>



<p>The biggest win is ownership. My music library is mine. It is not tied to a subscription, and it cannot disappear because a streaming service loses the rights to something.</p>



<p>The second win is audio quality. FLAC files sound excellent, and there is something satisfying about knowing I am listening to the full-quality version rather than a compressed stream.</p>



<p>The third win is curation. Instead of being pushed whatever the algorithm wants me to hear next, I am building a collection that reflects what I actually like.</p>



<p>That does mean giving up a few things. Spotify is still better for instant discovery, social sharing, and effortless access to absolutely everything. But for the music I really care about, my own setup is better.</p>



<h2 class="wp-block-heading">Storage Matters</h2>



<p>FLAC files are not small, so storage is worth thinking about. A single album can easily take up a few hundred megabytes, and a large collection will quickly grow into hundreds of gigabytes.</p>



<p>If you already have a NAS or home server, this is not a huge issue. If not, even a basic setup with a decent-sized drive can still hold a surprisingly large library.</p>



<h2 class="wp-block-heading">Is It Worth Doing?</h2>



<p>For me, definitely yes.</p>



<p>If you care about sound quality, like owning your media, and do not mind putting a bit of time into organising your library, this kind of setup is fantastic. Jellyfin gives you the server, Finamp gives you the mobile experience, and FLAC gives you the quality.</p>



<p>It will not be for everyone. Some people will always prefer the convenience of Spotify. But if you enjoy self-hosting and want more control over your music, it is hard to beat.</p>



<h2 class="wp-block-heading">Final Thoughts</h2>



<p>Moving away from Spotify and building my own Jellyfin music server has changed how I listen to music. I have gone from renting access to songs, to building a library I actually own. And with Finamp on my phone, I still get the convenience of a proper streaming app.</p>



<p>For me, that is the sweet spot: the convenience of modern streaming, with the control and permanence of owning my own collection.</p>



<p>If you have been thinking about doing the same, I would say start with your favourite playlists, keep your metadata clean, and get Jellyfin and Finamp working early. Once it clicks, it is hard to go back.</p>
