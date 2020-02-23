# Maya Desktop v0.1.2 (beta)
---
***Run as many as infinite robots*** :robot: ***on your desktop. Powered by Node Red.***

Maya Desktop allows you manage your own mighty fleet of Node Red robots to run parallely on you device and have it managed easily through a simple dashboard. 

We are bringing in features to collaborate over building bots, sharing and monetize them soon. Stay tuned on that.

---
#### Introduction

Maya Desktop is a desktop variant of our bot marketplace and runtime platform for your desktop. Powered by Node Red, it’s built cross platform so you get the same experience running your deployments on PC, Mac or Linux, or your IoT devices or web.

Maya Desktop let’s you make workflow bots to automate your work, or make webforms, or an IoT server or all of them together. Maya Desktop derives it's power out of marketplace that let's you discover nodes, flows and plugins to sew together a software bot. Nodes are functional primitives of Node Red and Maya - its the smallest self-sustaining unit that can be deployed on to the platform, and a flow is a sequence of nodes stringed together to form a software bot. 

To start with you have some basic nodes that can immeditaely get get you started with many useful functions. You can search from thousands of community created nodes that are hosted by Node Red, or you can use the task defined plugins curated by Maya team to reduce your job of finding things on the marketplace and get going in a button's click.

#### Getting Started

You can download Maya Desktop from https://getmaya.co  and install it locally in your Mac, PC or Linux machines.

We are released for Linux with AppImage binary. To download head over to github [releases](https://github.com/mayahq/maya-desktop/releases) and get yourself the latest version of Maya Desktop.

Alternatively you can use your linux terminal to do the same.

```bash
$ wget https://github.com/mayahq/maya-desktop/releases/download/v0.1.2/maya-desktop-0.1.1-x86_64.AppImage
$ chmod +x maya-desktop-0.1.1-x86_64.AppImage
$ ./maya-desktop-0.1.1-x86_64.AppImage
```

Open the Maya App from your application browser, and you should be able to view are neat UI.

Maya Desktop let's you classify your work in Fleets of Bots. You can make any number of fleet from New Fleet button.

![](/readme/fleet1.gif)

You can then create any number of bots for each fleet.

![](/readme/MultiBot.gif)

Now you are ready to make your first flow, and as computer Gods have it, it's Hello World! You can drag and drop the nodes available in the panel to the left on to your editor plate and wire them together. Double clicking on any node opens up the information sidebar of the node which gives options on configuring the property of the node.

![](/readme/HelloWorld.gif)

Here is another example of making a little bigger bot, that as of now does nothing but tell from even numbers from odd.

![](/readme/flow2.gif)


### License & Copyrights