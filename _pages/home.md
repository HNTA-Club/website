---
title: Yokoso!
permalink: /
layout: splash
header:
  overlay_image: /assets/images/dark_splash.jpg
  overlay_filter: 0.5
  cta_label: "Join us on Discord"
  cta_url: "https://discord.gg/uZJqHH7"
excerpt: "Welcome to the website of HeNTAi, an anime hobby club of Tampere University!"

intro:
  - excerpt: |
      **Our activities include:**
      <ul>
        <li>Watching anime in the clubroom or sometimes in lecture halls</li>
        <li>Hanging out at the clubroom</li>
        <li>Singing animekaraoke</li>
        <li>Occasional projects, like a building a giant mecha</li>
        <li>Hosting events, like grilling or sauna</li>
        <li>Attending events, like Tracon</li>
        <li>Watching movies in lecture halls</li>
      </ul>

club_info:
  - title: Clubroom
    image_path: /assets/images/clipart/cat_kotatsu_neko.png
    url: /clubroom
    excerpt: "We have a clubroom for hanging out and reading manga."
    btn_label: "Directions"
    btn_class: "btn--primary"
  - title: Discord
    url: https://discord.gg/uZJqHH7
    image_path: /assets/images/clipart/internet_mark.png
    excerpt: "We have a Discord for event updates and anime, manga, video game and other Japanese popular culture related discussion!"
    btn_label: "Discord"
    btn_class: "btn--primary"
  - title: Animekaraoke
    url: /karaoke
    image_path: /assets/images/clipart/karaoke_nessyou.png
    excerpt: "We sing animekaraoke, usually after the Friday anime viewing."
    btn_label: "List of songs"
    btn_class: "btn--primary"

current_series:
  - title: Anime viewings every Friday
    type: center
    excerpt: |
      We watch anime series on every Friday. <br />
      Viewings will be hosted in the clubroom or a lecture hall, 5 p.m. on Friday. <br />
      Animekaraoke usually afterwards! <br />
      Be sure to join our <a href="https://discord.gg/uZJqHH7">Discord</a> for any sudden changes in our plans. <br />
      The series we'll watch are down below!

  - image_path: https://image.tmdb.org/t/p/w600_and_h900_bestv2/31I6eGFgYbbn5FMwzxOVlZfYETW.jpg
    type: left
    title: Clevatess
    excerpt: |
      <a href="https://anilist.co/anime/178869/Clevatess-Majuu-no-Ou-to-Akago-to-Kabane-no-Yuusha">AniList Clevatess</a>

  - image_path: https://image.tmdb.org/t/p/w600_and_h900_bestv2/frgVn3ww547TVQH8vS2bWKZnEBu.jpg
    type: right
    title:  Ping Pong THE ANIMATION
    excerpt: |
      <a href="https://anilist.co/anime/20607/Ping-Pong-THE-ANIMATION/">AniList Ping Pong THE ANIMATION</a>

  - image_path: https://image.tmdb.org/t/p/w600_and_h900_bestv2/48KKO5QHkowaCVsEpKLdvrzir3a.jpg
    type: left
    title: Witch Watch
    excerpt: |
      <a href="https://myanimelist.net/anime/59597/Witch_Watch">MyAnimeList Witch Watch</a>

  - image_path: https://image.tmdb.org/t/p/w600_and_h900_bestv2/fcAKLwLJf6G8QaoGdJyxrVCHBnY.jpg
    type: right
    title: The Fragnant Flower Blooms with Dignity
    excerpt: |
      <a href="https://anilist.co/anime/181444/Kaoru-Hana-wa-Rin-to-Saku">AniList The Fragnant Flower Blooms with Dignity</a>

outro:
  - excerpt: Images courtesy of <a href="https://www.themoviedb.org/">TMDB</a>
---

{% include feature_row id="intro" type="center" %}
{% include feature_row id="club_info" %}
{% include current_series %}
{% include feature_row id="outro" type="center" %}