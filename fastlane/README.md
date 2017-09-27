fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

## Choose your installation method:

<table width="100%" >
<tr>
<th width="33%"><a href="http://brew.sh">Homebrew</a></td>
<th width="33%">Installer Script</td>
<th width="33%">Rubygems</td>
</tr>
<tr>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS or Linux with Ruby 2.0.0 or above</td>
</tr>
<tr>
<td width="33%"><code>brew cask install fastlane</code></td>
<td width="33%"><a href="https://download.fastlane.tools">Download the zip file</a>. Then double click on the <code>install</code> script (or run it in a terminal window).</td>
<td width="33%"><code>sudo gem install fastlane -NV</code></td>
</tr>
</table>

# Available Actions
### bump_version
```
fastlane bump_version
```
Bump the app versions and tag a new release

----

## iOS
### ios build
```
fastlane ios build
```
Build the iOS app
### ios beta
```
fastlane ios beta
```
Submit a new iOS build to Apple TestFlight
### ios release
```
fastlane ios release
```
Submit a new iOS build to the Apple App Store (synonym for :beta)

----

## Android
### android build
```
fastlane android build
```
Build the Android app
### android beta
```
fastlane android beta
```
Submit a new Android build to the Google Play beta channel
### android release
```
fastlane android release
```
Submit a new Android build to the Google Play production channel

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
