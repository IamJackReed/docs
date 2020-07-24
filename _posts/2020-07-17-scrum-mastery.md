---
layout: post
title: "Scrum Mastery"
description: "We have started to curate and organise a collection of practical topics, techniques, tips n tricks to help with Scrum Mastery"
date:   2020-07-24 17:40:00 -0300
categories: Scrum Mastery
icon: 'book'
---
<h2 style="text-align: left;">Coaching &amp; Mentoring</h2>
<p><span style="text-align: left; padding-left: 8%; color: #0000ff;"><a href="https://www.scrum.org/resources/blog/how-build-trust-enable-agility">How to Build Trust to Enable Agility</a></span></p>
<p><span style="text-align: left; padding-left: 8%; color: #0000ff;"><a href="https://www.agilesocks.com/coaching-secrets-stop-being-helpful">Coaching Secret: Stop being so helpful</a></span></p>
<p><span style="text-align: left; padding-left: 8%; color: #0000ff;"><a href="https://www.scrum.org/resources/psychological-models-scrum">Psychological Models In Scrum</a></span></p>
<p><span style="text-align: left; padding-left: 8%; color: #0000ff;"><a href="https://www.scrum.org/resources/blog/do-you-know-any-coaching-patterns">Do You Know any Coaching Patterns?</a></span></p>
<p><span style="text-align: left; padding-left: 8%; color: #0000ff;"><a href="https://www.scrum.org/resources/blog/agile-coach-toolkit-5-active-listening">Agile Coach Toolkit no5: Active Listening</a></span></p>
<h2 style="text-align: left;">Done</h2>
<p><span style="text-align: left; padding-left: 8%; color: #0000ff;"><a href="https://www.scrum.org/resources/blog/getting-started-definition-done-dod/">Getting Started with a Definition of Done (DoD)</a></span></p>
<p><span style="text-align: left; padding-left: 8%; color: #0000ff;"><a href="https://www.scrum.org/resources/blog/walking-through-definition-done/">Walking Through a Definition of Done</a></span></p>
<p><span style="text-align: left; padding-left: 8%; color: #0000ff;"><a href="https://www.scrum.org/resources/blog/definition-done-should-include-definition-undone/">Definition of Done Should Include a Definition of Undo(me)</a></span></p>

<p><span style="text-align: left; padding-left: 8%; color: #0000ff;"><a href="https://www.scrum.org/resources/blog/myth-3-scrum-releases-are-done-only-end-sprint/">Myth 3: In Scrum, releases are done only at the end of the Sprint</a></span></p>

<h2 style="text-align: left;">Emergent Software Development</h2>
<h2 style="text-align: left;">Empiricism</h2>
<h2 style="text-align: left;">Evidence-Based Management</h2>
<h2 style="text-align: left;">Facilitation</h2>
<h2 style="text-align: left;">Forecasting &amp; Release Planning</h2>
<h2 style="text-align: left;">Leadership Styles</h2>
<h2 style="text-align: left;">Managing Technical Risk</h2>
<h2 style="text-align: left;">Optimising Flow</h2>
<h2 style="text-align: left;">Organisational Design &amp; Culture</h2>
<h2 style="text-align: left;">Product Backlog Management</h2>
<h2 style="text-align: left;">Product Value</h2>
<h2 style="text-align: left;">Scaling Scrum</h2>
<h2 style="text-align: left;">Scrum Artifacts</h2>
<h2 style="text-align: left;">Scrum Events</h2>
<h2 style="text-align: left;">Scrum Roles</h2>
<h2 style="text-align: left;">Scrum Values</h2>
<h2 style="text-align: left;">Sprint Goal</h2>


---

## Anti-Patterns
- [Which Best Practice Is Ruining Your Business?](https://hbr.org/2012/12/which-best-practice-is-ruining)



[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

ally convert to Markdown
  - Drag and drop images (requires your Dropbox account be linked)


You can also:
  - Import and save files from GitHub, Dropbox, Google Drive and One Drive
  - Drag and drop markdown and HTML files into Dillinger
  - Export documents as Markdown, HTML and PDF

Markdown is a lightweight markup language based on the formatting conventions that people naturally use in email.  As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as pla
### Tech


* [AngularJS] - HTML enhanced for web apps!
* [Ace Editor] - awesome web-based text editor
* [markdown-it] - Markdown parser done right. Fast and easy to extend.
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework [@tjholowaychuk]
* [Gulp] - the streaming build system
* [Breakdance](https://breakdance.github.io/breakdance/) - HTML to Markdown converter
* [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

### Installation

Dillinger requires [Node.js](https://nodejs.org/) v4+ to run.

Install the dependencies and devDependencies and start the server.

```sh
$ cd dillinger
$ npm install -d
$ node app
```

For production environments...

```sh
$ npm install --production
$ NODE_ENV=production node app
```

### Plugins

Dillinger is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |


### Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma test
```
#### Building for source
For production release:
```sh
$ gulp build --prod
```
Generating pre-built zip archives for distribution:
```sh
$ gulp build dist --prod
```
### Docker
Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the Dockerfile if necessary. When ready, simply use the Dockerfile to build the image.

```sh
cd dillinger
docker build -t joemccann/dillinger:${package.json.version} .
```
This will create the dillinger image and pull in the necessary dependencies. Be sure to swap out `${package.json.version}` with the actual version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on your host. In this example, we simply map port 8000 of the host to port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart="always" <youruser>/dillinger:${package.json.version}
```

Verify the deployment by navigating to your server address in your preferred browser.

```sh
127.0.0.1:8000
```

#### Kubernetes + Google Cloud

See [KUBERNETES.md](https://github.com/joemccann/dillinger/blob/master/KUBERNETES.md)


### Todos

 - Write MORE Tests
 - Add Night Mode

License
----

MIT


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
