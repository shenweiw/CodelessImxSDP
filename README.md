# CodelessImxSDP
Codeless kext driver for Mac OSX

## Sign:

```
$ codesign -fs "Your Certificate" "CodelessImxSDP.kext"
```

```
$ codesign --verify -vvvv CodelessImxSDP.kext/

CodelessImxSDP.kext/: valid on disk
CodelessImxSDP.kext/: satisfies its Designated Requirement
```
```
$ codesign --display -vvvv CodelessImxSDP.kext/
```

## Install:

```
sudo cp -r CodelessImxSDP.kext /System/Library/Extensions/CodelessImxSDP.kext
sudo touch /System/Library/Extensions
```
