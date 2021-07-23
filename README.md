Wowchemy Widget for adding [Lottie animations](https://lottiefiles.com) and [animated stickers from Telegram](https://telegram.org/blog/animated-stickers) to your [Wowchemy](https://wowchemy.com) Site.

## 🌈 Add the Widget to your Site

1. Install the widget by referencing it in your `config/_defaults/config.yaml`:
   ```yaml
   module:
     imports:
       - path: github.com/rodrigoalcarazdelaosa/wowchemy-widget-hero-lottie
   ```
1. Create an instance of your widget in `home/`, for example let's create `home/my-widget.md`:
   ```markdown
   ---   
   widget: 'github.rodrigoalcarazdelaosa.hero-lottie'

   # This file represents a page section.
   headless: true

   # Order that this section appears on the page.
   weight: 1

   title: Hello
   ---

   Welcome to my new widget!
   ```
