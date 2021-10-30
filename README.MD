## What is this?

This Wordpress child theme is based on the excellent https://bootspress.com/ theme using the famous BootStrap framework.

This child theme is also using WebPack as it was explained in this (also excellent) article by Henner Setyono https://wptips.dev/webpack-in-wordpress/

Thanks for the original authors of both.

## Installation

1. Download Bootspress original theme in your Wordpress themes directory (https://wordpress.org/themes/bootspress/)
2. Clone this repository in your wordpress themes directory
You should have something like this

```
Your site root
├── …
├── wp-content
│   └── themes
│       ├── bootspress
│       └── bootspress-child
└── …
```

3. Go to the child theme directory and launch
$yarn install

4. `$yarn run dev`
or `$yarn run prod`

The `dev` option will use Browsersync and HMR while webpack is watching :)
Your site will be running at 
https://localhost:3000

## Important

Don't forget to edit `bootstrap-child/webpack.config.js` according to your own parameters. You can also add your own entry-points of course.

Alos, be aware that in my configuration, the rendered CSS and JS files are located in the `bootspress-child/dist folder`