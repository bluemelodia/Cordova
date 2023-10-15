# Cordova

## Build the app
Build output is under /platforms/ios.

	cordova build ios

## Open the project in Xcode

	open ./platforms/ios/HelloCordova.xcworkspace

## Deploying to device

Pre-requisite: Modify build.json, with the correct value for developmentTeam. Under XCode > Signing & Capabilities > All > Signing (Debug) > iOS, hover over the (i) button under Provisioning Profile. Under the tooltip, you should see:

	Certificates: 1 Included
	Includes newest signing certificate "Apple
	Development: <e-mail address>
	(<development team>)".
