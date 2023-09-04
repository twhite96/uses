<p align="center">
  <img src="assets/2.png" />
</p>

> What my gear is, what OS I am using, what editor, etc...
- [The Hardware](#the-hardware)
- [Software](#software)
- [Home Server](#home-server)
  - [Server software](#server-software)
  - [Racks on Racks...](#racks-on-racks)
- [I Use a lot of software, I admit](#i-use-a-lot-of-software-i-admit)

## The Hardware

Let’s start with my gear which you can find on [KIT](https://kit.co/tiffanywhite/my-office).

![](https://res.cloudinary.com/twhiteblog/image/upload/c_scale,w_1701/v1693794497/side-main.webp)

## Software

- [VS Code](https://code.visualstudio.com/)
  - I also use [Frontmatter](https://frontmatter.codes) as a markdown CMS right in VS Code.
- [Neovim](https://neovim.io/)
  - Plugins:
    - [NvChad](https://github.com/NvChad/NvChad)
  - [My neovim configs for macos](https://github.com/twhite96/neovim-configs)
- [Warp terminal](https://www.warp.dev/)
- Arc Browser for literally *everything*.
- [Alfred](https://www.alfredapp.com)
- Text Expander
- [Taskpaper](https://www.taskpaper.com/) for tasks.
- [Obsidian](https://obsidian.md) for Project management.
- [Fantastical](https://flexibits.com/fantastical) for scheduling. I pay for the premium version.
- [Sip for Mac](https://sipapp.io/) for a color picker
- [ScreenFlow](https://www.telestream.net/screenflow/overview.htm)
  - I use this to record videos for the whole hashtag build in public thing on LinkedIn.
- [StreamLabs OBS Software for Mac](https://streamlabs.com/)
  - Best OBS client on the Mac.
- [CleanShot X](https://cleanshot.com/) for the best screenshots you're going to get on any platform.

<hr />

## Home Server
Yeah I am running a home server of sorts, as my fascination with Home Assistant, InfoSec, and networking/network security continues to grow.

Below is a list of the hardware I use for the rack. Click the details button to see the softare I am running on the network for server and IoT purposes.

- [CyberPower Smart App LCD UPS System, 1500VA/900W, 8 Outlets, AVR, 2U Rack Tower](https://www.amazon.com/gp/product/B00HDODQYS?psc=1)
  - Having battery backup is important. This way if there is a black or brownout, you have enough juice to keep your system running until you can shut it down properly.
- [CyberPower CPS1215RMS Surge Protector, 120V/15A, 12 Outlets, 15ft Power Cord, 1U Rackmount Black](https://www.amazon.com/gp/product/B00077INZU?psc=1)
  - Ran out of outlets in the UPS
- [TP-Link 16 Port Gigabit Switch Smart Managed Switch](https://www.amazon.com/gp/product/B0797KPRPK?psc=1)
  - I have a couple of these TP-Link Switches, one unmanaged and another smaller managed switch. I want to separate different devices on different networks using a VLAN and other things.
- [NavePoint 9U Wall Mount Network Server 19 Inch IT Cabinet Rack Enclosure Glass Door Lock](https://www.amazon.com/NavePoint-Network-Server-Cabinet-Enclosure/dp/B01FKOW4LS/144-7175663-3493110?psc=1)
  - This is where I hold all the rack equipment
- [Synology 4 bay NAS DiskStation DS920+ Diskless 4-bay; 4GB DDR4](https://www.amazon.com/gp/product/B087Z34F3R?psc=1)
  - I *love* this thing. I have Homebridge running on it, I have Plex serving up stuff on it, and a dev instance of Home Assistant as well as a few Docker containers. Trying to figure out how to deploy a production app in a container[^4] and am using this to test out a few containers with small node apps in them.
- [Raspberry Pi 4 Model B (8gb)](https://www.amazon.com/gp/product/B08R87H4RR?psc=1)
  - I have a production Home Assistant instance running on this.
- [CanaKit Raspberry Pi 3 B+](https://www.amazon.com/CanaKit-Raspberry-Premium-Clear-Supply/dp/B07BC7BMHY)
  - I am running Pi-hole and WireGuard on this however I don't understand most of how Wireguard works so I bought a Swiss VPN with no ties to any government          
- [Intel NUC BXKit10i3 Home & Business Mini Desktop Black with Hub](https://www.amazon.com/gp/product/B09DCZQFF2?psc=1)
  - Moving Home Assistant to this as it is more powerful which means faster automations and load times.
- [Ubiquiti Dream Machine Pro](https://store.ui.com/collections/unifi-network-unifi-os-consoles/products/udm-pro)
  - Running a little server farm in here so why not.

> If you want more of an idea of my whole home lab setup, you can find it [on GitHub](https://homelab.tifflabs.org).


### Server software
Some of the software running on the servers

<details>
  <summary>Server Software</summary>
    <ul>
      <li><a href="https://www.proxmox.com/en/downloads/category/iso-images-pve/">Proxmox</a></li>
      <li><a href="https://ubuntu.com/download/server">Ubuntu Server</a></li>
      <li><a href="https://www.docker.com/">Docker</a></li>
      <li><a href="https://k3s.io/">k3s</a></li>
      <li><a href="https://www.home-assistant.io/">Home Assistant</a></li>
      <li><a href="https://tailscale.com/">Tailscale</a></li>
      <li><a href="https://store.ui.com/collections/unifi-network-unifi-os-consoles/products/udm-pro/">UniFi OS</a></li>
    </ul>
</details>


### Racks on Racks...

![](https://res.cloudinary.com/twhiteblog/image/upload/c_crop,w_1103,x_0,y_1978/v1693794497/rack.webp)


## I Use a lot of software, I admit

But I use ALL OF IT.

So this is my setup and what I am currently using. You can show me your dev setup on [Mastodon](https://hachyderm.io/@tiff).

![](https://res.cloudinary.com/twhiteblog/image/upload/c_scale,w_2094/v1693794869/new_room_and_lab-2023-08-07_i2ds2h.webp)