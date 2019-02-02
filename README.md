# CodelessImxSDP
Codeless kext driver for Mac OSX

Install:

sudo cp -r CodelessImxSDP.kext /System/Library/Extensions/CodelessImxSDP.kext
sudo touch /System/Library/Extensions

Sign:

codesign -fs "Your Certificate" "CodelessImxSDP.kext"
