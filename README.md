# tv
### Playlists by category

<details>

<summary>Expand</summary>

<br>

<!-- prettier-ignore -->

<table>

  <thead>

    <tr><th align="left">Category</th><th align="right">Channels</th><th align="left">Playlist</th></tr>

  </thead>

  <tbody>

    <tr><td align="left">Animation</td><td align="right">26</td><td align="left" nowrap><code>https://github.com/akkradet/IPTV-THAI/raw/master/IPTV-THAI.m3u8</code></td></tr>

  </tbody>

</table>

</details>



### Playlists by region

<details>

<summary>Expand</summary>

<br>

<!-- prettier-ignore -->

<table>

  <thead>

    <tr><th align="left">Region</th><th align="right">Channels</th><th align="left">Playlist</th></tr>

  </thead>

  <tbody>

    <tr><td align="left">Africa</td><td align="right">215</td><td align="left" nowrap><code>https://github.com/akkradet/IPTV-THAI/raw/master/IPTV-THAI-V2.m3u8</code></td></tr>
  </tbody>

</table>

</details>

### Playlists by country

<details>

<summary>Expand</summary>

<br>

<!-- prettier-ignore -->

<table>

  <thead>

    <tr><th align="left">Country</th><th align="right">Channels</th><th align="left">Playlist</th></tr>

  </thead>

  <tbody>
    <tr><td align="left">🇦🇫 Afghanistan</td><td align="right">36</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/countries/af.m3u</code></td></tr>
  </tbody>

</table>

</details>
## For Developers

In addition to the above methods, you can also get a list of all available channels in JSON format.

To do this, you just have to make a GET request to:

```

https://iptv-org.github.io/iptv/channels.json

```

If successful, you should get the following response:

<details>

<summary>Expand</summary>

<br>

  

```

[

  ...

  {

    "name": "CNN",

    "logo": "https://i.imgur.com/ilZJT5s.png",

    "url": "http://ott-cdn.ucom.am/s27/index.m3u8",

    "categories": [

      {

        "name": "News",

        "slug": "news"

      }

    ],

    "countries": [

      {

        "code": "us",

        "name": "United States"

      },

      {

        "code": "ca",

        "name": "Canada"

      }

    ],

    "languages": [

      {

        "code": "eng",

        "name": "English"

      }

    ],

    "tvg": {

      "id": "cnn.us",

      "name": "CNN",

      "url": "http://epg.streamstv.me/epg/guide-usa.xml.gz"

    }

  },

  ...

]

```

</details>
