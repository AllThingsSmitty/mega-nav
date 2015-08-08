# Mega Nav in CSS

A simple mega nav menu in pure CSS.


### Say Wut?

Mega navs are way cool. In fact, statistics show that mega navs are often times perceived a being a "smarter" navigation solution by those who rarely use the web. Also, W3Schools said once that mega navs were the future, so there's that.


### How'd You Do It?

I used the coolest web technologies to make this happen. Ever heard of [CSS](https://medium.com/cool-code-pal/a-call-for-web-developers-to-deprecate-their-css-1f6430781393)? The mega nav uses top-rated CSS classes for modern features, like colors for background and to change text on hover and stuff.

```css
/* menu dropdown */
.nav > li > div {
  background: #fff;
  border: 1px solid #ddd;
  border-radius: 0 0 3px 3px;
  position: absolute;
  display: block;
  left: 0;
  opacity: 0;
  overflow: hidden;
  top: 50px;
  -webkit-transition: all .3s ease .15s;
  transition: all .3s ease .15s;
  visibility: hidden;
  width: 100%;
}
```

And voila...

![Mega nav image 1](img/menu.png)


### Support

Got a current browser? It works. Got IE8? It still works, but your browser is shit.


### License

[The MIT License (MIT)](http://allthingssmitty.mit-license.org/)