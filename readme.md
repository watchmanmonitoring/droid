## This is the droid you're looking for

This repository is designed to help build a "Droid".. an external hard drive used in troubleshooting, and often performing data recovery on OS X based computers.


## Setup

Install a clean OS, created a user named `Droid`




- Install [Packages.app](http://s.sudre.free.fr/Software/Packages/about.html)

- Create a folder called `/Users/Shared/Development` for use as common starting ground in this package's scripts.

- Clone this repo*

```
git clone https://github.com/watchmanmonitoring/the-droid-you-are-looking-for.git /Users/Shared/Development/the-droid-you-are-looking-for
```

- Review the system wide settings to be applied in 

```
 /Users/Shared/Development/the-droid-you-are-looking-for/droid-prep/postinstallation 
```

- Install the suggested applications into /Applications

- Open `droid-prep.pkgproj` in `Packages.app` and remove any Applications you don't intend to bundle.

- Configure the Droid's user environment as desired.

- This command will strip data from the "droid" user account and build a package which preserves the setup.

```
/Users/Shared/Development/the-droid-you-are-looking-for/carbon-freeze.sh
```


*(If you'd rather tweak it yourself, consider Forking this, which would change the URL for cloning.


## What about autodmg | deploystudio | etc?

The process described in this repo is designed to get a person up and running with a usable external hard drive quickly. It is possible that some work environments may benefit from a more formal deployment, especially when something like autodmg or DeployStudio are already in use.

A major difference is that this package is designed for a technician's use as a diagnostic drive on the latest, perhaps beta, OS X. 