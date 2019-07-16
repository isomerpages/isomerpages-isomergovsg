---
title: Configuration Options
permalink: /documentation/configuration-options/
---

All configuration files for an Isomer sites are stored as [`yaml`](https://yaml.org/) files (with a `.yml` file extension). Except for `_config.yml` which is in the parent directory of the repository, all other configuration files are in the `_data` folder.

## _config.yml

`_config.yml` is Jekyll's site-wide configuration file. All of Jekyll's [global configuration options](https://jekyllrb.com/docs/configuration/options/#global-configuration) can be used. There are also some Isomer-specific options. Documented below are the Isomer-specifc options and selected Jekyll configuration options.

* `title` - the title of your entire site. Typically, we use the name of your agency, event, or campaign
* `title-abbreviated` - anabbreviated version of the title
* `email` - the email address of the sitemaster
* `description` - a brief description of your organisation/event/etc. Used for SEO purposes
* `url` - the base hostname & protocol for your site, e.g. <https://www.isomer.gov.sg>. Note that it is important to include the `https://` portion of the URL in order for the sitemap generator and SEO system to work properly
* `feedback_form_url` - the URL to your <https://form.sg> feedback form
* `faq_url` - the permalink to your URL page
* `exclude` - files in your repository that should be excluded from appearing on the live site
* `homepage_hero_i_want_to` - set to `true` if you're using the dropdown menu call to action. Set to `false` if you're using the standard button call to action. Note that there will be no key highlights if you choose the dropdown menu.
* `homepage_resources` - set to `true` to display the resources section on the homepage.
* `resources_name` - the name of your resource room directory

## _data/homepage.yml

`homepage.yml` contains the configuration for your home page. We have temporarily placed some site-wide configuration in this file as well - we plan to move these configuration to `_config.yml` in the near future. We will advise and assist you when this migration happens.

* `favicon` - the path to your website favicon, in `.ico` format
* `agency-logo` - the path to your agency logo
* `google-analytics` - (optional) your Google Analytics tracking ID
* `ask-jamie` - (optional) your AskJamie site ID
* `shareicon` - the path to a 600px by 600px `png` image that will be displayed in Facebook and WhatsApp previews
* `show-reach` - (optional) set this value to `true` if you wish to have a link to [REACH](https://www.reach.gov.sg/) in the footer of the site. This option is turned off by default
* `hero-title` - the title on the banner on the home page
* `hero-subtitle` - the accompanying text to the title on the banner
* `hero-banner` - path to the background image for the banner

For the call to action on the banner, you have the choice between a button and a dropdown menu. For the button, the syntax is as follows:

```yml
button:
  - text: Learn More
    url: /who-we-are/
```

If you select the dropdown menu, remember to set `homepage_hero_i_want_to` to `true` in `_config.yml`. Note that there will be no key highlights if you choose the dropdown menu. The syntax for the dropdown menu is as follows:

```yml
hero-dropdown-text: "Prompt on the dropdown menu"

i-want-to:
  - title: selection one
    url: /aaa/option-one/
  - title: selection two
    url: /link-two/
  - title: selection three
    url: /relative/url/thing-three/
```

The key highlights section below is optional. Leave it blank to not show any key highlights on your site.

```yml
key-highlights:
  - title: Highlight A
    description: Important highlight A is important
    url: https://google.com
    external: true
  - title: Page A
    description: Page A is important too
    url: /page-A/
  - title: Dropdown A Content C
    description: Dropdown A Content C is v important
    url: /dropdown-A/content-C/
# You can place 1 more key highlight, up to a maximum of 4
```

The information section below is optional. Omit it to not show informational text after the banner and key highlights.

```yml
info-sections:
  - section-title: Title
    section-subtitle: A longer, more detailed subtitle
    section-description: Lorem ipsum sit amet dolors ambit lucium
    section-more-button: More Details
    section-more-button-url: /page-one/
    section-image-path: /images/photo1.jpg
  - section-title: Title 2
    section-subtitle: Another long, more detailed subtitle
    section-description: Lorem ipsum sit amet dolors ambit two
    section-more-button: Learn More
    section-more-button-url: /page-two/
    section-image-path: /images/photo2.jpg
```

The resources section below is optional. If you choose not to incoporate a resources section in your home page, remember to set `hompage_resources` to `false` in `_config.yml`.

* `resources-title` - the title of your resource room in a "human readable" format (capital letters and spaces are allowed)
* `resources-subtitle` - the subtitle to your resource room title
* `resources-more-button` - text to be placed on the link briging users to your resource room
* `resources-more-button-url` - the permalink of the resource room
