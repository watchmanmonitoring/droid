## This is the droid you're looking for

This repository is designed to help build a "Droid".. an external hard drive used in troubleshooting, and often performing data recovery on OS X based computers.


## Setup

Install a clean OS, log in as a temporary user named something other than `Droid`


- Install [Packages](http://s.sudre.free.fr/Software/Packages/about.html)

- Create `/Users/Shared/Development` for use as common starting ground in this package's scripts.

- Clone this repo*

`git clone https://github.com/watchmanmonitoring/the-droid-you-are-looking-for.git /Users/Shared/Development/the-droid-you-are-looking-for`


- Install the suggested applications into /Applications

- Open `droid-prep.pkgproj` in Packages.app and remove any Applications you don't intend to bundle.


*(If you'd rather tweak it yourself, consider Forking this, which would change the URL for cloning.


## What about autopkg|autodmg|deploystudio|etc?

This is designed to get a person up and running with a usable external hard drive quickly. It is very possible that your internal workflow may benefit from a more formal deployment.

A major difference is that this package is designed for a technician's use as a diagnostic drive on the latest, perhaps beta, OS X. 