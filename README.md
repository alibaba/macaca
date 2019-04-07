<p align="center">
  <a href="//macacajs.github.io">
    <img
      alt="Macaca"
      src="https://macacajs.github.io/macaca-logo/svg/monkey.svg"
      width="200"
    />
  </a>
</p>

---

# Macaca

[中文版](README.zh.md)

Macaca is an open-source automation test solution for native, hybrid, mobile web and web application on mobile and desktop platforms.

0. Native means apps written with iOS or android SDKs.
0. Mobile web means apps written in HTML, CSS and JavaScript and displayed via a mobile device browser such as Safari, Chrome or Webview in iOS and android.
0. Hybrid is apps created by webview in native app.
0. Web means apps written in HTML, CSS and JavaScript.

Macaca is "cross-platform". It means you can use the same API to write test scripts, and same test scripts to test your apps running on devices such as iOS, Android or desktops.

Macaca doesn't limit what languages you will use to write your tests.

---

## Features

0. Macaca has a [MIT license](https://opensource.org/licenses/MIT).
0. Macaca's [App Inspector](https://macacajs.com/app-inspector/) is web based.
0. Macaca's [iOS WebDriver](https://github.com/macacajs/XCTestWD) is written in Swift and built in-house.
0. Macaca's Android WebDrive is built in-house, and supports Android UIAutomator 2.0.
0. Macaca has built-in [UI recorder](https://macacajs.github.io/guide/recorder.html) functionality.
0. Macaca has built-in support for using [computer vision](https://macacajs.github.io/guide/computer-vision.html) to verify UI elements.
0. Macaca supports major browsers such as Chrome, Firefox, Safari.
0. Macaca follows [W3C WebDriver Wire Protocol](//www.w3.org/TR/webdriver/). It means Macaca has much better chances to be compatible with current and future web standard.

## Architecture

![](https://wx2.sinaimg.cn/large/88fe9010gy1g1k8o53d0ej20wb0ggwgu.jpg)

## Macaca Community Ecosystem

![](https://wx4.sinaimg.cn/large/88fe9010gy1g1u1s0bzwsj20rz0kwtdx.jpg)

## Macaca Concepts

### Server

Macaca's core is a REST API web server. It connects with clients, listens for requesting, and executes request commands on a mobile device, and a desktop browser, responses with results conforming HTTP response protocol.

The beauty of a client/server architecure, REST API and W3C WebDriver Wire Protocol opens the opportunities that test codes can be written any common languages, as long as it has a http client API. On the other hand, the server can be on a different machine, or in cloud.

Besides this Macaca's core, we call it `macaca server`,  Macaca's extra utility tool is also server/client centric, such as UI Inspector, computer vision tool.

### Session

Macaca uses session to accept and respond requests. A client initiates a session with Macaca server by sending `POST /session` request. Macaca server will response with this session with a `sessionId`. The further request needs to contain this `sessionId` to move forward.

### Client

Macaca doesn't limit what client you use. We provide [Node.js](https://macacajs.com/guide/nodejs.html), [Java](https://macacajs.com/guide/java.html) and [Python](https://macacajs.com/guide/python.html) API libraries to get you started quickly.

## Source Code

Source code is maintained in different repos within [macacajs](https://github.com/macacajs).

It is recommended to get started from the [official site](https://macacajs.github.io), since there are many repos in macacajs.

## Help and Support

- [Official Site](//macacajs.github.io)
- [Samples](//github.com/macaca-sample)
- [Roadmap](//macacajs.github.io/guide/roadmap.html)
- [Awesome](//github.com/macacajs/awesome-macaca)
- [Community Support](//macacajs.github.io/guide/support.html)

## License

The MIT License (MIT)
