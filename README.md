# Elate Theme
Elate is a one page portfolio for freelancers, designers, developers and even agencies based on the [original html5 theme](//freehtml5.co/elate-free-html5-bootstrap-template/).
This Lektor theme features several content sections, a contact form, a responsive portfolio grid with hover effects, a smooth parallax and animation effect on sections. Its packed with 4 ready to use styles.

## Installation

Inside the folder of your Lektor site run:

    $ cd themes
    $ git clone https://github.com/nucleusai/lektor-theme-elate

Add the themes variable to the .lektorproject file

```ini
[project]
themes = lektor-theme-elate
```

For more information read the official [setup guide](//www.getlektor.com/docs/themes/installing/) of Lektor.

## Getting started

After installing the Elate Theme successfully it requires a just a few more steps to get your site running.


### Configurations

Add params in the `.lektorproject file`

```ini
[theme_settings]

```

Create a `404.html/contents.lr` content file pointing to 404.html, using a none model [see Lektor docs](https://www.getlektor.com/docs/guides/error-pages)

Create a `contents.lr` content file pointing to index.html, using a none model

### Make the contact form working
> Not working yet

Since this page will be static, you can use [formspree.io](//formspree.io/) as proxy to send the actual email. Each month, visitors can send you up to one thousand emails without incurring extra charges. Begin the setup by following the steps below:

1. Enter your email address under 'email' in the `lektorproject`
2. Enable form by setting `enable` to `true` in contact settings
3. Upload the generated site to your server
4. Send a dummy email yourself to confirm your account
5. Click the confirm link in the email from [formspree.io](//formspree.io/)
6. You're done. Happy mailing!

### Nearly finished

In order to see your site in action, run Lektor's built-in local server.

    $ lektor server

Now enter [`localhost:1313`](http://localhost:1313/) in the address bar of your browser.

# Notes

- It's missing extra (pre/post) menu entries

## Contributing

Did you find a bug or have an idea for a new feature? Feel free to use the [issue tracker](//github.com/nucleusai/lektor-theme-elate/issues) to let me know. Or make directly a [pull request](//github.com/nucleusai/lektor-theme-elate/pulls).

## License

This theme is released under The MIT License (MIT). For more information read the [License](//github.com/nucleusai/lektor-theme-elate/blob/master/LICENSE.md).

## Acknowledgements

Thanks to

- [freehtml5.co](//freehtml5.co) for creating this theme
- [Lektor](//getlektor.com)
- [Hugo elate theme](//github.com/saey55/hugo-elate-theme)
