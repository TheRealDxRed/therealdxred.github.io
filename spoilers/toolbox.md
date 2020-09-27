# Toolbox

###**Software**
#### WSL Ubuntu - GNU/Linux running under Windows 10
A lot of the work I do on puzzles actually takes place on the command line. To me, it feels a lot faster than jumping around from website to website. An added benefit is that it lets me work on the go.

My go-to for WSL distros is Ubuntu. It comes with a lot of built-in tools, as well as the all-too-familiar `apt` package manager.

As of writing this, running `cat /etc/*-release` gives me:

	DISTRIB_ID=Ubuntu
	DISTRIB_RELEASE=20.04
	DISTRIB_CODENAME=focal
	DISTRIB_DESCRIPTION="Ubuntu 20.04.1 LTS"
	NAME="Ubuntu"
	VERSION="20.04.1 LTS (Focal Fossa)"
	ID=ubuntu
	ID_LIKE=debian
	PRETTY_NAME="Ubuntu 20.04.1 LTS"
	VERSION_ID="20.04"
	HOME_URL="https://www.ubuntu.com/"
	SUPPORT_URL="https://help.ubuntu.com/"
	BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
	PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
	VERSION_CODENAME=focal
	UBUNTU_CODENAME=focal

And `cat /proc/version` gives:

    Linux version 4.19.104-microsoft-standard (oe-user@oe-host) (gcc version 8.2.0 (GCC)) #1 SMP Wed Feb 19 06:37:35 UTC 2020

The important commands to know are `file`, `xxd`, `cat`, `zip`, `unzip`, `base64`, `sha1sum`, and either `vim` or `nano`. These should be able to get you through just about anything I make. It also doesn't hurt to read up a little on how to use the BASH command line.

#### qrencode - Command line QR code generator
I have this installed on Ubuntu and I use it to-- guess what?-- generate QR code images. There's no decode function, so this one isn't as useful for solving puzzles as it is for making them.

#### Paint.NET - Freeware image editor for Windows
This has all the functionality I'll realistically need for an image editor (barring pen support). If you have a Photoshop subscription, or are more comfortable with tools like GIMP or Krita, feel free to use that.

###**Concepts**
#### Ciphers
For as long as I can remember, I've been playing with ciphers. I started off with some basic symbol substitution ciphers, [Caesar ciphers](https://en.wikipedia.org/wiki/Caesar_cipher), and [Vigenère ciphers](https://en.wikipedia.org/wiki/Vigen%C3%A8re_cipher). I even still have a toy cipher wheel from when I was a kid.
One of my more recent favourites is the [book cipher](https://en.wikipedia.org/wiki/Book_cipher), in which you use numbers to reference the words in a book.
As an example, if I were to apply the numbers ``3-1 1-2 2-8 3-20`` to [this wiki's home page](index.md), I would get ``What is a Toolbox``

#### Mathematics
A lot of solutions for my puzzles stem from mathematics and programming. In some cases, you might find an equation you'll have to put a name to, or just solve outright. There also happens to be a lot of mathematics involved in music and poetry.

#### Redactions
Sometimes, you might find me using black (or white if you use dark mode) squared to cross out text I don't want you reading. For the most part, it's to keep myself from revealing too much of the story too early, but sometimes you'll have to find a way to fill that information in.
