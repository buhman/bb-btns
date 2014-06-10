# BitBucket Buttons

Showcase your BitBucket (repo's) success with these three simple, static buttons featuring dynamic watch, fork and follower counts and a link to your BitBucket repo or profile page.

To get started, checkout <http://bb-btns.bitbucket.org>!


## Usage

These buttons are hosted via ButBucket Websites, meaning all you need to do is include an iframe and you're set. Once included, you can configure it with various options. Here's the include:

``` html
<iframe src="http://bb-btns.bitbucket.org/bitbucket-btn.html?user=USERNAME&repo=REPONAME&type=BUTTONTYPE"
  allowtransparency="true" frameborder="0" scrolling="0" width="62" height="20"></iframe>
```

### Requirements

`user` BitBucket username that owns the repo

`repo` BitBucket repository to pull the forks and watchers counts

`type` Type of button to show: `watch`, `fork`, or `follow`

### Optional

`count` Show the optional watchers or forks count: *none* by default or `true`

`size` Optional flag for using a larger button: *none* by default or `large`



## Examples

**Basic Watch button**

``` html
<iframe src="http://bb-btns.bitbucket.org/bitbucket-btn.html?user=mdo&repo=bb-btns.bitbucket.org&type=watch"
  allowtransparency="true" frameborder="0" scrolling="0" width="62" height="20"></iframe>
```

**Basic Fork button**

``` html
<iframe src="http://bb-btns.bitbucket.org/bitbucket-btn.html?user=mdo&repo=bb-btns.bitbucket.org&type=fork"
  allowtransparency="true" frameborder="0" scrolling="0" width="53" height="20"></iframe>
```

**Basic Follow button**

``` html
<iframe src="http://bb-btns.bitbucket.org/bitbucket-btn.html?user=mdo&type=follow"
  allowtransparency="true" frameborder="0" scrolling="0" width="132" height="20"></iframe>
```

**Watch with count**

``` html
<iframe src="http://bb-btns.bitbucket.org/bitbucket-btn.html?user=mdo&repo=bb-btns.bitbucket.org&type=watch&count=true"
  allowtransparency="true" frameborder="0" scrolling="0" width="110" height="20"></iframe>
```

**Fork with count**

``` html
<iframe src="http://bb-btns.bitbucket.org/bitbucket-btn.html?user=mdo&repo=bb-btns.bitbucket.org&type=fork&count=true"
  allowtransparency="true" frameborder="0" scrolling="0" width="95" height="20"></iframe>
```

**Follow with count**

``` html
<iframe src="http://bb-btns.bitbucket.org/bitbucket-btn.html?user=mdo&type=follow&count=true"
  allowtransparency="true" frameborder="0" scrolling="0" width="165" height="20"></iframe>
```

**Large Watch button with count**

``` html
<iframe src="http://bb-btns.bitbucket.org/bitbucket-btn.html?user=mdo&repo=bb-btns.bitbucket.org&type=watch&count=true&size=large"
  allowtransparency="true" frameborder="0" scrolling="0" width="170" height="30"></iframe>
```


## Completely copied and adapted from

(https://github.com/mdo/github-buttons)



## Author

**Earthware*

+ http://twitter.com/earthware
+ https://bitbucket.org/earthware



## Copyright and license

Original Copyright 2014 Mark Otto, Adaptions Copyright 2014 Earthware Ltd. Released under Apache 2.0.
