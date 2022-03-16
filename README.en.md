<p align="center">
  <a href="//macacajs.github.io">
    <img
      alt="Macaca"
      src="https://macacajs.github.io/macaca-ecosystem/macaca-logo/svg/monkey.svg"
      width="200"
    />
  </a>
</p>

---

# Macaca

[中文版](README.md)

Macaca is an open-source automation solution for multi-platform.

---

## Macaca Core

At its core, Macaca is an end-to-end test automation framework consisting of clients, servers and drivers.

<p align="center">
  <img src="https://macacajs.github.io/assets/88fe9010gy1g1k8o53d0ej20wb0ggwgu.jpg" width="740px">
</p>

### Client

Macaca doesn't limit what languages you will use to write your tests. You can choose to write your tests in Node.js, Java or Python, using respective clients:
* Node.js client - [macaca-wd](https://github.com/macacajs/macaca-wd)
* Java client - [wd.java](https://github.com/macacajs/wd.java)
* Python client - [wd.py](https://github.com/macacajs/wd.py)

### Server

Macaca's core is a REST API web server. It connects with clients, listens for requesting, and executes request commands on a mobile device, and a desktop browser, responses with results conforming HTTP response protocol.

The beauty of a client/server architecture is that REST API and [W3C WebDriver Wire Protocol](https://www.w3.org/TR/webdriver/) opens the opportunities that test codes can be written any common languages, as long as it has a http client API. On the other hand, the server can be on a different machine, or in cloud.

### Driver

Macaca is "cross-platform". It means you can use the same API to write test scripts, and same test scripts to test your apps running on devices such as iOS, Android or desktops. To achieve this, we have drivers for different platforms:

* Macaca's [iOS WebDriver](https://github.com/macacajs/XCTestWD) is written in Swift and built in-house.
* Macaca's [Android WebDriver](https://github.com/macacajs/UIAutomatorWD) is built in-house, and supports Android UIAutomator 2.0.

Macaca supports major browsers such as Chrome, Firefox, Safari. It also supports electron environment.

## Native, Mobile, Hybrid

0. Native means apps written with iOS or android SDKs.
0. Mobile web means apps written in HTML, CSS and JavaScript and displayed via a mobile device browser such as Safari, Chrome or Webview in iOS and android.
0. Hybrid is apps created by webview in native app.
0. Web means apps written in HTML, CSS and JavaScript.

## Macaca Community Ecosystem

<p align="center">
  <img src="https://macacajs.github.io/assets/88fe9010gy1g1u1s0bzwsj20rz0kwtdx.jpg" width="740px">
</p>

### Macaca DataHub

<p align="center">
  <a href="https://macacajs.github.io/macaca-datahub/">
    <img
      alt="Macaca DataHub"
      src="https://macacajs.github.io/macaca-datahub/logo/logo-color.svg"
      width="128"
    />
  </a>
</p>

Macaca DataHub is a continuous data provider for development, testing, staging and production.

---

<p align="center">
  <img src="https://macacajs.github.io/macaca-datahub/assets/1556087321021-f5514eb2-62f6-484b-ad58-24433c7f8906.png" width="740px">
</p>

* [Website](https://macacajs.github.io/macaca-datahub/)
* [GitHub](https://github.com/macacajs/macaca-datahub)

### Reliable

<p align="center">
  <a href="https://macacajs.github.io/reliable/">
    <img
      alt="Macaca Reliable"
      src="https://macacajs.github.io/reliable/logo/reliable.svg"
      width="128"
    />
  </a>
</p>

Reliable is a testing management suite with continuous delivery support.

---

<p align="center">
  <img src="https://macacajs.github.io/reliable/assets/6d308bd9ly1fz3wii2wqsj21bh0u0qij.jpg" width="740px">
</p>

* [Website](https://macacajs.github.io/reliable/)
* [GitHub](https://github.com/macacajs/reliable)

### NoSmoke

NoSmoke is a cross platform UI crawler which generate and execute UI test cases.

<p align="center">
  <img src="https://macacajs.github.io/NoSmoke/assets/macaca-architecture-2.0.png" width="740px">
</p>

* [Website](https://macacajs.github.io/NoSmoke/)
* [GitHub](https://github.com/macacajs/NoSmoke)

### App Inspector

App-inspector is a mobile UI viewer in browser. View the UI in a tree view, and generate XPath automatically.

<p align="center">
  <img src="https://macacajs.github.io/app-inspector/assets/7dfcf2f7gw1f77ev6csw5g20s50iwe81.gif" width="740px">
</p>

* [Website](https://macacajs.github.io/app-inspector/)
* [GitHub](https://github.com/macacajs/app-inspector)

### Macaca UITest

Macaca UITest runs mocha in a browser environment.

<p align="center">
  <img src="https://macacajs.github.io/uitest/assets/6d308bd9gw1f6wsic5dmxj20rl0qqtbi.jpg" width="740px">
</p>

* [Website](https://macacajs.github.io/uitest/)
* [GitHub](https://github.com/macacajs/uitest)

### Macaca Reporter

Macaca Reporter is a reporter used for mocha and other frameworks.

<p align="center">
  <img src="https://macacajs.github.io/macaca-reporter/assets/6d308bd9gy1fivuatxep5j21kw13dgs6.jpg" width="740px">
</p>

* [Website](https://macacajs.github.io/macaca-reporter/)
* [GitHub](https://github.com/macacajs/macaca-reporter)

### Torchjs

Torchjs is an excellent unit testing framework for browser environment.

[gif demo](https://macacajs.github.io/torchjs/assets/6d308bd9gy1fiw8er0a5eg20zc0k0he0.gif)

* [Website](https://macacajs.github.io/macaca-reporter/)
* [GitHub](https://github.com/macacajs/macaca-reporter)

### UI Recorder

<p align="center">
  <a href="https://uirecorder.com/">
    <img
      alt="UI Recorder"
      src="https://raw.github.com/alibaba/uirecorder/master/logo.png"
      width="400"
    />
  </a>
</p>

UI Recorder is a zero cost UI test case recorder like Selenium IDE.

---

<p align="center">
  <img src="https://raw.github.com/alibaba/uirecorder/master/screenshot/shot1.png" width="740px">
</p>

* [Website](https://uirecorder.com/)
* [GitHub](https://github.com/alibaba/uirecorder)

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
