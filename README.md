### This is the fabled master repository for [munki](http://munki.googlecode.com/ "The Munki on Google Code") pkginfo files.
## _Collaborators wanted! Please help us maintain these submodules as updates come out!_

# **Notice: These will NOT work 'as-is'. See: [the official munki wiki](http://code.google.com/p/munki/wiki/PkginfoFiles "The Munki Wiki on Google Code") please test before putting into production, no warranty granted or implied**

### Checkitout: 
`git clone git://github.com/arubdesu/BarrelOfPkginfos.git`

`cd BarrelOfPkginfos`

`git submodule init`

`git submodule update`

To update, and for collaborators, ensure you're cd'd into the BarrelOfPkginfos folder and run: `git submodule foreach git checkout master`
That should only be necessary the first time. From then on, run this command to actually pull the updates:

`git submodule foreach git pull`