# 🎫 Tour of itopia Spaces

## 👋 Welcome

In this tour, you'll explore a space and learn what's possible.

## 👀 Look around

What do you see?

### 🖥️ This IDE

You're currently reading this inside [VS Code](https://code.visualstudio.com/),
over a video stream, from your web browser.

VS Code itself is actually running somehwere in the cloud
(more specifically, in an ephemeral container on an auto-scaling itopia-managed cluster),
but you can simply use it in your browser like it's an on-demand web app.

Why does that matter? Compared to local IDEs...

- ⏳ cloud-based IDEs are faster,
because developers get more computing power and spend less time creating/maintaining personal environments.
- 🔐 video-streamed IDEs are more secure,
because codebases don't need to be downloaded onto developer devices.
- 💸 browser-based IDEs are cheaper for large teams,
because their hardware procurement requirements are decreased.

<!-- (a few browser tabs vs. an overheating laptop). -->

>Note: You can use nearly any IDE in this way -
[PyCharm](https://www.jetbrains.com/pycharm/),
[Eclipse](https://www.eclipse.org/ide/), etc. -
we have a variety of setups in our image catalog.
If our catalog is missing something you want,
try configuring it in one of your organization's private custom images.

### 📁 This repo

Another thing to notice is that this space automatically opened
[this tour repo](https://github.com/itopia-inc/spaces-tour),
and it's simply convenient to have those cloning & opening steps be automated.

>Note: You can configure nearly any Git repository to open on launch.
Additionally, you can connect to nearly any version control system once inside.

## 🖱️ Click around

Yes, your mouse works in here!

### 🌐 Browsers all the way down

Try clicking on one of the hyperlinks in this doc.

~ insert gif of that ~

You'll find that you can securely browse the internet
from inside a space,
which is especially useful for `localhost` (if you're a web developer)
and private network browsing (if your admins configure VPC peering).
Your admins can customize network traffic policies (allowlist & blocklist),
but by default all public internet traffic is allowed.

### ☝️ The window tray

To switch focus back to VS Code, you could simply click anywhere on the VS Code app.
However, you can also use the window tray.

Try hovering your mouse over the shadow at the top of the webpage -
you should see a tray/menu drop down, displaying all open windows.
Click on a window title to switch focus to that window (or minimize it, if it's already focused).

### 👈 IDE extensions

Try clicking on the Extensions icon to the left.
Then, search for "containers".
You should see a variety of extensions,
including by verified extension developers like Microsoft.

>Note: Extensions should work in all itopia-supported IDEs.

~ insert a gif of that ~

## 🧑‍💻 Play around

We've included a variety of fun projects in the folders adjacent to this file,
as well as all necessary runtimes pre-installed in this space for you.

Try getting some project(s) running, and see for yourself how it feels to work in a space!

~ insert a gif of each of the projects running ~

>Note: You can run Docker inside a space if your admin(s) allow it.
We've enabled Docker for all Test Drive spaces.

## ⏭️ Next steps

<!-- - Check out [the docs](https://documentation.itopia.com/hc/en-us/articles/4410355049883-Signing-up-for-a-new-organization). -->
- [Sign up](https://console.cloud.google.com/marketplace/product/itopia-public/itopia-spaces) for your free trial.
<!-- - Browse [the open-source image catalog](https://github.com/itopia-inc/spaces-images). -->
<!-- - Automate administrative tasks with [the Spaces CLI](https://github.com/itopia-inc/spaces-cli). -->
- TODO
