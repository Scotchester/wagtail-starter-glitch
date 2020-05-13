# Wagtail Starter Kit

This project was created by following the "[Your first Wagtail site](https://docs.wagtail.io/en/v2.8/getting_started/tutorial.html)" tutorial in the Wagtail docs, up through the point at which [you first run the server and the welcome page appears](https://docs.wagtail.io/en/v2.5/getting_started/tutorial.html#start-the-server).

From here, you could continue following the tutorial to learn about basic Wagtail development, or use this as a starting point for quick demos or examples.

## Getting started

1. Remix this project
1. Open the console and run `python3 manage.py createsuperuser` to create an admin user for yourself
   - **Full disclosure:** I have already created my own superuser (`admin`) that is stored in the SQLite database in the source of this project. If you remix the project, I could theoretically log in with that user on _your_ project's public admin URL. If you are concerned about this, you can use your new superuser to change the `admin` user's password.
1. Click **Show** ➡️ **In a New Window** to view the welcome page
   - _Note:_ Due to cross-origin restrictions, the site will not render in iframes on `glitch.com` URLs, such as if you were to try and show it next to the code, or if you are looking at the [main project info page](https://glitch.com/~wagtail-starter).
1. Add `/admin` to the URL to log into the Wagtail admin interface (or click the link on the bottom right of the welcome page)
1. Hack away!

Feedback welcome! Find me at:
- [@scott_ish](https://twitter.com/scott_ish) on Twitter
- @scotchester on the [Wagtail public Slack group](http://docs.wagtail.io/en/latest/support.html#slack)
