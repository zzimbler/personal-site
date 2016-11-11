## Personal Site Theme

---

What has inside?

- [Gulp](http://gulpjs.com/)
- [BrowserSync](https://www.browsersync.io/)
- [Stylus](http://stylus-lang.com/) with [BEM](http://getbem.com/) Methodology
- [SVG](https://www.w3.org/Graphics/SVG/)
- [Travis](https://travis-ci.org/)
- No JS

## Setup

1. [Install Jekyll](http://jekyllrb.com)
2. [Install NodeJS](https://nodejs.org/)
3. [Install Bundler](http://bundler.io/)
4. Fork the project [Indigo](https://github.com/sergiokopplin/indigo/fork)
5. Edit `_config.yml` with your data.
6. `bundle install`
7. `npm install`
8. `gulp`
9. open in your browser: `http://localhost:3000`

Images on project page created with : http://mockdrop.io

## Settings

You have to fill some informations on `_config.yml` to customize your site.

```
name: John Doe
bio: 'A Man who travels the world eating noodles'
picture: 'assets/images/profile.jpg'

url: http://YOURUSER.github.io
permalink: /:title/

analytics: 'UA-MYANALYTICS'
disqus: mydisqus
facebook: myfacebook
twitter: mytwitter
instagram: myinstagram
linkedin: mylinkedin
youtube: myyoutube
spotify: myspotify
github: mygithub
email: myemail@gmail.com
```

If you want pagination:
```
paginate: 5
paginate_path: "blog/:num/"
```

If you have some projects:
```
projects: true
```

---

## Based On Themes & Contributions From

- [siddhantjain](https://github.com/siddhantjain)
- [sergiokopplin](https://github.com/sergiokopplin

## License

[MIT](http://zzimbler.mit-license.org/) License © Zachary Zimbler
