---
layout: post
title: Up and running!
---

**What is this?**

An attempt at making Manjaro packages available for i686 systems after official support was removed.

Read more in our [forum](https://forum.manjaro.org/t/manjaro32-org/34634)

**How to use this?**

For now you can adopt to Manjaro-32 like this:
<pre><code>
sudo sed -i -e 's|stable|x32-unstable|g' /etc/pacman.d/mirrorlist
sudo pacman -Syy
sudo pacman -S archlinux32-keyring-transition
sudo pacman -Suu
</code></pre>

**Will it work?**

We are still at the beginning and some might change druing the process. So stay tuned ...
