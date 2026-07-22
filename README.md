# NAME TBD
Webring for members of SCG. Inspired by [Roboring](https://github.com/stellophiliac/roboring/tree/main)

# How to join

1. Generate a [UUID](https://www.uuidgenerator.net/) for your site!

2. Add the folliwng links to your site:

  ```html
  <a href="https://ring.scg.wtf/UUID/previous"> <- </a>
  <a href="https://ring.scg.wtf/">roboring</a>
  <a href="https://ring.scg.wtf/UUID/next"> -> </a>
  ```

  3. Submit a pull request adding yourself to `websites.json`, or [contact me](https://rowdythecrux.dev)! 

  Pull requests should have the **name** of your site, your **UUID**, a short **description**, your **site link**, and a **contact link**!

  here's an example entry:

  ```json
  {
    "name": "My cool website!",
    "UUID": "3b8677fd-1175-4a51-938b-58c612d6b3fa",
    "about": "Cool site!",
    "url": "https://example.com/",
    "owner": "person@example.com"
  }
  ```

